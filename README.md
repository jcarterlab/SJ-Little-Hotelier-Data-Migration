# SJ-Little-Hotelier-Data-Migration

This notebook creates a pipeline that transforms 356 of Saint James hostel's reservations from an Excel bookings sheet into an xlsx file that can be bulk uploaded into the Little Hotelier property management system. Averages taken from Saint James employees indicate that this script saved over 7 hours of manual work. It also uncovered a number of existing human errors in booking entries and likely prevented further mistakes through the manual entry  of data while balancing reception duties. 

The main challenges included:

- reassigning the check-in dates on current bookings that fell before the upload date (07/11/2023)
- splitting first and last names
- assigning room type names based on existing room names
- correctly detecting and renaming the sources of reservation

<br/>

The notebook can be found [here.](SJ_Little_Hotelier_Data_Migration.ipynb)
