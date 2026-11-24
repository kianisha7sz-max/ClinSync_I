
# Security Policy

## ClinSync – Clinical Learning Platform

ClinSync is committed to maintaining the security, privacy, and integrity of its platform. We take security vulnerabilities seriously and encourage responsible disclosure to help protect our users and their information.

## 1. Supported Versions

Security updates are primarily provided for the latest version of ClinSync maintained in the main branch.

| Version | Security Support |
|---|---|
| Latest version (main) | Supported |
| Older versions | Not guaranteed |

## 2. Reporting a Vulnerability

If you discover a potential security vulnerability in ClinSync, please report it privately.

**Reporting method:**
- Use GitHub's Private Vulnerability Reporting feature, if enabled.
- Alternatively, contact the repository maintainer through a designated security contact.

Please include:
- A clear description of the vulnerability.
- The affected component or feature.
- Steps to reproduce the issue, where safe and appropriate.
- The potential security impact.
- Any relevant screenshots or logs, with personal information removed.

Please do not disclose vulnerabilities publicly before the maintainer has had an opportunity to investigate.

## 3. Scope of Security Concerns

The project welcomes reports involving:

- Unauthorized access to student or instructor accounts.
- Authentication and session management vulnerabilities.
- Improper access to Firestore records.
- Student and instructor role authorization weaknesses.
- Exposure of confidential information.
- Insecure file uploads or unauthorized file access.
- Cross-site scripting (XSS).
- Injection vulnerabilities.
- Exposed API credentials, private keys, or environment variables.
- Insecure communication between the application and its backend services.

## 4. Security Practices

ClinSync aims to follow these security practices:

### Authentication and Account Protection
- Use Firebase Authentication for account management.
- Protect user credentials and authentication sessions.
- Apply appropriate account access restrictions.
- Prevent unauthorized account access.

### Authorization and Role Management
- Enforce access permissions for students and clinical instructors.
- Restrict access to records according to authenticated user identity and assigned role.
- Validate permissions through backend and database security rules, not merely frontend controls.

### Data Protection
- Restrict access to student profiles and academic records.
- Protect submitted files and educational records from unauthorized access.
- Avoid collecting or exposing unnecessary personal information.
- Use secure connections when communicating with cloud services.

### File Upload Security
- Validate uploaded file types and sizes.
- Restrict access to uploaded submissions.
- Prevent unauthorized access to files and stored records.

### Credential and Configuration Security
- Never commit passwords, private keys, service account credentials, or other confidential secrets to the repository.
- Store server-side credentials in environment variables or an appropriate secrets manager.
- Restrict public API credentials to the services and domains that require them.

## 5. Responsible Disclosure

Security researchers and contributors are expected to:

- Avoid accessing, modifying, or exposing other users' personal information.
- Avoid disrupting the availability of the platform.
- Avoid testing against real student accounts or private records without authorization.
- Report discovered vulnerabilities privately.
- Allow maintainers reasonable time to investigate and address reported issues.

## 6. Privacy and Sensitive Information

ClinSync is an educational clinical learning platform.

Users and contributors must not upload or publicly disclose:
- Passwords or authentication tokens.
- Private account information.
- Confidential student records.
- Sensitive personal information.
- Real patient information or identifiable clinical records.

## 7. Security Updates

The maintainers will review reported vulnerabilities, assess their severity, and implement appropriate security fixes.

Updates may include:
- Authentication improvements.
- Database security rule updates.
- Access control improvements.
- Dependency updates.
- File upload and storage security improvements.

## 8. Contact

For security-related concerns, please use the repository's private vulnerability reporting feature or contact the project maintainer through the designated security contact.

Thank you for helping keep ClinSync and its community secure.
