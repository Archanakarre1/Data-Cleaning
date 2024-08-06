Project Oerview:
The Nashville Housing Data Cleaning Project involves cleaning and standardizing a dataset from a housing project to ensure consistency and accuracy. This dataset contains information about property sales in Nashville and requires several data cleaning steps, including standardizing date formats, filling in missing values, breaking down address fields, and more. The goal of this project is to prepare the data for further analysis and ensure it meets high data quality standards.

Data Cleaning:
The data cleaning process is divided into several key steps:
1) Standardize Date Formats
2) Convert SaleDate to a standard Date format and handle any inconsistencies.
Populate Missing Property Address Data
3) Fill in missing PropertyAddress values using available data from the same table.
4)Break Down Address into Individual Columns
5)Split the PropertyAddress into separate columns for Address, City, and State.
6)Handle Owner Address Data
7)Similarly, split OwnerAddress into Address, City, and State.
Standardize Values
8)Convert values in the SoldAsVacant field from 'Y'/'N' to 'Yes'/'No'.
9)Remove Duplicates
10)Identify and remove duplicate records from the dataset.
11)Delete Unused Columns
12)Remove columns that are no longer needed for analysis.
13)Advanced Data Import (Optional)
14)Includes methods for importing data using OPENROWSET and BULK INSERT for future use.
