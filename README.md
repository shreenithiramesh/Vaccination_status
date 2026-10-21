# Vaccination Status Data Analysis and Visualization

## 1. Project Overview

The main objective of this project is to analyse vaccination status data using Python and data visualization techniques. The project focuses on understanding vaccination status distribution, examining submission trends, identifying missing values and duplicate records, and analysing data over time.

The project uses an Excel dataset named `vaccination_status_clean.xlsx`. Python libraries are used to process the data, perform statistical analysis, and create meaningful visualizations.

The results help present the available vaccination records in a clear and understandable format.

## 2. Dataset

The dataset used in this project is `vaccination_status_clean.xlsx`. It contains 33 records and 4 columns in the `in` worksheet.

The columns are:

- **submitted_at:** Records the date and time when the information was submitted.
- **vaccination_status:** Indicates the vaccination status reported in the record.
- **vaccination_status_code:** Contains the corresponding code for the vaccination status.
- **name:** Contains the name associated with each record.

The dataset is used to analyse vaccination status categories and submission patterns. Data quality checks are performed to identify missing values, duplicate records, and invalid dates.

## 3. Tools Used

The following tools and technologies are used in this project:

- **Python:** The primary programming language for data analysis.
- **Google Colab:** An online environment for writing and executing Python code.
- **Pandas:** Used to load, process, clean, and analyse the Excel dataset.
- **Matplotlib:** Used to create charts and visual representations.
- **Seaborn:** Used to create statistical visualizations.
- **OpenPyXL:** Used by Pandas to read Excel `.xlsx` files when required.

These tools provide a simple and effective workflow for analysing structured data and generating visual reports.

## 4. Analysis Performed

### 4.1 Vaccination Status Analysis

The vaccination status categories are counted to determine the number of records in each category. A bar chart named `vaccination_status.png` is created to compare the counts.

### 4.2 Vaccination Percentage Analysis

The percentage distribution of vaccination status categories is calculated. A pie chart named `vaccination_percentage.png` represents the proportion of records in each category.

### 4.3 Submission Trend Analysis

The `submitted_at` column is converted into a datetime format. The number of submissions is grouped by date and visualized using a line chart named `submission_trend.png`.

This visualization helps identify dates with more or fewer recorded submissions.

### 4.4 Monthly Analysis

The submission dates are grouped by month and the number of records in each month is calculated. A bar chart named `monthly_analysis.png` is generated to compare monthly submission activity.

### 4.5 Data Quality Analysis

The dataset is checked for missing values, duplicate rows, and invalid submission dates. Vaccination status values and their corresponding status codes can also be compared to identify inconsistencies.

These checks help assess the quality and reliability of the dataset before interpreting the results.

## 5. How to Run

Follow these steps to execute the project in Google Colab.

1. Open Google Colab at https://colab.research.google.com/.
2. Create a new Python notebook.
3. Upload the file `vaccination_status_clean.xlsx` using the Files panel.
4. Install any required libraries if they are not already available.
5. Import Pandas, Matplotlib, and Seaborn.
6. Load the Excel dataset using `pd.read_excel()`, specifying the `in` worksheet.
7. Run the data exploration and data quality checks.
8. Execute the visualization code to generate the four charts.
9. Save the charts as PNG files and download them for the project report.

The generated output files are:

- `vaccination_status.png`
- `vaccination_percentage.png`
- `submission_trend.png`
- `monthly_analysis.png`

## 6. Conclusion

This project demonstrates how Python can be used to analyse and visualize vaccination status data stored in an Excel file. The analysis covers vaccination status distribution, percentage distribution, submission trends, monthly submission activity, and basic data quality checks.

The visualizations make it easier to understand the structure of the dataset and identify patterns in the available records. Data quality checks also help identify issues that may require further investigation.

Overall, the project provides practical experience in data preprocessing, exploratory data analysis, and visualization using Python. However, the findings describe only the records available in the dataset and should not be interpreted as vaccination coverage estimates for a wider population without additional representative data.
