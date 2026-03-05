# Test Plan — SauceDemo (QA Manual Portfolio)

## 1. Objective
Validate the core user flow of SauceDemo and produce QA artifacts (test cases, checklists, bug reports, and summary).

## 2. Scope
### In scope
- Login
- Products listing & sorting
- Product details
- Add/Remove items to/from cart
- Cart page
- Checkout flow (Information → Overview → Complete)
- Logout

### Out of scope
- Performance/load testing
- Security testing
- Mobile app testing (native)
- Cross-browser testing beyond Chrome (initially)

## 3. Test approach
- Smoke testing using a checklist (basic health check)
- Regression checklist for broader coverage
- Manual test cases (positive + negative)
- Exploratory testing for UI/UX issues

## 4. Test environment
- URL: https://www.saucedemo.com/
- Browser / OS: Chrome (latest) / Windows 10

## 5. Entry & Exit criteria
### Entry
- Application is accessible
- Test environment is available

### Exit
- Smoke checklist executed
- 20+ test cases created
- At least 1 bug report documented
- Test summary report prepared

## 6. Risks & assumptions
- Demo environment may change without notice
- Some issues might be intentional (training demo)
- Limited browser coverage may miss browser-specific defects

## 7. Deliverables
- Test Plan
- Test Cases (Login/Products + Cart/Checkout)
- Smoke & Regression Checklists
- Bug reports
- Test Summary
