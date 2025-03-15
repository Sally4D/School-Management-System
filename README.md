# 🏫 School Management System (SMS)

## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
  - [Interactive Dashboard](#1-interactive-dashboard)
  - [Multi-Portal Access](#2-multi-portal-access)
  - [Student Management](#3-student-management)
  - [Teacher Management](#4-teacher-management)
  - [Class & Timetable Organization](#5-class--timetable-organization)
  - [Goal Management System](#6-goal-management-system)
  - [User Profile Management](#7-user-profile-management)
  - [Advanced Reporting](#8-advanced-reporting)
- [Technical Specifications](#technical-specifications)
- [Installation & Setup](#installation--setup)

## Project Overview
The **School Management System (SMS)** is a comprehensive Microsoft Access-based application designed to streamline and modernize educational institution operations. This system provides an intuitive interface for managing students, teachers, classes, and academic goals through role-specific portals that ensure appropriate access control while maximizing administrative efficiency.

## Key Features

### 1. Interactive Dashboard
- Personalized dashboard views based on user role
- Real-time notifications for goals and important updates
- Quick access to frequently used features and reports
- Summary statistics relevant to the logged-in user

![Dashboard](/Dashboard.png)

### 2. Multi-Portal Access
- Three distinct access portals with role-specific functionality:
  - **Student Portal**: View classes, assignments, goals, and personal progress
  - **Teacher Portal**: Manage classes, student records, and goal assignment
  - **Admin Portal**: Comprehensive system control and oversight of all functions
- Secure login system with role-based permissions

### 3. Student Management
- Complete student record management including:
  - Student ID and personal information
  - Academic history and enrollment details
  - Guardian/parent contact information
  - Attendance tracking
- Add, update, and remove student records with data validation

![Student Management](/List%20View%20Manage%20Students.png)

### 4. Teacher Management
- Comprehensive teacher profile system including:
  - Qualifications and specializations
  - Class assignments and scheduling
  - Performance metrics and goal completion rates
  - Contact information and availability
- Efficient assignment of teachers to classes with workload management

### 5. Class & Timetable Organization
- Intuitive timetable creation and management interface
- Conflict detection and prevention when scheduling classes
- Classroom resource allocation and management
- Visual timetable views by teacher, class, or room

![Class Assignment](/List%20View%20-%20Assigning%20Classes.png)
![Timetable Management](/Manage%20TimeTable.png)

### 6. Goal Management System
- Goal creation and assignment based on user type:
  - Teacher goals focused on academic outcomes and professional development
  - Student goals tracking academic progress and achievement targets
  - Administrative goals for institutional improvement
- Progress tracking and notification system
- Achievement recognition and reporting

![Goal Management](/Assign%20%26%20ManageGoals.png)

### 7. User Profile Management
- Detailed user profile creation and maintenance
- Customizable fields for different user types
- Document attachment capabilities for certificates, IDs, etc.
- Password management and security controls

![User Profile Management](/Managing%20User%20Profiles.png)

### 8. Advanced Reporting
- Comprehensive reporting system with filterable parameters
- Performance analytics across various metrics
- Export capabilities to multiple formats
- Custom report generation for stakeholder requirements

![Advanced Reporting](/Extensive%20Reports.png)

## Technical Specifications
- ### **Microsoft Access Implementation:**
The system is built using Microsoft Access, leveraging:
  - Access Forms for intuitive user interfaces
  - VBA (Visual Basic for Applications) for custom functionality
  - Access Queries for efficient data retrieval and manipulation
  - Relationship integrity enforcement through referential constraints
  - Form and Report Wizards for rapid interface development
  - Custom macros for automation of routine tasks

- ### **Database Design:**
The database implements a normalized structure with:
  - Optimized table relationships to prevent redundancy
  - Appropriate indexing for performance enhancement
  - Data validation rules to maintain data integrity
  - Parameterized queries to prevent SQL injection
  - Transaction processing for critical operations

![Database Management 1](/Managing%20Data%20(1).png)
![Database Management 2](/Managing%20Data%20(2).png)
![Database Management 3](/Managing%20Data%20(3).png)

## Installation & Setup
Follow these steps to set up and run the School Management System on your machine.

### 1. System Requirements
- Microsoft Windows 7/8/10/11
- Microsoft Access 2016 or newer (part of Microsoft Office suite)
- Minimum 4GB RAM recommended
- At least 500MB of free disk space

### 2. Download the System
- Download the SMS.accdb file from this repository
- Save it to a location on your computer with read/write permissions

### 3. First-Time Setup
- Double-click the SMS.accdb file to open it in Microsoft Access
- If prompted about security warnings, click "Enable Content"
- The system will guide you through initial setup including:
  - Creating the admin account
  - Setting up school information
  - Configuring basic system parameters

### 4. User Creation
- Log in with the admin account
- Navigate to the User Management section
- Create accounts for teachers and students as needed
- Assign appropriate access levels

### 5. Data Import (Optional)
- The system supports importing existing data from Excel spreadsheets
- Use the Data Import tool in the Admin Portal to populate the database with existing records

### 6. Backup Recommendations
- Regular backups are strongly recommended
- Use the built-in backup tool in the Admin Portal
- Store backups in a secure location separate from the main system

**Enjoy your new School Management System!**
