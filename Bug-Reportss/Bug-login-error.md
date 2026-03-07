Title:
No error message displayed when user enters incorrect password

Summary:
When the user attempts to log in with an incorrect password, the system does not display any error message.
The page simply refreshes and the user remains on the login page without feedback.

Environment:
Windows 10
Chrome v142.0.1

Severity: Major
Priority: Medium

Steps to Reproduce:

Go to the login page

Enter test@test.com
 in the email field

Enter wrongpassword in the password field

Click the Login button

Expected Result:
The message "Invalid password" should be displayed.

Actual Result:
No error message is displayed and the user remains on the login page.
