#Secure-Auth-System
A secure and user-friendly authentication system implemented as part of the BHEL Cybersecurity Internship. This project ensures secure login, password validation, and credential management using Python.

Overview
The Secure-Auth-System is designed to authenticate users, validate passwords, and handle forgotten password scenarios. It also ensures the secure storage and retrieval of user credentials, providing a robust solution for maintaining account integrity.

Features
1. Password Validation
Passwords must meet the following criteria to ensure security:

Minimum length of 8 characters.
Includes at least one numeric digit.
Includes at least one special character.
2. Credential Storage and Retrieval
User credentials are securely stored in a text file on Google Drive.
The system verifies user credentials during login by reading the file.
New credentials are appended to the file, and existing passwords can be updated.
3. Login Process
Users provide their username and password.
The system checks if the username exists:
If it exists, the password is verified.
If it matches, the user is welcomed; otherwise, an error message is displayed.
If it does not exist, the system validates the password. If valid, the new credentials are saved, and the user is welcomed.
4. Forgot Password Process
Users can reset their password by providing their username and a new password.
The system checks if the username exists:
If it exists, the new password is validated and updated in the credentials file.
If it does not exist, an error message is displayed.
5. User Interface
The login form includes:
Fields for username and password.
Login and "Forgot Password" buttons.
The forgot password form includes:
Fields for username and new password.
A "Reset Password" button.
The interface dynamically switches between the login and forgot password forms based on user actions.
