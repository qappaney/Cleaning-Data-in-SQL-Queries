# Cleaning-Data-in-SQL-Queries
This project focuses on cleaning and standardizing real estate data from a Nashville Housing dataset using SQL.The goal is to prepare the data for better usability in analysis and reporting. The following steps highlight the key processes and techniques applied in this project:

Key Features:
Date Standardization:

Added a new column to store sale dates in a standardized format.
Handling Null Values:

Replaced null values in the PropertyAddress column by referencing related records in the dataset.
Splitting Address Components:

Separated PropertyAddress and OwnerAddress into distinct components such as Address, City, and State for better data granularity.
Field Value Normalization:

Converted SoldAsVacant field values from Y/N to Yes/No for readability.
Duplicate Removal:

Identified and removed duplicate records using a Common Table Expression (CTE) and the ROW_NUMBER() function.
Dropping Unnecessary Columns:

Removed unused columns (OwnerAddress, TaxDistrict, etc.) to optimize the dataset.
This project demonstrates how to apply various SQL techniques such as:

Using CTEs for deduplication.
Applying string functions (SUBSTRING, CHARINDEX, PARSENAME) for data transformation.
Conditional updates with CASE statements.
Leveraging JOIN operations to handle null values.
The cleaned dataset is now structured, standardized, and ready for further analysis or visualization in business intelligence tools.

