# Task 19 — Filter Dataset Records Using Pandas

## Project Overview

This project demonstrates how to filter records from a dataset using Python and Pandas. It applies numerical, categorical, and combined conditions to retrieve relevant student records.

## Objectives

- Filter records using Boolean conditions.
- Combine conditions using AND (`&`) and OR (`|`).
- Apply both numerical and categorical filters.
- Display filtered DataFrames.
- Count records returned by each condition.

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## Dataset Description

The project uses a manually created student performance dataset containing 12 fictional student records and six columns:

- Student ID
- Name
- Department
- Age
- Marks
- Attendance

## Filtering Examples

1. Students with marks greater than or equal to 85.
2. Students with marks greater than or equal to 80 and attendance greater than or equal to 85.
3. Students with marks greater than or equal to 90 or attendance greater than or equal to 95.
4. Computer Science students with marks greater than or equal to 90.

## Key Pandas Concepts

- Boolean indexing
- DataFrame filtering
- Comparison operators
- AND and OR conditions
- Parentheses for combining conditions
- Counting filtered records

## Sample Results

| Filtering Condition | Matching Records |
|---|---:|
| Marks >= 85 | 6 |
| Marks >= 80 AND attendance >= 85 | 7 |
| Marks >= 90 OR attendance >= 95 | 4 |
| Computer Science AND marks >= 90 | 3 |

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. Review the filtered DataFrames and record counts.
4. Download the notebook and CSV dataset.

## Project Files

- `Task_19_Filter_Dataset_Records.ipynb` — Notebook and code.
- `student_performance.csv` — Sample dataset.
- `requirements.txt` — Required Python libraries.
- `project_report.pdf` — Formatted project report.
- `screenshots/` — Execution evidence.

## Conclusion

This project demonstrates how Pandas can retrieve relevant records using one or more conditions. It provides practical experience with Boolean indexing and conditional data filtering.
