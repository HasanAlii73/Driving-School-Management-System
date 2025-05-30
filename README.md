# Driving School Management System

## Overview
A comprehensive desktop application built with C# Windows Forms and Microsoft SQL Server to streamline operations in a driving school. The system manages license issuance, user management, test scheduling, and maintains detailed records of all applicants and license holders.

## Features

### Authentication & Security
- Secure login system with username/password authentication
- "Remember Me" functionality for convenience
- Role-based access control for different system users

### People Management
- Centralized database for storing personal records
- Add, edit, and manage detailed personal information
- Profile image support with upload/update capabilities

### License Management
- Complete license processing system including:
  - New license issuance
  - License renewal
  - Replacement of lost/damaged licenses
  - Detainment and release of licenses
  - Support for both Local and International Licenses

### Test Scheduling
- Integrated test scheduling system for:
  - Vision tests
  - Written tests
  - Driving tests
- License issuance only after successful completion of all required tests

### User Sections
- **Drivers Section**: Filters and displays individuals who have obtained driving licenses
- **Users Section**: Manages system users with controlled permissions

## Technical Specifications
- **Frontend**: C# Windows Forms Application
- **Backend**: Microsoft SQL Server Database
- **Image Support**: Personal photo storage for record accuracy

## Installation
1. Clone or download the repository
2. Restore the SQL Server database from the provided backup file
3. Update the connection string in the application configuration
4. Build and run the Windows Forms application

## Usage
1. Log in with appropriate credentials (admin/user accounts)
2. Navigate through the intuitive interface to:
   - Manage people records
   - Process license applications
   - Schedule and track tests
   - View and manage issued licenses
   - Administer system users

## Requirements
- Windows OS
- .NET Framework [version]
- Microsoft SQL Server [version]
