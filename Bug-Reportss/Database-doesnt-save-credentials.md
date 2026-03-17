Title:

User is not saved in the database after successful registration

Environment:

Application: Demo E-commerce App
Environment: Test
Database: PostgreSQL
Browser: Chrome
OS: Windows 10

Steps to Reproduce:

Open the registration page.

Enter valid data:

Name: Test QA

Email: testqa@gmail.com

Password: Test123!

Click the Register button.

Verify that the success message appears.

Execute the following database query:

SELECT * 
FROM users
WHERE email = 'testqa@gmail.com';
Expected Result:

The user should be created in the database.

The query should return exactly one record.

Actual Result:

The query returns 0 records.

The user is not stored in the database.,

Severity:High

Priority:High
