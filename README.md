# SJ-Little-Hotelier-Data-Migration

This notebook creates a pipeline that transforms 356 of [Saint James](https://www.saint-james-hostel.co.uk) hostel's reservations from an Excel bookings sheet into an xlsx file that can be bulk uploaded into the [Little Hotelier](https://www.littlehotelier.com) property management system. Averages taken from Saint James receptionists indicate that this script saved over 7 hours of manual work. It also uncovered a number of existing human errors and likely prevented further mistakes that would have occurred throught the manual entry of data while attempting to balance reception duties. 

The main challenges included:

- reassigning the check-in dates on current bookings that fell before the upload date (07/11/2023)
- splitting first and last names
- assigning room type names based on existing room names
- correctly detecting and renaming the sources of reservation

<br/>

The notebook can be found [here.](SJ_Little_Hotelier_Data_Migration.ipynb)
