SWAG LABS – Manual QA Testing

Project Overview

This repository contains my submission for the Software QA Assignment based on the Swag Labs (SauceDemo) web application.

The project focuses on manual functional testing and exploratory testing of the application. The main objective was to understand the application flow, execute test scenarios, identify defects, and document them clearly with reproducible steps.

Application: Swag Labs
Website: https://www.saucedemo.com/
Testing Type: Manual QA / Functional Testing / Exploratory Testing
Test Account: "problem_user"
Password: "secret_sauce"

---

Testing Scope

The following areas of the application were tested:

- Login
- Product listing
- Product details
- Product selection
- Add to Cart
- Shopping Cart
- Remove from Cart
- Checkout
- Checkout form behavior

---

Testing Approach

The application was tested manually using a combination of:

Functional Testing

Verified whether the main application functions behave as expected.

UI Testing

Checked product names, images, buttons, input fields, and other visible elements.

Negative Testing

Tested invalid and restricted user scenarios where applicable.

Exploratory Testing

Explored the application beyond the predefined test cases to identify unexpected behavior and less obvious defects.

Risk-Based Testing

Focused more attention on areas that directly affect the user's ability to purchase products, such as product selection, cart functionality, and checkout.

---

Test Plan

The test plan covers:

- Testing objective
- Scope
- Testing types
- Test environment
- Test data
- Test cases
- Risk assessment
- Entry and exit criteria

The detailed test plan is included in the repository.

---

Test Data

The Swag Labs application provides different test users.

Username| Purpose
"standard_user"| Normal application functionality
"locked_out_user"| Locked-user login testing
"problem_user"| Exploratory testing and defect identification
"performance_glitch_user"| Performance-related behavior

Password: "secret_sauce"

---

Bugs Identified

During exploratory testing with the "problem_user" account, I identified the following five defects:

Bug ID| Module| Description| Severity| Priority
BUG-001| Product Details| Incorrect product opens after product selection| High| High
BUG-002| Product Details / Cart| Add to Cart does not work from the product details page| High| High
BUG-003| Shopping Cart| Remove button does not remove the product| High| High
BUG-004| Products / Cart| Some products cannot be added to the cart| High| High
BUG-005| Checkout| Checkout focus unexpectedly moves to the First Name field| High| High

Each bug report contains:

- Bug ID
- Title
- Module
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- User impact

---

Test Cases

The main test scenarios covered:

1. Login with valid credentials
2. Login with a locked-out user
3. Add a product to the cart
4. Remove a product from the cart
5. Complete the checkout process

Additional exploratory scenarios were performed to identify defects that were not limited to the predefined test cases.

---

Test Environment

Item| Details
Application| Swag Labs
URL| https://www.saucedemo.com/
Testing| Manual
Device| Desktop/Laptop
Operating System| [windows]
Browser| [Google Chrome]
Primary Test User| "problem_user"

«The operating system and browser should reflect the actual environment used during testing.»

---

Deliverables

This repository contains the QA assignment deliverables:

- Test Plan
- Test Cases
- Bug Reports
- Supporting screenshots/evidence, where applicable
- Video links, where applicable

Video Demonstration

Manual Bug Discovery Demo:
https://www.loom.com/share/6c9bb75570504c55ac63aa3424f70df1

The video demonstrates the five identified bugs and explains their expected behavior, actual behavior, severity, and potential user impact.

---

Skills Demonstrated

Through this assignment, I demonstrated:

- Manual Functional Testing
- Exploratory Testing
- Test Case Design
- Bug Identification
- Bug Reporting
- Severity and Priority Assessment
- Defect Reproduction
- User Impact Analysis
- QA Mindset
- Attention to Detail

---

Conclusion

This project demonstrates my approach to manual QA testing by starting with the expected application behavior, exploring the application from a user's perspective, identifying unexpected behavior, and documenting defects with clear reproduction steps.

The focus of this project is on manual QA testing and defect identification rather than test automation.
