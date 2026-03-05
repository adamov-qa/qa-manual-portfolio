# Smoke Checklist — SauceDemo

**Environment**
- Browser: Chrome (latest)
- URL: https://www.saucedemo.com/

## Authentication
- [ ] Login with valid user works (redirect to Products)
- [ ] Login with invalid password shows an error
- [ ] Login with empty username/password shows validation/error

## Products
- [ ] Products page loads and shows list of items
- [ ] Sorting works (Name/Price)
- [ ] Product details page opens from item click

## Cart
- [ ] Add to cart from Products works (badge count updates)
- [ ] Remove from cart works (badge count updates)
- [ ] Cart page opens and shows added items

## Checkout
- [ ] Checkout flow starts from Cart
- [ ] Required fields validation works (First/Last/Postal)
- [ ] Finish order shows confirmation

## Basic UI/Navigation
- [ ] Logout works
- [ ] Back/Navigation does not break the flow
