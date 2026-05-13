# S3 Lifecycle Rules

Lifecycle rules automate object transitions and deletions.

## Actions

### Transition
Move objects to cheaper storage classes.

### Expiration
Automatically delete objects.

## Benefits

- Cost optimization
- Automated storage management

## Example

```text
30 days → Standard-IA
90 days → Glacier
365 days → Delete
```

## Screenshots

Add:
- Lifecycle rule creation
- Transition settings