# IAM Users, Groups, and Roles

## IAM User

An IAM user represents a person or application that needs access to AWS.

Examples:
- Admin user
- Developer user
- CLI automation user

---

## IAM Group

IAM groups are collections of IAM users.

Groups simplify permission management by assigning policies to multiple users at once.

Example:
- Developers group
- Administrators group

---

## IAM Role

IAM roles provide temporary AWS credentials.

Roles are commonly used by:
- EC2 instances
- Lambda functions
- Cross-account access

Unlike IAM users, roles do not have permanent credentials.

---

## Key Difference

| Component | Purpose |
|---|---|
| User | Identity for a person/application |
| Group | Organize users |
| Role | Temporary delegated access |

---

## Important Concepts

- IAM is a global AWS service
- Root user should not be used daily
- MFA should be enabled
- Least privilege principle is important