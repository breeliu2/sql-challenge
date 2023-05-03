# sql-challenge

## Challenge Instructions
This challenge utilizes Data Engineering and Data Analysis to create a SQL database of employees who worked at a corporation called Pewlett Hackard from the 1980s and 1990s. Provided with only six CSV files that contain the data of the employees, the task is as follows: 
* Design tables to hold the data
* Import data into a SQL database 
* Answer questions about the data

## Data Modeling
First, is to inspect the data in the CSV files and create an Entity Relationship Diagram. Quick DBD was used for this. 
![QuickDBD-export](https://user-images.githubusercontent.com/124847109/235824694-e1fc867b-266d-4fcf-ba6f-19de6f86f65e.png)

## Data Engineering 
Then, using the information from the ERD, create a table schema for each CSV file and specify data types, primary keys, foreign keys, and other constraints. 
Import each CSV file into the corresponding SQL table in the same order that the tables were created. 

## Data Analysis 
Answer the following questions: 
* List the employee number, last name, first name, sex, and salary of each employee.
* List the first name, last name, and hire date for the employees who were hired in 1986.
* List the manager of each department along with their department number, department name, employee number, last name, and first name.
* List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
* List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
* List each employee in the Sales department, including their employee number, last name, and first name.
* List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
* List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
