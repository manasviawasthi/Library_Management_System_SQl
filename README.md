# Library Management System (SQL Project)

## Overview
The Library Management System is designed to simplify and organize library operations using SQL. It keeps detailed records of books, customers, employees, branches, and tracks book issuance and returns. The system also maintains data regarding rental costs, availability status, and other critical information to ensure efficient library management.

---

## Database Setup
- **Database Name:** `Library`  
- Stores information about:
  - Books  
  - Customers  
  - Employees  
  - Branches  
  - Issuance and return transactions  

---

## Key Features

### 1. Book Management
- Add, update, or remove books in the collection.  
- Maintain the following details:  
  - Title  
  - Category  
  - Author and Publisher  
  - Rental Price  
  - Availability Status  

### 2. Customer Management
- Keep a record of all customers including:  
  - Name  
  - Address  
  - Registration Date  
  - Issuance History  

### 3. Employee Management
- Store information about library employees such as:  
  - Name  
  - Position  
  - Salary  
  - Assigned Branch  

### 4. Book Issuance and Returns
- Track issued books and their due dates.  
- Update availability automatically upon return.  

### 5. Branch Management
- Maintain branch-related details:  
  - Branch Number  
  - Manager Information  
  - Address and Contact Details  

---

## Queries and Data Analysis
The project includes SQL queries to manage and analyze library data effectively:

1. Retrieve book titles, categories, and rental prices of all **available books**.  
2. Display employee names with their **salaries in descending order**.  
3. Show book titles with the **customers who issued them**.  
4. Display the **total number of books per category**.  
5. Retrieve employee names and positions for staff earning **above ₹50,000**.  
6. List customer names who **registered before 2022-01-01** and have not issued any books.  
7. Show **branch numbers** along with **employee counts per branch**.  
8. Retrieve names of customers who issued books in **June 2023**.  
9. Get book titles that belong to the **"History" category**.  
10. Display branch numbers where the **employee count is greater than 5**.  

---
