# Regression Checklist — SauceDemo

**Environment**
- Browser: Chrome (latest)
- URL: https://www.saucedemo.com/

## Login & Session
- [ ] Valid login works for standard user
- [ ] Invalid login shows error message
- [ ] Empty credentials show validation/error
- [ ] User stays logged in after page refresh
- [ ] Logout ends the session (cannot access Products without login)

## Products List
- [ ] Products page loads correctly
- [ ] Each product shows name, price, image, Add to cart button
- [ ] Sorting: Name (A→Z) works
- [ ] Sorting: Name (Z→A) works
- [ ] Sorting: Price (low→high) works
- [ ] Sorting: Price (high→low) works

## Product Details
- [ ] Open product details from list
- [ ] Back to products returns to list
- [ ] Add to cart works from details page
- [ ] Remove works from details page

## Cart
- [ ] Add multiple items from products list
- [ ] Cart badge count matches added items
- [ ] Cart page shows correct items, names and prices
- [ ] Remove item from cart updates list and badge
- [ ] Continue shopping returns to Products
- [ ] Cart persists after refresh

## Checkout — Information
- [ ] Checkout starts from cart
- [ ] First Name required validation works
- [ ] Last Name required validation works
- [ ] Postal Code required validation works
- [ ] Cancel returns to cart
- [ ] Continue proceeds to Overview with correct items

## Checkout — Overview
- [ ] Item total is calculated correctly
- [ ] Tax is displayed
- [ ] Total is displayed
- [ ] Finish completes the order
- [ ] Cancel returns to Products

## Checkout — Complete
- [ ] Confirmation page is displayed
- [ ] Back Home returns to Products

## UI & Navigation
- [ ] Menu opens/closes
- [ ] About link opens (if available)
- [ ] Footer/social links (if available) work
- [ ] No broken layout in common resolutions (desktop)

## Negative / Edge
- [ ] Removing an item not in cart is not possible (no unexpected states)
- [ ] Cart with 0 items cannot complete checkout without adding items
