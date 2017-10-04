# JSPInsertDataWebApp
JSP Web App that inserts data into MySQL db. 


This is a web application using Java Server Pages that will allow a user to enter a first name and last
name into a MySQL database. For this project, the db used was one that was pre-provided upon installation
of MySQL (sakila). 

The table in which data was added to for testing was "film" with variables "actor_id", 
"first_name", "last_name", and "last_update" all being updated as data was being entered. The actor_id is 
auto-incremented, with first and last names of the Actors going in their respective columns. A timestamp
is created and inserted into the "last_update" column each time data is entered. 

After the data is successfully entered into the db, a message will pop up saying "Data Inserted!"
This template can be modified to other databases w/ different variables. 