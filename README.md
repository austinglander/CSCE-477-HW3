# Code explanation
[login.html](login.html) contains a simple implementation of a styled login page similar to the OWASP Juice Shop. There is no backend functionality, so the login page simply reports whether the email + password combination is valid or not.

The login validator checks and reports violations of the following criteria:
- Password is not empty
- Passwords is at least 8 characters long
- Email is not empty
- Email contains an @ that is not at the beginning or end

Violation of these criteria are reported via error messages directly on the UI.
