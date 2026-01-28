# Test Intent Over Implementation

Tests should express *why* a behavior matters,
not *how* the system is implemented.

## Example
Good:
- Authorized user can place a trade

Bad:
- POST /trade returns 201

## Benefit
- Tests survive refactoring
- Failures are business-readable
