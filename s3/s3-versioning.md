# S3 Versioning

Versioning stores multiple versions of objects in a bucket.

## Benefits

- Protects against accidental deletion
- Recovery of older versions
- Better backup protection

## Important Notes

- Once enabled, cannot be permanently disabled
- Can only be suspended

## Delete Marker

Deleting an object creates a delete marker instead of removing data.

## MFA Delete

Adds MFA protection for:
- Deleting object versions
- Changing versioning settings

## Screenshots

Add:
- Enabling versioning
- Viewing object versions
- Delete markers