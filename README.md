Netflix Data Cleaning Summary

1. Removed duplicate rows based on title and show_id.
2. Filled missing values in director, cast, and country columns with "Unknown".
3. Filled and Converted the missing and "UR" Value with "Not Rated".
4. Converted date_added to proper date format.
5. Standardized text in type, rating, and listed_in columns using PROPER and TRIM.
6. Split genres into multiple columns for clarity.
7. Removed leading/trailing spaces from all text fields.

Tools used: Excel functions (TRIM, PROPER, IF, TEXT TO COLUMNS, REGEXREPLACE), Remove Duplicate, Create Filter, Split Text To Collumn, Remove White Spaces
