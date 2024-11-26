# Query

## Create a table for the Library management system

create table Library_Management_System (

Author_id int,

Name varchar(20),

Nationality varchar(15)

);

## Create a table for Books

create table Books (
Books_Id int,

Author_id varchar(15),

Title varchar(20),

Genre int,

ISBN varchar(10)
);

## Create a table for Members

create table Members (
Members_id int,

Name varchar(20),

Address varchar(15),

Membership_Type varchar(10)
);

## Create a table for Loans

create table Loans (
Loan_id int,

Member_Id int,

Books_Id int,

Loan_Date int,

Return_date int 
);
