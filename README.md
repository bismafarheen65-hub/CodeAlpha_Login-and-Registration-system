 Login and Registration System
📖 Project Description:

This is a desktop-based Login and Registration System developed using C++/CLI Windows Forms and SQL Server (LocalDB). The system allows users to register, store their details in a database, and securely log in using authentication.

This project was developed as part of the CodeAlpha Internship Program.

✨ Features:
User Registration
User Login Authentication
Password Confirmation Validation
Duplicate Email Check
SQL Server Database Integration
User Dashboard after Login
Error Handling & Validation
🛠️ Technologies Used:
C++/CLI
Windows Forms (.NET Framework)
SQL Server (LocalDB)
ADO.NET (SqlConnection, SqlCommand, SqlDataReader)
🗄️ Database Table Structure:
CREATE TABLE users (
    id INT IDENTITY(1,1) PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100) UNIQUE,
    phone VARCHAR(20),
    address VARCHAR(200),
    password VARCHAR(100)
);
How to Run Project:
Open project in Visual Studio
Set SQL Server LocalDB connection
Run the project
Register a new user
Login with registered credentials
 Author:

Developed by: Bisma
Internship: CodeAlpha
