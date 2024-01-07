
# Software Requirements Specification (SRS) for Online Shop Management System

  # 1. Introduction
## 1.1 Purpose

The purpose of the Online Shop Management System is to provide a platform for users to log in, manage their information, purchase products, and for administrators to manage product categories, products, and user accounts.

### 1.2 Scope

The system will include functionalities for user authentication, user and admin dashboards, product management, category management, and user account management.

# 2. System Overview
## 2.1 System Description

The system consists of a login page with options for user and admin login. Users can manage their account information, purchase products, and view their dashboard. Admins can manage product categories, products, and user accounts.

 ### 2.2 System Features
    
User Authentication

  * Login for Users
  * Login for Admins
 * Signup for New Users

User Dashboard

- View and Edit User Information
- Purchase Products
- Print Total Bill
- Update and Delete User Information

Admin Dashboard

- Add, Update, and Delete Categories
- Add, Update, and Delete Products
- Manage User Accounts

# 3. Functional Requirements

## 3.1 User Authentication
- The system shall allow users to log in with a valid username and password.
- New users shall be able to create an account by providing required details.
- The system shall differentiate between user and admin logins.

### 3.2 User Dashboard

- Users shall be able to view and edit their account information.
- Users shall be able to purchase products.
- Users shall be able to print the total bill.
- Users shall be able to update and delete their own information.

#### 3.3 Admin Dashboard

- Admins shall be able to add, update, and delete product categories.
- Admins shall be able to add, update, and delete products.
- Admins shall be able to manage user accounts.

# 4. Non-functional Requirements

## 4.1 Performance
- The system should respond to user interactions within a reasonable time frame.

### 4.2 Usability

- The user interface should be intuitive and easy to use for both users and admins.

#### 4.3 Security

- User passwords should be securely stored using encryption.
- Admin functionalities should be accessible only after successful admin login.

# 5. Constraints
- The system will be developed using Java with a Swing-based graphical user interface.
- The project will not include online payment functionality (for simplicity).

# 6. Assumptions and Dependencies
-  The system assumes that users have a basic understanding of the login process.

# 7. Glossary

- User: A registered user of the system.

- Admin: An administrator with privileged access to manage the system.

- Dashboard: The main interface for users and admins to access relevant functionalities.



