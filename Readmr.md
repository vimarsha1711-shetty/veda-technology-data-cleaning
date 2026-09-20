Data Cleaning and Preprocessing - Titanic Dataset

I used the Titanic dataset for this task. First, I checked the data for missing values, duplicate rows, wrong data types and other problems.

1) Missing Values:
- Age had some missing values, so I filled them using the median value, which was 28.
- Cabin had many missing values, so I replaced them with "Unknown".
- Embarked had 2 missing values, so I filled them with "S", which was the most common value.

2) Duplicate Values:
- I checked the dataset for duplicate rows.
- There were no duplicate rows.

3) Data Types:
- I checked the data types of all the columns.
- The data types looked correct, so no major changes were needed.

4) Text Cleaning:
- I changed the Embarked values to uppercase.
- I removed extra spaces from the Name column.

5) Outliers:
- I checked the Age and Fare values.
- Some Fare values were high, but I did not remove them because they can be real values.

6) Final Check:
- After cleaning, there were no missing values.
- There were no duplicate rows.
- The final dataset has 891 rows and 12 columns.

The cleaned dataset is saved as train_cleaned.csv.