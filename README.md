# Simple Database Design 
Description

This database is designed to manage information about employees, branches, clients, suppliers, and their interactions within a fictional company structure.

# Tables

1. Employee

emp_id: Unique identifier for an employee

first_name: First name of the employee

last_name: Last name of the employee

birth_day: Birthdate of the employee

sex: Gender of the employee

salary: Employee's salary

super_id: ID of the employee's supervisor

branch_id: ID of the branch where the employee works

2. Branch

branch_id: Unique identifier for a branch

branch_name: Name of the branch

mgr_id: ID of the branch manager

mgr_start_date: Start date of the manager at the branch

3. Client

client_id: Unique identifier for a client

client_name: Name of the client

branch_id: ID of the branch associated with the client


4. Works_With

emp_id: Employee ID associated with a client

client_id: Client ID associated with an employee

total_sales: Total sales between the employee and client

5. Branch_Supplier

branch_id: ID of the branch associated with the supplier

supplier_name: Name of the supplier

supply_type: Type of supplies provided by the supplier to the branch
