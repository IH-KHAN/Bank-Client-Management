

## Overview
Client Management System is a comprehensive application designed to streamline general banking operations and customer relations. It provides a secure, centralized platform for bank personnel to manage client profiles, oversee service integrations (such as loan applications and approvals), and maintain accurate banking records.

## Key Features
* **Client Profile Management:** Securely create, read, update, and manage customer data and interactions.
* **Role-Based Authorization:** Strict access control ensuring that sensitive client data and approval workflows are only accessible to authorized bank personnel.
* **Service Workflows:** Integrated modules for handling day-to-day operations, including loan processing and customer relation tracking.
* **Relational Database Management:** Robust data structuring utilizing SQL Server to maintain high data integrity for financial records.

## Tech Stack
* **Database:** SQL Server (MSSQL), Entity Framework

## Repository Structure
This repository contains the core application files alongside the primary database files required to run the local environment:
* `BCES_DATA1.mdf`: Primary SQL Server Data file containing the database schema and local data.
* `BCES_LOG1.ldf`: SQL Server Log file.
* standard `.gitignore` and `.gitattributes` for ASP.NET/C# environments.

### Prerequisites
* [SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) or SQL Server Management Studio (SSMS)



