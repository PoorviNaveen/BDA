# BDA
Big Data Analytics Lab
<br>
<br>
<br>
<br>
## Programs
- MongoDB- CRUD Operations Demonstration (Practice and Self Study)
- Perform the following DB operations using Cassandra.
a) Create a keyspace by name Employee
b) Create a column family by name Employee-Info with attributes: Emp_Id Primary Key, Emp_Name, Designation, Date_of_Joining, Salary, Dept_Name
c) Insert the values into the table in batch
d) Update Employee name and Department of Emp-Id 121
e) Sort the details of Employee records based on salary
f) Alter the schema of the table Employee_Info to add a column Projects which stores a set of Projects done by the corresponding Employee.
g) Update the altered table to add project names.
h) Create a TTL of 15 seconds to display the values of Employees.
- Perform the following DB operations using Cassandra.
a) Create a keyspace by name Library
b) Create a column family by name Library-Info with attributes: Stud_Id Primary Key, Counter_value of type Counter, Stud_Name, Book-Name, Book-Id, Date_of_issue
c) Insert the values into the table in batch
d) Display the details of the table created and increase the value of the counter
e) Write a query to show that a student with id 112 has taken a book “BDA” 2 times.
f) Export the created column to a csv file
g) Import a given csv dataset from local file system into Cassandra column family
- Execution of HDFS Commands for interaction with Hadoop Environment. (Minimum 10 commands to be executed)
- Implement Wordcount program on Hadoop framework
- From the following link extract the weather data https://github.com/tomwhite/hadoop-book/tree/master/input/ncdc/all
a) Create a MapReduce program to find average temperature for each year from NCDC data set.
b) find the mean max temperature for every month.
- For a given Text file, Create a Map Reduce program to sort the content in an alphabetic order listing only top 10 maximum occurrences of words.
- Write a Scala program to print numbers from 1 to 100 using for loop.
- Using RDD and FlatMap count how many times each word appears in a file and write out a list of words whose count is strictly greater than 4 using Spark.
- Write a simple streaming program in Spark to receive text data streams on a particular port, perform basic text cleaning (like white space removal, stop words removal, lemmatization, etc.), and print the cleaned text on the screen. (Open Ended Question).
