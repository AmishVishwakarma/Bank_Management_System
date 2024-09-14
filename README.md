# Bank_Management_System

## Overview
The Bank Management System is a console-based C++ application designed to manage customer accounts and facilitate banking transactions. It uses SQL Server for backend database management and supports roles for users, bankers, and admins, providing different levels of access.

## Features
### 1. Users:
> Sign up/Login
> View Account Details
> Deposit/Withdraw Money
### 2. Bankers:
> Manage User Accounts
> Add New Users
> Request Admin Approval for Updates
### 3. Admins:
> Manage Bankers
> Full User Account Access
> Approve/Decline Banker Requests

## Prerequisites
> C++ Compiler
> SQL Server
> Database connector library for SQL Server

## Database Structure
### Tables:
> main_account: Stores user data.
> login_details_user: Stores user login credentials.
> login_details_banker: Stores banker login details.
> login_details_admin: Stores admin login details.

## Usage
> Compile and run the C++ application.
> Set up the database using the provided SQL script (Bank_System_Database.sql).
> Follow the prompts in the console to access different functionalities based on the role (User/Banker/Admin).

## Contribution
Contributions are welcome. Feel free to fork the repository and submit pull requests.
