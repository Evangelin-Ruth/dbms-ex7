## EXPERIMENT 07:AGGREGATE FUNCTION IN SQL
## AIM:
To perform aggregation functions in SQL.

## ALGORITHM:
1. Create a table and insert values using keywords "create table","insert into values".
2. Display the table using "select"
3. Using sum() , count() and avg() perform the operations.
4. Display the result.

## PROGRAM:
```
-- create
CREATE TABLE STUDENT (
  sid INTEGER PRIMARY KEY,
  sname TEXT NOT NULL,
  smark TEXT NOT NULL
);

-- insert
INSERT INTO STUDENT VALUES (0001, 'Clark',83);
INSERT INTO STUDENT VALUES (0002, 'Dave',67);
INSERT INTO STUDENT VALUES (0003, 'Ava', 92);
INSERT INTO STUDENT VALUES (0004, 'Tom', 78);
INSERT INTO STUDENT VALUES (0005, 'Ava', 59);

-- fetch 
SELECT * FROM STUDENT ;

SELECT SUM(smark) "SUM : " FROM STUDENT;
SELECT count(*) "Count : "FROM STUDENT;
SELECT avg(smark) "Average : "FROM STUDENT;
```
## OUTPUT :
![image](https://github.com/Evangelin-Ruth/dbms-ex7/assets/94219798/6c98455f-94f6-4e01-8674-54d0410ddeca)
![image](https://github.com/Evangelin-Ruth/dbms-ex7/assets/94219798/bfc3c55b-8474-4599-a3e5-f660fc2f549c)
## RESULT :
Hence, the aggregation functions in SQL are performed successfully.

