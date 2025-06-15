# Blood-Bank-Database
A SQL Server-based Blood Bank Management System featuring normalized schemas, views, and security triggers. Includes stored procedures, user-defined functions, and audit logging for donor activities.


# Blood Bank Management System – SQL Server

## Overview
This project is a comprehensive Blood Bank Management System built using Microsoft SQL Server for IFT-530 at Arizona State University. It demonstrates advanced SQL features like schema creation, data modeling, views, triggers, stored procedures, user-defined functions, and cursors for managing donors, patients, hospitals, blood inventory, and donation requests.

## Features
- **Normalized Relational Schema** with six core tables under `Blood_bank` schema.
- **Views** for active blood requests, filtered donations, and low inventory alerts.
- **Triggers** to audit donor INSERT, UPDATE, DELETE operations.
- **Stored Procedure** to add donations and update donor records.
- **User-defined Function** to calculate total donations by donor.
- **Cursor** implementation to iterate through donors of specific blood types.
- **Test cases** for stored procedures, functions, and data validations.

## Contributors
- **Sumasree Battula** 

## Requirements
- Microsoft SQL Server 2012 or above  
- SQL Server Management Studio (SSMS)

## Usage
1. Run the script `blood_bank.sql` in SSMS to set up the database and all components.
2. Use the test cases included to verify functionality.
3. Query views like `active_blood_requests` and call procedures/functions to interact with the system.

![Image Alt](https://github.com/suma419/Blood-Bank-Database/blob/1c45e8d0fc6373ebdb705f22454ce4ca38a02703/database%20diagram.png)
