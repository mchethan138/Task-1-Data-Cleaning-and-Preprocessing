# Task-1-Data-Cleaning-and-Preprocessing

Imported the dataset using pd.read_csv() from Pandas.
Explored the dataset using info(), duplicated().sum(), and isnull().sum() to understand its structure and check for missing or duplicate values.
Identified 24 missing values in the income column.
Displayed rows with missing values using df[df.isnull().any(axis=1)].
Handled missing values in the income column by replacing them with 0 using fillna(0).

Standardized text values (like those in the education and Marital_Status  column) using string methods:
  str.strip() to remove extra spaces,
  str.lower() to convert text to lowercase,
  str.title() to capitalize the first letter of each word.
Applied similar string operations to clean column headers by converting them to lowercase.
Converted the dt_customer column from object type to datetime format using pd.to_datetime() for easier date-based analysis.
