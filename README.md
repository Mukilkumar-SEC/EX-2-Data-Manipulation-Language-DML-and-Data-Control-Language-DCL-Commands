# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## DATE:
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```

## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b32bceb5-9f0f-4c30-b27f-c4375e677f46)



### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/3fd9b83b-a6e7-4e47-b0cb-f2815bbbae95)


### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/15e1ebf0-899f-4589-aee8-0ea4570cefba)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/ad0c2970-47bc-4591-8f4b-a295a38b092d)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/72faf04a-7d00-4070-8b1b-433f67d05a51)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b697b096-ba16-4329-ac6b-d015128fd061)


### Q5)	List the names of Clerks from emp table.


### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/56786044-5d67-49a1-97b5-c1a9ebeaba58)

### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/9dac7081-c1e3-4258-8599-e80a625dc1c3)


### Q6)	List the names of employee who are not Managers.


### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/92ff6c91-741c-466c-a56c-1a8cd98a6c47)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/0b612e84-47ec-4a92-84cc-d8d47bad31a9)


### Q7)	List the names of employees not eligible for commission.


### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/115674ab-12b8-4365-81ce-8fc7e3e0d6d9)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/747f7859-d68a-4a3c-9489-1183fba86dc2)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/37453bf7-a728-4207-8120-96c30a425b98)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/c0f086e1-46d0-4227-8128-df05bff487c1)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/4ede6ac7-78af-4960-a713-d9fc3da5c270)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/016fc6e9-d11e-4ead-b6a3-3da2de24cb5e)



### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:

![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/96806e3a-1e06-4e79-9213-21b6334b7d45)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/9ca18434-a5c4-41a2-967c-1c8e04d2d9c0)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/5fd72123-d579-411c-97df-17d4f0aae8b4)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/d13ca56f-28a8-4dd8-9ae9-3baa0670c114)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/ce31b83c-5d0b-4af2-bbee-8179ce10c242)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/18952b16-4129-4b9c-b465-38d259660223)


### Q13) Find number of rows in the table EMP

### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/73db5b0a-49f9-4e88-ba13-d70b560a5c51)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/22521157-7fb3-4013-b3cc-253f9d45b3ba)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/d98c5cc1-ccd5-45e3-8b16-62ac42c8920a)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/4a7af52d-2308-4cb8-a1e2-4f6fb400b707)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/2628a8ea-ad9a-4384-a1b4-6d77dd524664)


### OUTPUT:
![image](https://github.com/AtchayaSundaramoorthy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119393516/a765a09d-d3c5-41e2-98e5-0a1c6a9f5043)

### RESULT;

Queries Executed Successfully
