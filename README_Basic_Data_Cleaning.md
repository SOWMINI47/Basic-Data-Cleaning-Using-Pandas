# Basic Data Cleaning Using Pandas

## Project Overview
This project demonstrates a practical data-cleaning workflow using Python and Pandas. A sample student performance dataset is inspected and cleaned by handling missing values, removing duplicate records, correcting data types, and exporting the cleaned dataset.

## Objective
Combine fundamental data-cleaning techniques into one practical workflow.

## Tools
- Python
- Pandas
- Google Colab / Jupyter Notebook

## Dataset
The sample dataset contains `Student_ID`, `Name`, `Age`, `Marks`, and `Attendance`. It intentionally includes missing values, a duplicate record, and a numeric column stored as text.

## Cleaning Steps
1. Inspect dataset structure, data types, missing values, and duplicates.
2. Remove duplicate records using `drop_duplicates()`.
3. Fill missing names with `Unknown`.
4. Fill missing ages with the median and missing marks with the mean.
5. Convert attendance to a nullable integer and ensure age and marks are numeric.
6. Verify missing values and duplicates after cleaning.
7. Export the cleaned data to `cleaned_student_dataset.csv`.

## How to Run
1. Download `Basic_Data_Cleaning.ipynb`.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook** and upload the notebook.
4. Select **Runtime → Run all**.
5. Download `cleaned_student_dataset.csv` from the Colab Files panel.

## Key Functions
`info()`, `isnull()`, `duplicated()`, `drop_duplicates()`, `fillna()`, `to_numeric()`, and `to_csv()`.

## Learning Outcomes
- Identify missing values and duplicate records.
- Apply basic missing-value strategies.
- Correct data types for analysis.
- Verify and export cleaned data.

## Conclusion
This project shows how Pandas can be used to improve data quality before further analysis.
