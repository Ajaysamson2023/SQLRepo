  **SQL Assignments:**

**Data Base Creation_Q1:**

- Created a simple table Locations including columns country_id,country_name and region_id by SQL query.
- Renamed the table Locations to Locations_new. 
- Added a column region_name to the table locations. 
- Added a column ID to the table locations. 
- Added a column state_province after region_id to the table locations. 

**Constraints_Q2**

- Created the  table with (agent_name,agent_code,working_area).
- Created a table to achieve UNIQUE constraints for ord_num.
- Checked the UNIQUE values on more columns.
- Query to check constraint for commission column.
- Query  to check constraint using alter table statement
- Query to check constraints on multiple columns using AND,OR.

**Distinct where clause query_Q3**

- Created a table named Salesman with columns Salesman_id, Name, City, Commission.
- Selected Salesman_id column as primary key and using identity for auto increment.
- Used distinct clause to get the unique name of the city.
- Used <''>  to get all the city names except paris.
- Used where,AND to get the city records with commission>0.14 and city is paris.
- Used order by asc to get the records of the commission in ascending order.

**Aggregate FunctionsQ4**

- Restored the database from AdventureworksDW2019.
- sorted the Lastname from the Dimcustomer table.
- Used the TOP clause to get the top 20 products from dimproduct table.
- Used top and percent to get the 50 percentage of customers from DimCustomer table. 
- Used  max and min functions to get the maximum and minimum yearly income from the DimCustomer.

**Unions**

- Created department table with mentioned data and inserting values.
- Apply Join on Employee and Department tables using the common column DeptID.
- SQL query to display Dname, Avg. salary of Each dept. using Joins and Group by Clauses. 
- Used AdventureWorksDW2019 database..
- SQL query to display FirstName and BirthDate and birthdate should be between 01-01-1985 to 01-12-1985 from DimCustomer and DimEmployee tables using Union and Union all functions.

**Joins**
- Created Employee_details table and ProjectDetail table and inserting values in to it. 
- Get employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for those employee which have assigned project already. 
- Get employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for all employee even they have not assigned project.
- Get all project name even they have not matching any employeeid, in left table, order by firstname from "EmployeeDetail" and "ProjectDetail". 
- Get complete record(employeename, project name) from both tables([EmployeeDetail], [ProjectDetail]), if no match found in any table then show NULL.
