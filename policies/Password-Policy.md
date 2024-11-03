# Zeudi Password Policy

## Document Information
- **Document ID:** PWP-001
- **Classification:** Public
- **Version:** 1.0
- **Effective Date:** 11/03/2024
- **Review Date:** 11/03/2025

## Purpose
This Password Policy defines the requirements for creating and managing passwords across Zeudi's streaming platform to ensure secure access to user accounts, artist portals, and administrative systems.

## Scope
This policy applies to:
- User account passwords
- Artist and label portal credentials
- Administrative accounts
- API access tokens
- Service account credentials
- Developer account access
- Content management systems

## Policy Requirements

### 1. Password Creation
1.1. Minimum Requirements by Account Type:

Standard User Accounts:
- Length: At least 10 characters
- Complexity: Must include:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special characters recommended

Artist/Label Portal Accounts:
- Length: At least 12 characters
- Complexity: Must include all of:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special characters (!@#$%^&*(),.?":{}|<>)

Administrative/Developer Accounts:
- Length: At least 16 characters
- Complexity: Must include all of:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special characters (!@#$%^&*(),.?":{}|<>)
  - No common patterns

1.2. Prohibited Content:
- Dictionary words
- Sequential numbers/letters
- Personal information
- Previous passwords
- Company name "Zeudi"
- Common substitutions

### 2. Password Management
2.1. Change Requirements:

Standard User Accounts:
- Change recommended every 180 days
- Must change if compromise suspected
- Cannot reuse last 5 passwords

Artist/Label Accounts:
- Mandatory change every 90 days
- Cannot reuse last 8 passwords
- Immediate change after staff changes

Administrative Accounts:
- Mandatory change every 60 days
- Cannot reuse last 12 passwords
- Change after privilege modifications

2.2. Storage and Protection:
- All passwords must be hashed (not stored in plain text)
- Password managers must be company-approved
- No sharing of credentials
- No storing in unsecured locations
- Multi-factor authentication required for sensitive accounts

### 3. Account Lockout
3.1. Lockout Parameters by Account Type:

Standard User Accounts:
- Lock after 5 failed attempts
- 15-minute lockout duration
- Reset counter after successful login

Artist/Label Portal:
- Lock after 4 failed attempts
- 30-minute lockout duration
- Support ticket required after 3 lockouts

Administrative Accounts:
- Lock after 3 failed attempts
- 60-minute lockout duration
- Security team notification
- Manual unlock required

### 4. System Requirements
4.1. Technical Controls:
- Secure password reset mechanism
- Encryption of passwords in transit
- Strong hashing algorithms
- Password strength meters
- Breach detection systems

4.2. Authentication Requirements:
- MFA required for:
  - Administrative access
  - Artist/label portals
  - Financial operations
  - Content management
  - API access
  - Remote access

### 5. Special Circumstances
5.1. API Tokens and Service Accounts:
- Automatic rotation every 30 days
- Strict access limitations
- Monitoring and logging
- Emergency revocation process

5.2. Emergency Access:
- Break-glass procedures
- Documented approval process
- Security team notification
- Immediate password change after use

## Roles and Responsibilities
- **Users:** Follow password requirements
- **Security Team:** Policy enforcement
- **IT Support:** Password reset assistance
- **Development Team:** Implementation
- **Security Team:** Monitoring and audit

## Compliance and Enforcement
- Regular password audits
- Automated compliance checking
- Security awareness training
- Violation reporting
- Progressive disciplinary actions

## Related Documents
- Information Security Policy
- Acceptable Use Policy
- Access Control Policy
- Multi-Factor Authentication Policy

## Review and Updates
This policy shall be reviewed quarterly to maintain alignment with current security best practices and emerging threats in the streaming industry.
