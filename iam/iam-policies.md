# IAM Policies

IAM Policies define permissions in AWS.

Policies are written in JSON and attached to:
- Users
- Groups
- Roles

## Types

### Managed Policies
Reusable policies managed separately.

### Inline Policies
Directly attached to one identity.

## Policy Structure

```json
{
  "Effect": "Allow",
  "Action": "s3:*",
  "Resource": "*"
}
```

## Important Rules

- Explicit DENY always wins
- Default is DENY
- Policies only grant permissions when attached

## Common Use Cases

- S3 access
- EC2 management
- Read-only access
- Admin access

## Screenshots

Add:
- Policy creation
- JSON editor
- Policy attachment