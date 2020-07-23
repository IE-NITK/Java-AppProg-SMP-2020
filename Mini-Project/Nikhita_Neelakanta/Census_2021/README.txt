The application uses 2 mysql tables.
One storing UserId(enumerator) and passwords and the other(biodata) the main data.

Structure of the tables:

enumerator:
+----------+--------------+------+-----+---------+-------+
| Field    | Type         | Null | Key | Default | Extra |
+----------+--------------+------+-----+---------+-------+
| Username | varchar(100) | NO   | PRI | NULL    |       |
| Password | varchar(100) | YES  |     | NULL    |       |
+----------+--------------+------+-----+---------+-------+
NOTE:The application doesn't allow you to create an account, so enter a record using mysql command line tool to gain access to the application.

biodata:
+-------------------+--------------+------+-----+---------+----------------+
| Field             | Type         | Null | Key | Default | Extra          |
+-------------------+--------------+------+-----+---------+----------------+
| s_no              | int(11)      | NO   | PRI | NULL    | auto_increment |
| Name              | varchar(100) | YES  |     | NULL    |                |
| DOB               | date         | YES  |     | NULL    |                |
| Age               | int(3)       | YES  |     | NULL    |                |
| Gender            | varchar(8)   | YES  |     | NULL    |                |
| disability        | varchar(3)   | YES  |     | NULL    |                |
| literacy_status   | varchar(10)  | YES  |     | NULL    |                |
| employment        | varchar(10)  | YES  |     | NULL    |                |
| Occupation        | varchar(30)  | YES  |     | NULL    |                |
| Income            | int(11)      | YES  |     | NULL    |                |
| Mobile            | bigint(10)   | YES  |     | NULL    |                |
| HEQ               | varchar(30)  | YES  |     | NULL    |                |
| District          | varchar(100) | YES  |     | NULL    |                |
| Town_City_Village | varchar(100) | YES  |     | NULL    |                |
| State             | varchar(100) | YES  |     | NULL    |                |
+-------------------+--------------+------+-----+---------+----------------+

