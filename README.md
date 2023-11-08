# SJ-Little-Hotelier-Data-Migration

This notebook creates a pipeline that transforms 356 of Saint James hostel's reservations from an Excel bookings sheet into an xlsx file that can be bulk uploaded into the Little Hotelier property management software platform. The main challenges included:

- reassigning the check-in dates on current bookings that fell before the upload date (07/11/2023)
- splitting first and last names
- assigning room type names based on existing room names
- correctly detecting and renaming the sources of reservation

<br/>

The notebook can be found [here.](SJ Little Hotelier Data Migration.ipynb)
