* Veda Technology - Data Cleaning and Preprocessing

** Project
Titanic Dataset

** Tools Used
- Python
- Pandas

** Data Cleaning Performed

1) Missing Values
- Age: 177 missing values were filled using the median value, which was 28.
- Cabin: Missing values were replaced with "Unknown".
- Embarked: 2 missing values were filled with "S", the most common value.

2) Duplicate Rows
- Checked the dataset for duplicate rows.
- No duplicate rows were found.

3) Data Types
- Checked the data types of all columns.
- The data types were correct, so no major changes were needed.

4) Text Cleaning
- Embarked values were converted to uppercase.
- Extra spaces were removed from the Name column.

5) Outliers
- Checked Age and Fare values.
- Some Fare values were high, but they were kept because they may be valid values.

6) Final Check
- No missing values remain.
- No duplicate rows remain.
- Final dataset contains 891 rows and 12 columns.

7) Output
The cleaned dataset is saved as `train_cleaned.csv`.

## GitHub Repository
This repository contains the cleaned Titanic dataset and documentation of the data cleaning process.
