# Products Module — Test Cases

## 1. Module Information

**Application:** SauceDemo

**Module:** Products

**Testing Type:** Functional Testing / UI Testing

**Priority:** High

## 2. Test Cases

### TC-PROD-001: Verify products page is displayed

**Priority:** High

**Steps:**
1. Log in using valid credentials.
2. Open the Products page.

**Expected Result:**
The Products page is displayed successfully.

**Execution Status:** PASS (Executed)

---

### TC-PROD-002: Verify all products are displayed

**Priority:** High

**Steps:**
1. Open the Products page.
2. Observe the product catalog.

**Expected Result:**
All available products are displayed in the catalog.

**Execution Status:** PASS (Executed)

---

### TC-PROD-003: Verify product names

**Priority:** Medium

**Steps:**
1. Open the Products page.
2. Check the name of each product.

**Expected Result:**
Every product has a visible name.

**Execution Status:** PASS (Executed)

---

### TC-PROD-004: Verify product descriptions

**Priority:** Medium

**Steps:**
1. Open the Products page.
2. Inspect product descriptions.

**Expected Result:**
Every product has a visible description.

**Execution Status:** PASS (Executed)

---

### TC-PROD-005: Verify product prices

**Priority:** High

**Steps:**
1. Open the Products page.
2. Inspect the displayed prices.

**Expected Result:**
Every product has a visible price.

**Execution Status:** PASS (Executed)

---

### TC-PROD-006: Verify product images

**Priority:** Medium

**Steps:**
1. Open the Products page.
2. Inspect all product images.

**Expected Result:**
All product images are displayed correctly.

**Execution Status:** NOT EXECUTED

---

### TC-PROD-007: Sort products by Name (A to Z)

**Priority:** Medium

**Steps:**
1. Open the sorting dropdown.
2. Select Name (A to Z).
3. Observe the product order.

**Expected Result:**
Products are displayed in alphabetical ascending order.

**Execution Status:** PASS (Executed)

---

### TC-PROD-008: Sort products by Name (Z to A)

**Priority:** Medium

**Steps:**
1. Open the sorting dropdown.
2. Select Name (Z to A).
3. Observe the product order.

**Expected Result:**
Products are displayed in alphabetical descending order.

**Execution Status:** PASS (Executed)

---

### TC-PROD-009: Sort products by Price (Low to High)

**Priority:** High

**Steps:**
1. Open the sorting dropdown.
2. Select Price (low to high).
3. Compare product prices.

**Expected Result:**
Products are displayed in ascending price order.

**Execution Status:** PASS (Executed)

---

### TC-PROD-010: Sort products by Price (High to Low)

**Priority:** High

**Steps:**
1. Open the sorting dropdown.
2. Select Price (high to low).
3. Compare product prices.

**Expected Result:**
Products are displayed in descending price order.

**Execution Status:** NOT EXECUTED

---

### TC-PROD-011: Verify sorting dropdown options

**Priority:** Medium

**Steps:**
1. Open the sorting dropdown.
2. Inspect all available options.

**Expected Result:**
The following sorting options are available:
- Name (A to Z)
- Name (Z to A)
- Price (low to high)
- Price (high to low)

**Execution Status:** NOT EXECUTED

---

### TC-PROD-012: Verify product price format

**Priority:** Medium

**Steps:**
1. Open the Products page.
2. Inspect all product prices.

**Expected Result:**
Prices are displayed in a consistent currency format.

**Execution Status:** NOT EXECUTED

---

### TC-PROD-013: Verify product price values

**Priority:** Medium

**Steps:**
1. Open the Products page.
2. Inspect every product price.

**Expected Result:**
All product prices contain valid positive numeric values.

**Execution Status:** NOT EXECUTED

---

### TC-PROD-014: Verify product details navigation

**Priority:** Medium

**Steps:**
1. Open the Products page.
2. Click a product name.
3. Observe the product details page.

**Expected Result:**
The application opens the corresponding product details page.

**Execution Status:** NOT EXECUTED

---

### TC-PROD-015: Verify product details information

**Priority:** Medium

**Preconditions:**
- Product details page is opened.

**Steps:**
1. Inspect the product name.
2. Inspect the product description.
3. Inspect the product price.
4. Inspect the product image.

**Expected Result:**
All product details correspond to the selected product.

**Execution Status:** NOT EXECUTED

---

### TC-PROD-016: Verify sorting persistence after page refresh

**Priority:** Low

**Steps:**
1. Select a sorting option.
2. Refresh the browser page.
3. Observe the sorting option and product order.

**Expected Result:**
The application handles the selected sorting state consistently with its intended behavior.

**Execution Status:** NOT EXECUTED

---

### TC-PROD-017: Verify product count

**Priority:** Medium

**Steps:**
1. Open the Products page.
2. Count the displayed products.

**Expected Result:**
The number of displayed products matches the available product catalog.

**Execution Status:** NOT EXECUTED

---

### TC-PROD-018: Verify sorting after changing the option

**Priority:** Medium

**Steps:**
1. Select Name (A to Z).
2. Observe the product order.
3. Change the sorting option to Price (low to high).
4. Observe the product order again.

**Expected Result:**
The product catalog is reordered according to the newly selected sorting option.

**Execution Status:** NOT EXECUTED

## 3. Test Execution Summary

| Status | Count |
|---|---:|
| PASS | 9 |
| FAIL | 0 |
| NOT EXECUTED | 9 |
| Total | 18 |

**Note:** Execution results are based on the available observations. All remaining scenarios require verification.
