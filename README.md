# Time Tracker Application

**Technologies:** C#, ASP.NET Web Forms, SQL Server, HTML, CSS, JavaScript  

## Overview
The Time Tracker application is a web-based system designed to help organizations manage employee work hours efficiently. It allows employees to log their work hours and descriptions, while managers and admins can view, edit, and report on employee work data.  

This project was developed as part of a software development internship and demonstrates full-stack skills including database integration, user authentication, and dynamic web page generation.

## Features
- **Employee Functionality:**
  - Log daily work hours and descriptions
  - View personal work history within a date range
- **Manager/Admin Functionality:**
  - Add, edit, or delete employee information
  - View all employee logs and generate reports
  - Export work hours data to Excel
- **User Authentication:**
  - Login system with role-based access control (employee, manager, admin)
- **Calendar Integration:**
  - Select log dates via interactive calendar controls
- **Responsive Design:**
  - Supports switching between desktop and mobile views

## Architecture
- **Frontend:** ASP.NET Web Forms, HTML, CSS, JavaScript  
- **Backend:** C# (code-behind), SQL Server for database operations  
- **Database Tables:**
  - `idus` — stores employee information  
  - `workHours` — stores logged work hours with descriptions  
  - `logHoursPage` — supports filtering and reporting  


