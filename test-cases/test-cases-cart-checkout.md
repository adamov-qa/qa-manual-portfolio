# Test Cases — Cart & Checkout (SauceDemo)

**URL:** https://www.saucedemo.com/  
**Precondition (unless stated):** User is logged in as `standard_user`.

---

### TC-011 — Add item to cart from Products
**Steps**
1. On Products page, click **Add to cart** for any item
2. Observe cart badge
**Expected**
- Button changes to **Remove**
- Cart badge increments to 1

---

### TC-012 — Remove item from cart from Products
**Precondition:** At least 1 item is added
**Steps**
1. Click **Remove** for the added item
2. Observe cart badge
**Expected**
- Button changes back to **Add to cart**
- Cart badge decrements / disappears

---

### TC-013 — Cart page shows correct items
**Precondition:** Add 2 different items
**Steps**
1. Click cart icon
2. Observe cart items list
**Expected**
- Both added items are listed
- Names and prices are visible

---

### TC-014 — Remove item from Cart page
**Precondition:** At least 1 item is in cart
**Steps**
1. Open Cart page
2. Click **Remove** for one item
**Expected**
- Item is removed from the list
- Cart badge updates accordingly

---

### TC-015 — Continue shopping returns to Products
**Steps**
1. Open Cart page
2. Click **Continue Shopping**
**Expected**
- User is redirected to Products page

---

### TC-016 — Start checkout from Cart
**Precondition:** At least 1 item is in cart
**Steps**
1. Open Cart page
2. Click **Checkout**
**Expected**
- User is redirected to **Checkout: Your Information** page

---

### TC-017 — Checkout information: required fields validation
**Steps**
1. On Checkout: Your Information page, leave fields empty
2. Click **Continue**
**Expected**
- Validation/error message is displayed
- User stays on the same page

---

### TC-018 — Checkout information: successful continue
**Precondition:** At least 1 item is in cart
**Steps**
1. Enter First Name, Last Name, Postal Code
2. Click **Continue**
**Expected**
- User is redirected to **Checkout: Overview**
- Selected items are listed

---

### TC-019 — Finish checkout shows confirmation
**Precondition:** On Checkout: Overview page
**Steps**
1. Click **Finish**
**Expected**
- User sees **Checkout: Complete**
- Confirmation message is displayed

---

### TC-020 — Cancel checkout returns to Cart/Products
**Steps**
1. Start checkout from Cart
2. On Checkout: Your Information click **Cancel**
**Expected**
- User returns to Cart page (or previous step)
