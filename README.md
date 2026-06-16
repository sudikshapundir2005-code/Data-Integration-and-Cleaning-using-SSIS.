 https://sudikshapundir2005-code.github.io/Data-Integration-and-Cleaning-using-SSIS./

## Project Architecture Diagrams
1. Control Flow(control_flow.png)
2. Data Flow(data_flow.png)

This project demonstrates a robust ETL (Extract, Transform, Load) pipeline built using SQL Server Integration Services (SSIS). It is designed to automate data processing and provide real-time status updates.

## Project Overview
The core objective of this project is to streamline data cleaning and integration tasks. It includes a Data Flow Task for processing source data and a custom Script Task that triggers automated email notifications upon successful completion of the package.

## Key Features
Automated Data Flow: Efficiently extracts, transforms, and loads data.
Notification System: Utilizes a C# Script Task to send email alerts via SMTP after successful package execution.
Error Handling: Implements `try-catch` blocks within the script to handle and report runtime errors effectively.

## How to Configure
1. SSIS Package: Open the project in Visual Studio.
2. Data Flow: Configure your source and destination connections in the Data Flow Task.
3. Script Task: Open the Script Task and update the `SmtpClient` credentials with your own email and App Password.
4. Execution: Ensure your connection managers are properly configured and execute the package.

## Technologies Used
SQL Server Integration Services (SSIS)
C# (for Script Task automation)
SMTP Protocol (for email notifications)
