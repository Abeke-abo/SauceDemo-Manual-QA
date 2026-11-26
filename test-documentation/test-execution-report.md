# Test Execution Report — SauceDemo

## 1. Project Information

| Field | Details |
|---|---|
| Project | SauceDemo |
| Application | https://www.saucedemo.com/ |
| Testing Type | Manual Testing |
| Testing Level | UI / Functional Testing |
| Tester Role | Junior Manual QA Engineer |
| Report Status | In Progress |

## 2. Test Execution Overview

A total of 66 test cases are documented across four functional areas:

- Login
- Products
- Shopping Cart
- Checkout

Testing has been partially completed. The results below are based on the manual checks reported during the test session. No screenshots, screen recordings, or other formal evidence have been attached.

## 3. Execution Summary

| Test Suite | Total | Passed | Failed | Not Executed |
|---|---:|---:|---:|---:|
| Login | 15 | 10 | 0 | 5 |
| Products | 18 | 8 | 0 | 10 |
| Shopping Cart | 15 | 0 | 0 | 15 |
| Checkout | 18 | 0 | 0 | 18 |
| **Total** | **66** | **18** | **0** | **48** |

## 4. Detailed Execution Results

### 4.1 Login Testing

**Status:** Partially Completed

10 test cases were reported as successfully executed.

Verified scenarios included:

- Login with valid credentials.
- Login with an invalid username.
- Login with an invalid password.
- Login with an empty username.
- Login with an empty password.
- Login with both fields empty.
- Username input containing leading or trailing spaces.
- Login with a non-existing user.
- Login again after logging out.

**Result:** 10 Passed, 0 Failed, 5 Not Executed.

Note: The results are based on reported manual observations. Exact error messages and supporting evidence were not recorded.

### 4.2 Products Testing

**Status:** Partially Completed

8 test cases were reported as successfully executed.

Verified scenarios included:

- Product names are displayed.
- Product descriptions are displayed.
- Product prices are displayed.
- All expected products are visible.
- Sorting products by Name (A to Z).
- Sorting products by Name (Z to A).
- Sorting products by Price (low to high).
- Checking that the displayed order matches the selected sorting option.

**Result:** 8 Passed, 0 Failed, 10 Not Executed.

The Price (high to low) sorting option and other unverified product-related scenarios remain pending.

### 4.3 Shopping Cart Testing

**Status:** Not Started

No test cases have been executed.

**Result:** 0 Passed, 0 Failed, 15 Not Executed.

### 4.4 Checkout Testing

**Status:** Not Started

No test cases have been executed.

**Result:** 0 Passed, 0 Failed, 18 Not Executed.

## 5. Defects and Observations

One potential issue was observed during exploratory testing:

- **Issue:** Clicking the "Reset App State" option appeared not to clear the shopping cart.
- **Status:** Needs Verification.
- **Details:** The behavior has not yet been reproduced and confirmed through a dedicated test case.

This observation is not counted as a confirmed defect.

## 6. Testing Limitations

- Testing is performed manually.
- Formal test evidence has not been collected.
- Some test scenarios remain unexecuted.
- The potential Reset App State issue requires further investigation.
- The current report reflects only the checks completed so far.

## 7. Conclusion

A total of 18 out of 66 documented test cases have been reported as passed.

No confirmed failures have been recorded at this stage.

Login and Products testing are partially completed. Shopping Cart and Checkout testing have not started.

Further execution is required before the application can be considered fully tested.

## 8. Next Steps

- Complete the remaining Login test cases.
- Complete the remaining Products test cases.
- Execute all Shopping Cart test cases.
- Execute all Checkout test cases.
- Investigate the Reset App State observation.
- Collect screenshots or other evidence for test results.
- Update the execution summary after further testing.
