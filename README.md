![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Select-From-Where-Like-Lab-2/assets/170050432/861e61cc-a93e-4b2c-a7e1-badba0aacbde)

# Basic-SQL-Queries-Select-From-Where-Like-Lab-2


# Task 1. List all organization machines

In this task, I need to get a list of all organization machines and their operating systems. 
The data is contained in the machines table. I’ll need to use the SELECT keyword to return specific columns.

I will run a SQL query to retrieve only the device_id and operating_system columns from the machines table.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Select-From-Where-Like-Lab-2/assets/170050432/9dba68a0-197e-4764-b94e-61f830987057)



# Task 2. Retrieve a list of the machines with OS 2

In this task, I need to obtain a list of all machines with the 'OS 2' operating system because these machines need an update. 

To get this information, I’ll run my first SQL query with a filter.

I will select all the records from the machines table with a value of 'OS 2' in the operating_system column. I'll replace the value X with the correct string:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Select-From-Where-Like-Lab-2/assets/170050432/f0e00b2d-48f4-4251-bf0c-fcf5bde74769)


# Task 3. List employees in specific departments

In this task, I need to retrieve a list of all the employees in the Finance and Sales departments to obtain their office numbers. 

A notice about handling confidential financial information will be posted to these offices.

I will filter the rows returned from the department column in the employees table to include only employees from the 'Finance' department.

I’ll replace X with the appropriate column name and Y with the appropriate value to complete the filter:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Select-From-Where-Like-Lab-2/assets/170050432/c276f6a1-dcdb-445b-8375-ffa3fb87d030)

# Task 4. 

In this task, I need to retrieve a list of all the employees in the Finance and Sales departments to obtain their office numbers. 

A notice about handling confidential financial information will be posted to these offices.

I will filter the rows returned from the department column in the employees table to include only employees from the 'Sales' department. I’ll replace X with the appropriate column name and Y with the appropriate value to complete the filter:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Select-From-Where-Like-Lab-2/assets/170050432/a77b4224-78d6-49af-aa19-9c2279941613)


# Task 5. Identify employee machines

My team recently discovered that there are issues with machines in the South building. In this task, I need to obtain certain employee and computer information.

A machine in 'South-109' has an issue. I need to determine which employee uses that computer so I can send them an alert.

I will write a query to identify which employee uses the office in 'South-109'. The data must be returned from the office column in the employees table:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Select-From-Where-Like-Lab-2/assets/170050432/3a22ad18-05d4-4f39-8c38-2d0be6b38734)

# Task 6. 

Next, my team has determined that there is an issue with all the machines in the South building. Offices in the organization are named with the building name, a hyphen, and the office number in that building (for example, 'South-109').

I will modify the query I used in the previous step so that it returns information on all the employees in the 'South' building. I will use the LIKE operator with % in this query:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Select-From-Where-Like-Lab-2/assets/170050432/a80ea52c-2a09-4f9e-a759-5a394d23a579)

I now have practical experience in using SQL to:

Apply the WHERE clause to filter what a SQL query returns.
Use the LIKE operator to filter for patterns.
