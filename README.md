
User Story 1
As a user, so I can see what bookmarks I have saved I want to be abble to see a list of the bookmarks.
See Excel file for domain model

---------------------
SQL - To set up database
1) Connect to psql
2) Create the database using the psql command CREATE DATABASE bookmark_manager;
3) Connect to the database using the pqsl command \c bookmark_manager;
4) Run the query we have saved in the file 01_create_bookmarks_table.sql


SQL - Setting up the test database (to pass the rspec tests)
1) Connect to psql
2) Create the database using the psql command CREATE DATABASE bookmark_manager_test;
3) Connect to the database using the pqsl command \c bookmark_manager_test;
4) Run the query we have saved in the file 01_create_bookmarks_table.sql
CREATE TABLE bookmarks(id SERIAL PRIMARY KEY, url VARCHAR(60));