# Fundementals of computer security
## Identification, Authentication, and Authorization

| concept           | Description            | Examples                             |
|-------------------|------------------------|--------------------------------------|
|**Identication**   | Claiming an Identify   | Typing username                      |
|**Authentication** | Proving identity       | Entering password / fingerprint      |
|**Authorization**  | Granting acces         | Accessing certain files after login  |

## key Principles :
" Authentication  verifies who you are. Authorization decides what you can do."

# Authentication Methods 
- Knowledge-based : Password, Pins
- Possesion-based: Smart cards, OTP tokens
- INherence-based: Biometrics (fingerprints, face ID)
- MUtifactor Authentication (MFA): Comabination of 2 or more above
- Single-sign-on(SSO):one time login across multiple system (e.g., google or microsoft SSo)

# Authorization models
- DAC (Discretionary Access control): owner Decides who can access ( Windows permissions).
- MAC (Mandotory access control): Access based on classification levels (military systems).
- RBAC (Role-Bassed Access control): Permiission assingned to roles (Admin , maneger, User).
- ABAC (Attribute-Based access cantrol): Access based on conditions( time, location,user type).
![download](https://github.com/user-attachments/assets/423f188d-6952-4a02-9e54-bca98bcf25c6)

## Example:
 An "HR Manager" role can view employee data,while "Employee" role can only view their own profits.

 # Best Practies
 - Use stronge, unic passwords.
 - Apply MFA wherever possible.
 - REview role-based permission regularly.
 - Log all authentication and access events
