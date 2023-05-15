# Database_Financial_Voucer
This database is designed in MY SQL. 
THE ISLAMIA UNIVERSITY BAHAWALPUR
DEPARTMENT OF SOFTWARE ENGINEERING 

  Topic Assigned to the Group : Financial Vouchers
Group:  
F21BSEEN1E02079
(ABDULLAH IQBAL)
F21BSEEN1E02080 
(MARYAM EHSAN) 
F21BSEEN1E02081
(MUHAMMAD SHAHGHIL ALI)
F21BSEEN1E02082 
(ABDULLAH AMIR)
F21BSEEN1E02083
(MUHAMMAD HUNAIN ALI) 
____________________________________________________________________________


we create four tables: "Student," "Employees," "Financing Voucher," "Program," and "Department." Here's a breakdown of the entities and attributes:

The "Student" table has attributes such as student_id, student_name, date_of_birth, email, and program_id. The program_id is a foreign key referencing the "Program" table's primary key.

The "Employees" table has attributes such as employee_id, employee_name, position, and department_id. The department_id is a foreign key referencing the "Department" table's primary key.

The "Financing Voucher" table has attributes such as voucher_id, student_id, amount, and payment_date. The student_id is a foreign key referencing the "Student" table's primary key.

The "Program" table stores information about different academic programs, with attributes such as program_id and program_name.

The "Department" table stores information about different departments within the university, with attributes such as department_id and department_name.
