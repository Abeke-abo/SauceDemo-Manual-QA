# Test Summary Report — SauceDemo

## 1. Project Information

| Field | Details |
|---|---|
| Project | SauceDemo |
| Application | https://www.saucedemo.com/ |
| Testing Type | Manual Functional Testing |
| Testing Level | UI Testing |
| Tester Role | Junior Manual QA Engineer |
| Report Status | In Progress |

## 2. Testing Objectives

The purpose of testing was to evaluate the main user flows and verify the functional behavior of the SauceDemo application.

The testing scope included:

- User authentication.
- Product listing and sorting.
- Shopping cart operations.
- Checkout process.

## 3. Test Execution Summary

A total of 66 test cases have been documented.

| Test Suite | Total | Passed | Failed | Not Executed |
|---|---:|---:|---:|---:|
| Login | 15 | 10 | 0 | 5 |
| Products | 18 | 8 | 0 | 10 |
| Shopping Cart | 15 | 0 | 0 | 15 |
| Checkout | 18 | 0 | 0 | 18 |
| **Total** | **66** | **18** | **0** | **48** |

### Overall Progress

- Executed: 18 test cases.
- Passed: 18 test cases.
- Failed: 0 test cases.
- Not Executed: 48 test cases.

The current execution progress is approximately 27% of the documented test cases.

## 4. Testing Results by Area

### 4.1 Login

Login testing was partially completed.

The reported checks covered valid and invalid credentials, empty input fields, whitespace in the username, and login after logout.

No failures were reported during these checks.

### 4.2 Products

Products testing was partially completed.

The reported checks covered product information visibility and several sorting options:

- Name (A to Z).
- Name (Z to A).
- Price (low to high).

Price (high to low) and other scenarios remain unverified.

### 4.3 Shopping Cart

Shopping Cart testing has not started.

All 15 documented test cases remain unexecuted.

### 4.4 Checkout

Checkout testing has not started.

All 18 documented test cases remain unexecuted.

## 5. Defects and Risks

No confirmed defects have been recorded.

One observation requires further investigation:

**Reset App State**

The Reset App State option appeared not to clear the shopping cart during an initial observation. This behavior has not been reproduced or confirmed.

Status: Needs Verification.

### Testing Risks

- A significant number of test cases remain unexecuted.
- No formal screenshots or execution evidence have been collected.
- Shopping Cart and Checkout functionality have not yet been tested.
- The Reset App State observation remains unresolved.

## 6. Overall Assessment

Testing is still in progress.

The completed checks did not reveal any reported failures. However, the current results are insufficient to assess the overall quality of the application because most documented test cases have not been executed.

No final quality or release-readiness conclusion can be made at this stage.

## 7. Recommendations

The following activities are recommended:

1. Complete the remaining Login test cases.
2. Finish Products testing, including all sorting options.
3. Execute the Shopping Cart test suite.
4. Execute the Checkout test suite.
5. Reproduce and investigate the Reset App State observation.
6. Capture screenshots for important test results.
7. Update test execution statuses and this report after additional testing.

## 8. Final Conclusion

The SauceDemo manual testing project has made partial progress.

18 of 66 documented test cases have been reported as passed. The remaining 48 test cases require execution.

The project remains **In Progress**.
