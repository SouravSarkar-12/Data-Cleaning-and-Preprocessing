# Data-Cleaning-and-Preprocessing

I have used Mall Customer Segmentation Dataset, on which I have tried to used multiple functions to clean the dataset. 

I worked on Python and these are the summarized points


  1. Data types: Ensured age is int, by using dtype function.
  2. Missing values: used df.isnull().sum(), to find out out the no. of missing values. And no nulls were found.
  3. Duplicates: df.drop_duplicates() - for removing duplicate cells. Any duplicate rows were removed.
  4. Text standardization: I have used .strip() to remove whitespaces and .lower() to convert all astring to lowercase. gender values are now in lowercase (male, female).
  5. Date formatting: There were no date column.
  6. Column names: Cleaned and converted to lowercase with underscores (e.g., annual_income_k_).
