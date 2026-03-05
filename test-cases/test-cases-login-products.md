# Test Cases — Login & Products (SauceDemo)

**URL:** https://www.saucedemo.com/  
**Precondition (unless stated):** User is on Login page.

---

### TC-001 — Login with valid credentials
**Steps**
1. Enter valid username (e.g. `standard_user`)
2. Enter valid password (e.g. `secret_sauce`)
3. Click **Login**
**Expected**
- User is redirected to **Products** page
- Products list is visible

---

### TC-002 — Login with invalid password
**Steps**
1. Enter username `standard_user`
2. Enter wrong password
3. Click **Login**
**Expected**
- Error message is displayed
- User stays on Login page

---

### TC-003 — Login with empty username and password
**Steps**
1. Leave username empty
2. Leave password empty
3. Click **Login**
**Expected**
- Validation/error message is displayed

---

### TC-004 — Login with empty password
**Steps**
1. Enter username `standard_user`
2. Leave password empty
3. Click **Login**
**Expected**
- Validation/error message is displayed

---

### TC-005 — Login with empty username
**Steps**
1. Leave username empty
2. Enter password `secret_sauce`
3. Click **Login**
**Expected**
- Validation/error message is displayed

---

### TC-006 — Products page displays correct UI elements
**Precondition:** Logged in successfully
**Steps**
1. Observe Products page
**Expected**
- Products list is displayed
- Each product has name, price, image, and Add to cart button
- Cart icon is visible

---

### TC-007 — Open product details page
**Precondition:** Logged in successfully
**Steps**
1. Click on a product name or image
**Expected**
- Product details page opens
- Product name and price are visible

---

### TC-008 — Back to Products from details page
**Precondition:** On product details page
**Steps**
1. Click **Back to products**
**Expected**
- User returns to Products list page

---

### TC-009 — Sort products by Price (low to high)
**Precondition:** Logged in successfully
**Steps**
1. Open sort dropdown
2. Select **Price (low to high)**
**Expected**
- Products are sorted by price ascending

---

### TC-010 — Sort products by Name (Z to A)
**Precondition:** Logged in successfully
**Steps**
1. Open sort dropdown
2. Select **Name (Z to A)**
**Expected**
- Products are sorted by name descending
