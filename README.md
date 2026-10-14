# Data Visualisation and Communication — CA1

## Project Overview

This project explores employment and wage statistics for three technology-related occupations in the United States:

- Software Developers
- Data Scientists
- Computer and Information Research Scientists

The analysis uses May 2023 data from the U.S. Bureau of Labor Statistics (BLS). A second dataset for May 2022 is used to compare employment and wage distributions over time.

## Research Focus

The notebook investigates:

- How employment levels differ across the three selected occupations.
- How each occupation contributes to the combined employment total.
- How total employment and mean annual wages compare across occupations.
- How mean annual wages vary across U.S. state-level areas.
- How employment changed between May 2022 and May 2023.
- How the distribution of mean annual wages across geographic areas differs between 2022 and 2023.

## Visualisations

The notebook contains the following visualisations:

1. **Bar chart — Total Employment Comparison Across Tech Roles:** compares national employment estimates for the three occupations.
2. **Pie chart — Employment Share by Technology Role:** shows each occupation's share of the combined employment total for the selected roles.
3. **Scatter plot — Employment and Mean Annual Wage:** compares national employment estimates and mean annual wages.
4. **Box plot — State-Level Wage Distribution:** compares the distribution of mean annual wages across state-level records for the three occupations.
5. **Interactive scatter plot — Employment and Mean Annual Wage by Occupation and State:** explores the relationship between employment and mean annual wages across geographic areas.
6. **Line chart — Employment Trend by Technology Role (2022–2023):** compares national employment estimates between May 2022 and May 2023.
7. **Interactive histograms — Salary Distribution Comparison (2022 vs 2023):** compares how geographic-area records fall into mean annual wage intervals for each occupation and year.

Each visualisation is followed by Markdown discussing its objective, the reason for selecting the chart type, and the main findings.

## Data Sources

The datasets are from the U.S. Bureau of Labor Statistics, Occupational Employment and Wage Statistics (OEWS):

- May 2023: https://www.bls.gov/oes/tables.htm
- May 2022: https://www.bls.gov/oes/tables.htm

The workbook files used by the notebook are:

- `all_data_M_2023.xlsx`
- `all_data_M_2022.xlsx`

These source data files are required to run the notebook and are not included in the Moodle notebook submission unless the assessment instructions explicitly request otherwise.

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly Express

## Project Files

Keep the following files in the project directory:

```text
CA1_Data_Visualisation_and_Communication/
├── CA1_Data_Visualisation_and_Communication.ipynb
├── all_data_M_2022.xlsx
├── all_data_M_2023.xlsx
└── README.md
```

The notebook loads the Excel workbooks using relative file paths, so the notebook and both workbooks need to be in the same directory.

## How to Run the Notebook

1. Install Python and Jupyter Notebook, for example through Anaconda.
2. Place the notebook and both Excel workbooks in the same folder.
3. Open the notebook in Jupyter.
4. If any required package is missing, install it in the active environment:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly openpyxl
   ```

5. Run the notebook cells from top to bottom. The May 2023 and May 2022 workbook sheet names used by the notebook are `All May 2023 data` and `All May 2022 data`.

## Interpretation Notes

- The national comparison uses the selected occupation records for the U.S. and the cross-industry category.
- The state-level charts use the dataset's state-level area filter.
- The histograms show the number of geographic-area records within wage intervals. They do **not** show the number of individual workers earning those wages.
- The 2022–2023 comparison covers two annual snapshots (May 2022 and May 2023), not a continuous time series. The results should not be interpreted as proof of the cause of any employment or wage changes.

## Assessment and Presentation

The notebook is the main assessment artefact and includes the analysis, code, visualisations, Markdown explanations, and references.

Before submission, replace the video placeholder in the first notebook cell with the shareable Google Drive link to the screen recording. Set the video's sharing permission to **Anyone with the link**. Include the GitHub repository URL in the first notebook cell as required by the assessment brief.

Any use of AI must be declared in the required appendix, including the exact prompts and relevant outputs, and a reflection on Delegation, Description, Discernment, and Diligence. The final submission should accurately distinguish AI-assisted learning/troubleshooting from work completed independently and follow the lecturer's instructions.

## References

U.S. Bureau of Labor Statistics (2023) *May 2023 National Occupational Employment and Wage Estimates*. Available at: https://www.bls.gov/oes/tables.htm (Accessed: 8 October 2026).

U.S. Bureau of Labor Statistics (2022) *May 2022 National Occupational Employment and Wage Estimates*. Available at: https://www.bls.gov/oes/tables.htm (Accessed: 8 October 2026).
