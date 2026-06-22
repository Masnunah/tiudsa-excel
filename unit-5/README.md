# Project: Excel / Data Cleaning

## What I did

* Downloaded a messy HR or customer dataset from Kaggle
* Saved the dataset as an Excel `.xlsx` workbook
* Kept the original dataset in a `Raw Data` sheet
* Created a separate `Cleaned Data` sheet for the cleaned version
* Removed duplicate rows from the dataset
* Removed extra spaces from text using the `TRIM()` formula
* Fixed inconsistent text casing using the `PROPER()` formula
* Removed completely blank rows
* Corrected columns stored as the wrong data type, such as numbers stored as text
* Created a separate `Cleaning Log` sheet to document all cleaning actions

## Files / Links

* `Customer_Data_Cleaning.xlsx`

## How to Run / Verify

1. Download and open `Customer_Data_Cleaning.xlsx`
2. Check the `Raw Data` sheet to see the original unchanged dataset
3. Check the `Cleaned Data` sheet to see the cleaned version of the dataset
4. Verify that duplicate rows were removed
5. Check text columns to confirm that extra spaces were removed using `TRIM()`
6. Check text columns to confirm that capitalization was fixed using `PROPER()`
7. Check that completely blank rows were removed
8. Check numeric columns to confirm that numbers stored as text were converted into proper number format
9. Open the `Cleaning Log` sheet to see the list of issues found and actions taken

## Notes / References

* Dataset source: Kaggle messy HR or customer dataset
* `TRIM()` was used to remove unnecessary spaces from text values
* `PROPER()` was used to make text casing consistent
* Duplicate rows were removed using Excel’s Remove Duplicates tool
* Blank rows were removed from the cleaned dataset
* Wrong data types were corrected where needed, such as converting text-formatted numbers into real numbers
* All cleaning steps were documented in the `Cleaning Log` sheet
* The original data was preserved in the `Raw Data` sheet for comparison
