# Service Control Policies (SCPs)

SCPs restrict what AWS accounts can do inside AWS Organizations.

## Key Points

- SCPs do NOT grant permissions
- SCPs define maximum allowed permissions
- Affect all users including root user
- Management account is NOT affected

## Example

Deny S3 access:

```json
{
  "Effect": "Deny",
  "Action": "s3:*",
  "Resource": "*"
}
```

## Best Practice

Use SCPs as guardrails for:
- Region restrictions
- Service restrictions
- Security enforcement

## Screenshots

Add:
- SCP creation
- SCP attachment
- OU policy view