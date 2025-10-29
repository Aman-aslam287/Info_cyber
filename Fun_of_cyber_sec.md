# Fundementals of Computer Security
## Identification, Authentication, and Authorization

|Concept            |Description           |Examples                           |
|-------------------|----------------------|-----------------------------------|
|**Identification** | Claiming and Identity| Typing username                   |
|**Authentication** | Proving identity     |Entering password / fingerprint    |
|**Autorization**   | Granting access      |Accessing certain files after login|

## Key Principle:
"Authentication verifies who you are. Authorization decides what you can do."

# Authentication Methods
- Knowledge-based: Password, PINs
- Possession-based: Smart cards, OTP tokens
- Inherence Authentication (MFA): Combination of 2 or more above
- Single Sign-on (SSO): One-time login across multiple systems (e.g, Google or Microsoft SSO)

# Authorization Models
- DAC (Discretionary Access Control): Owner decides who can access (Windows permissions).
- MAC (Mandatory Access Control): Access based on classisfication levels (military systems).
- RBAC (Role-Based Access Control): Permissions assigned to roles (Admin, Manegers, User).
- ABAC (Attribute-Based Access Control): Access based on conditions (time, location, user type).

# Examples:
An "HR Manager" role can view employee data, while "Employee" role can only view their own profile

# Best Practices
- Uses storng, unique passwords
- Apply MFA whenever possible.
- Review role-based permissions regularly.
- Log all authentication and access events.
