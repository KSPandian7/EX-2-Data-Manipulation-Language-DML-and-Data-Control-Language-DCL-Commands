# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL

## DATE: 10/08/2023


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
![Alt text](271174892-081ff76d-e743-4fee-993b-4fd367716f94.png)

### OUTPUT:
![Alt text](271174912-b667993b-d5b9-4197-be2c-ee7cab1c7d1e.png)
### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![Alt text](271174961-c3469723-36d2-4488-ac58-b5c8683a0e93.png)

### OUTPUT:
![Alt text](271174985-91233fd3-5dfa-4318-b62f-db528e31914c.png)
### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:
![Alt text](271175005-180d48fb-dd02-4d7e-991d-79e92d50f3ae.png)

### OUTPUT:
![Alt text](271175026-cbf1e6e9-9633-4cf9-ad85-341e7b03c613.png)
### Q5)	List the names of Clerks from emp table.


### QUERY:
![Alt text](271175071-feb4b41d-8428-440b-8961-078212a7e836.png)

### OUTPUT:
![Alt text](271175098-86f71191-94a7-45e6-b756-6020a06350b7.png)

### Q6)	List the names of employee who are not Managers.


### QUERY:
![Alt text](271175146-a65b548c-2cd5-45c9-b21b-89cbdb1114c4.png)

### OUTPUT:
![Alt text](271175187-02933c79-0073-4274-9b90-2bc9f4814d8b.png)

### Q7)	List the names of employees not eligible for commission.


### QUERY:
![Alt text](271175220-6d3c980b-752e-4df5-9648-2a4bcf6e1962.png)

### OUTPUT:
![Alt text](271175271-f4a825b1-ac41-4d65-9b0c-e59a55e4ca33.png)

### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![Alt text](271175311-aec361f2-371a-43c0-8be2-7fae5ecfa2e8.png)

### OUTPUT:
![Alt text](271175346-6c098d6f-d039-4325-9810-93275772b07f.png)

### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![Alt text](271175362-89b37e50-40ad-42ab-9d4a-dbba66165238.png)

### OUTPUT:
![Alt text](271175394-9bd94ed7-a460-4084-8ede-87fdaf6191cf.png)

### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![Alt text](271175413-a5349ed1-9a23-4d89-ad1f-4f1ea9cd63c0.png)

### OUTPUT:
![Alt text](271175439-85269e01-cc98-47d0-8e3a-18ca0b00d42e.png)

### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![Alt text](280692494-69e2a111-09de-4bea-baeb-bb407cf7ef47.png)

### OUTPUT:
![Alt text](280692521-f9599776-6835-4d4f-a55a-57e4c876176e.png)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![Alt text](280692565-bcab33b0-c04a-452f-b6a7-5978c08b3a50.png)

### OUTPUT:
![Alt text](280692586-46c0225c-48d4-4a72-8793-af38eff1f02a.png)
### Q13) Find number of rows in the table EMP

### QUERY:
![Alt text](280692621-e27d184b-83ae-4fa3-b4d7-537748036d6d.png)

### OUTPUT:
![Alt text](280692638-b456cfaa-d6bd-4692-81f2-f8458278cb05.png)

### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:
![Alt text](280692665-9a2745e9-c67f-4532-ae99-1f686381c9a3.png)

### OUTPUT:
![Alt text](280692684-e8fb67f1-4151-454b-9447-3481910b3f56.png)

### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![Alt text](280692726-ac0f8772-861c-4648-9c21-c08ede389ecd.png)

### OUTPUT:
![Alt text](280692755-f7664cf4-5a48-4d0b-b59a-76af6216f386.png)


## RESULT:
Thus,the data manipulation language and data control language commands are executed.

