Netflix Data Cleaning Summary

1. Removed duplicate rows based on title and show_id.
2. Filled missing values in director, cast, and country columns with "Unknown".

   before the cleaning process the data have a lot of null/blank values.

   
   ![image](https://github.com/user-attachments/assets/5634585e-1323-4cd9-aff1-6b001602ec43)


   
   after cleaning we fill the blank values with "Unknown".

   
   ![image](https://github.com/user-attachments/assets/f491ffa1-7971-4b27-885e-56256c4080a6)


4. Filled and Converted the missing and "UR" Value in rating column with "Not Rated".

   Before cleaning the data:

   
     ![image](https://github.com/user-attachments/assets/aa1434b3-0086-4fc4-9567-6819bf9a7875)
   

   After cleaning the data: The data now is very consistent and ready to use for analysis.

   
      ![image](https://github.com/user-attachments/assets/01b24d54-3305-4b4d-8732-42c31eb6224a)


6. Converted date_added to proper date format.
   

   Before Cleaning the data the date is not in proper date format

   
   ![image](https://github.com/user-attachments/assets/786d49b6-412f-4320-a7fc-78215f2124b2)


   after we clean the data we use the proper date format

   
      ![image](https://github.com/user-attachments/assets/084f8a7b-0e9d-4709-bc7f-d504eff6bf72)



8. Standardized text in type, rating, and listed_in columns using PROPER and TRIM.
9. Split genres into multiple columns for clarity.
10. Removed leading/trailing spaces & inconsistent from all text fields.

    
   We can see here that the country have coma(,) in front.

   
   ![image](https://github.com/user-attachments/assets/d953ac66-636f-44fd-a9f4-ca8909357e8c)

   
   after using REGEXREPLACE we are able to remove the coma in front of the value.

   
   ![image](https://github.com/user-attachments/assets/543773cc-6e22-4c4f-8cf1-42ecf9568e96)



         
11. Put data value in its proper column.

   
   we can see here that the input is not on the right column(Rating)

   
  ![image](https://github.com/user-attachments/assets/ed74def8-2858-4fcc-b5f5-4dd135bbd388)

  
  after the cleaning process we put the data in its designated column and fill the blank cells in Rating column.

  
  ![image](https://github.com/user-attachments/assets/f06c6ab0-2b7b-4aa1-8df6-d42d52051dd1)



Tools used: Excel functions (TRIM, PROPER, IF, TEXT TO COLUMNS, REGEXREPLACE), Remove Duplicate, Create Filter, Split Text To Column, Remove White Spaces
