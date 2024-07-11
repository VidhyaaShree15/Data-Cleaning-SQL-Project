# Nashville Housing Data Cleaning Project using SQL

This repository contains SQL scripts used for cleaning and processing the Nashville Housing data. The project includes various data cleaning tasks such as converting data types, populating missing data, splitting address fields, standardizing values, and removing duplicates.

## Project Description

The SQL scripts perform the following tasks:
1. Convert `SaleDate` to `DATE` data type.
2. Populate missing `PropertyAddress` using other records with the same `ParcelID`.
3. Split `PropertyAddress` and `OwnerAddress` into separate columns for address, city, and state.
4. Standardize `SoldAsVacant` field values from 'Y'/'N' to 'Yes'/'No'.
5. Remove duplicate records based on specific criteria.

## SQL Scripts

- `nashville-housing-data-cleaning.sql`: Contains all SQL queries used for data cleaning.

## Contact

For any questions or feedback, please contact Vidhyaa Shree Rajakumar at vidhyaashreerajkumar15@gmail.com

