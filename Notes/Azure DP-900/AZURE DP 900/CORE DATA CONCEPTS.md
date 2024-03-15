core data concepts - 15 -20%
relational data workload - 25 - 30%
non relational data workload - 25 - 30%
data analytics and processing - 25 -30%

#### CORE DATA CONCEPT - 

data - collection of facts , no , observation
1. structured data - typically tabular , represented by rows and columns , ex . relational database - database that has tables and rows 
2. semi structured - not in relational database but has some structure , ex. JSON
3. unstructured - audio , video files

#### DATA PROCESSING - 
process of conversion of raw data into meaningful information

1. streaming - real time data , process data as it arrives , ex. video stream on yt in real time
2. batch processing - buffering and processing the data in groups 

#### RDBMS - 
collection of multiple table and database objects 

#### SQL COMMANDS - 
DDL - data definition language
defines the structure of database

1. create - create database and its objects like tables , index 
2. alter - alter the structure of object
3. drop - delete the object
4. truncate - removes all the records from table
5. rename - rename the database

DML - data manipulation language
used to store , modify , retrieve , delete and update data in database
1. select - retrieve data from database
2. insert - insert data into table
3. update - update existing data
4. delete - delete the data inside objects

#### OBJECTS -
1. table - 
2. index - `CREATE INDEX index_name ON table_name;`
3. view - virtual table
   `CREATE VIEW view_name AS
    `SELECT coumn1<column2`
    `FROM table_name
    `WHERE condition`

#### SQL CONSTRAINTS - 
rules enforced on data columns on table
![[Pasted image 20240306115317.png]]
![[Pasted image 20240306115522.png]]
![[Pasted image 20240306115645.png]]
![[Pasted image 20240306115808.png]]

#### DATA INTEGRITY - 
![[Pasted image 20240306115929.png]]

#### OLTP VS OLAP -
![[Pasted image 20240306120149.png]]

#### IAAS VS PAAS VS SAAS - 
![[Pasted image 20240306120440.png]]




 


