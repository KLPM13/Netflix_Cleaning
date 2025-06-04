Netflix Data Cleaning Summary

1. Removed duplicate rows based on title and show_id.
2. Filled missing values in director, cast, and country columns with "Unknown".
3. Filled and Converted the missing and "UR" Value in rating column with "Not Rated".
4. Converted date_added to proper date format.
5. Standardized text in type, rating, and listed_in columns using PROPER and TRIM.
6. Split genres into multiple columns for clarity.
7. Removed leading/trailing spaces from all text fields.
8. Put data value in its proper column.
   we can see here that the input is not on the right column(Rating)
  ![image](https://github.com/user-attachments/assets/ed74def8-2858-4fcc-b5f5-4dd135bbd388)
  after the cleaning process we put the data in its designated column and fill the blank cells in Rating column.
  ![image](https://github.com/user-attachments/assets/f06c6ab0-2b7b-4aa1-8df6-d42d52051dd1)


Tools used: Excel functions (TRIM, PROPER, IF, TEXT TO COLUMNS, REGEXREPLACE), Remove Duplicate, Create Filter, Split Text To Column, Remove White Spaces
