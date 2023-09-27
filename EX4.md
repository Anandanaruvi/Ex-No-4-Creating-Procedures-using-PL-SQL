# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```

SQL> create table employees(empid NUMBER,empname VARCHAR(10),dept VARCHAR(10),salary NUMBER);

Table created.

SQL> create procedure insert_employees_data as begin
  2  insert into employees(empid,empname,dept,salary)values(1,'Anandan','AIDS',50000);
  3   insert into employees(empid,empname,dept,salary)values(2,'Mullai','AIDS',10000);
  4   insert into employees(empid,empname,dept,salary)values(2,'Aruvi','AIML',20000);
  5   insert into employees(empid,empname,dept,salary)values(2,'Aadhavan','AIDS',25000);
  6  commit;
  7  end;
  8  /
```

### Output:
![image](https://github.com/Anandanaruvi/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/120443233/695d8b27-c905-43a0-9ba4-ef7b23368169)


### Result:

THE PROGRAM HAS BEEN IMPLEMENTED SUCCESSFULLY. 


