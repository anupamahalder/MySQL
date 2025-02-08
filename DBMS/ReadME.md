## DBMS (Database Management System) and RDBMS (Relational Database Management System):
DBMS/RDBMS is a software to manage database.
 <br><b>
DBMS consists of <ol>
1. Data (Information as data is organized)
2. User ( We all are user)
3. Hardware (Computer, memory card, DVD, Pendrive)
4. Software
5. Processing Unit </b>
<br> </ol>

## Advantanges of DBMS: 
Advantages are <ol>
  1. Organized (Store, Retrieve, Manage)
  2. First access
  3. Parallel Accessing
</ol>

## Primary Key:
All the value of the field/column is unique then we call that field as a primary key.
Table: Student
| Roll | Name | Phone |
| ---- | ---- | ----- |
| 101  | Ram  | 3564  |
| 102  | Sam  | 23724 |
| 103  | Ram  | 32562 |
<br>
To uniquely identify any record using a particular data we use primary key. Here Roll is primary key. <br>

## Composite Primary Key:
Where two or more columns/fields are needed to uniquely identify a record from a table.
<br>
Table: Course 
| Course ID | College | Credit |
| --------- | ------- | ------ |
| CSE 01    | ABC     | 7      |
| CSE 02    | JNU     | 6      |
| CSE 01    | PQR     | 8      |
| CSE 03    | VC      | 3      |
<br>
Here to uniquely identify a record we need primary key as (Course ID, College) together.
<br>

## Foreign Key:
If the field/column of a table is the primary key of another table then this column is known as foriegn key to that table.
Table: Student
| Roll | Name | Phone |
| ---- | ---- | ----- |
| 101  | Ram  | 3564  |
| 102  | Sam  | 23724 |
| 103  | Ram  | 32562 |
| 104  | Riya | 32562 |
| 105  | Tom  | 32562 |
<br>

Table: Library
| Book ID | Borrowed_ID   |
| ------- | ------------ |
| Ab12    | 101          |
| Ab62    | 105          |
| Ab92    | 102          |
<br>
The primary key of Student table is Roll and of Library table is Book ID.
Borrowed_ID is the primary key of Student table. 
In any table if we use the the primary key of any other table then this column/field is known as foreign key to this table.
<br>

## Relation:
There are three types of relations
1. One to One (One row of a table has relation with only one row of another table)
2. One to Many (One row of a table has relation with multiple rows of another table)
3. Many to Many (One row of a table can have relation with multple rows of another table and vice versa)
<br>
**Example:**
#### One-to-One relationship:
Relation between Student table with Student details table.
#### One-to-Many relationship:
Relation between Customer table with Order table.
#### many-to-Many relationship:
Relation between Student table with Course table.
