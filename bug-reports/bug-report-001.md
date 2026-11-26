# Bug Report BUG-001

## Summary

Cart items may remain after clicking Reset App State.

## Environment

- Application: SauceDemo
- Browser: Google Chrome
- Operating System: Not specified
- Testing Type: Manual Testing

## Preconditions

1. User is logged in.
2. At least one product is added to the shopping cart.

## Steps to Reproduce

1. Open the SauceDemo application.
2. Log in using valid credentials.
3. Add at least one product to the shopping cart.
4. Open the application menu.
5. Click Reset App State.
6. Open the shopping cart.
7. Check whether the product is still displayed.

## Expected Result

The application state should be reset and the shopping cart should be cleared.

## Actual Result

According to the initial tester observation, the product may remain in the shopping cart after clicking Reset App State.

## Severity

Not determined — requires verification.

## Priority

Not determined — requires verification.

## Status

Needs Verification.

## Attachments

No screenshots attached yet.

## Additional Notes

This issue was initially observed during exploratory testing.

The behavior must be reproduced and verified before this report can be classified as a confirmed defect.
