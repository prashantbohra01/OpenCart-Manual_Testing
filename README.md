*OpenCart Manual Testing Project*
This repository contains comprehensive documentation and test cases for the manual testing of the OpenCart e-commerce platform. The project includes test scenarios, test cases, a requirements traceability matrix, and other artifacts to ensure the robustness and quality of OpenCart’s core functionalities.

Table of Contents
Project Overview
Project Scope
Documents and Artifacts
Test Scenarios
Sample Test Cases
Requirements Traceability Matrix (RTM)
How to Contribute
License
Project Overview
OpenCart is an open-source e-commerce solution widely used for building online stores. This manual testing project aims to verify and validate the core functionality of OpenCart, identifying any bugs, usability issues, or non-compliance with functional requirements. The project covers end-to-end scenarios for customer-facing and admin modules, including user registration, product browsing, cart management, checkout, payment processing, and administration.

Project Scope
The manual testing covers the following modules:

User Module: User registration, login, profile management, and order history.
Product Module: Product browsing, category filters, and product details.
Cart and Checkout Module: Adding/removing products from the cart, updating quantities, applying discounts, and checkout processes.
Payment Processing Module: Payment gateway integrations, handling payment success and failure scenarios.
Admin Module: Product management, order management, and user role management.
Each module is thoroughly tested to ensure functional accuracy, data integrity, security, and usability.

Documents and Artifacts
This repository includes the following key documents:

Functional Requirements Specification (FRS): Outlines the expected functionality for each OpenCart module.
Test Scenarios: High-level scenarios that cover major actions and workflows.
Test Cases: Detailed test cases with steps, expected results, and status for each test.
Requirements Traceability Matrix (RTM): Maps each requirement to its respective test case(s) to ensure complete test coverage.
Test Scenarios
Here are some high-level test scenarios covered in this project:

User Registration and Login

Ensure that new users can register successfully.
Verify login functionality for registered users and handle invalid login attempts.
Product Browsing and Filtering

Verify that users can browse products by category and apply relevant filters.
Ensure search functionality returns accurate results based on keywords.
Shopping Cart Management

Verify users can add, update, and remove items from the cart.
Ensure correct calculations for quantities and discounts applied to the cart.
Checkout and Payment

Validate the checkout process, including address management, shipping options, and order summary.
Verify that payments are processed correctly through different gateways (e.g., credit card, PayPal).
Admin Product Management

Ensure that admins can add, update, and delete products.
Verify that admin role restrictions are in place for user roles.
Sample Test Cases
Here are examples of test cases for common OpenCart functions:

Test Case ID	Description	Precondition	Steps	Expected Result
TC-01	Register with valid details	User not registered	1. Go to registration page
2. Enter valid details
3. Submit form	User successfully registers and logs in
TC-05	Add product to cart	User is logged in, product exists	1. Go to product page
2. Click "Add to Cart"	Product added to cart with correct quantity
TC-08	Checkout process with valid payment	User has items in cart, is logged in	1. Go to checkout
2. Fill in shipping and payment details
3. Confirm order	Payment processed, confirmation displayed
The complete list of test cases is available in the Test Cases Document.

Requirements Traceability Matrix (RTM)
The RTM ensures all requirements are mapped to corresponding test cases, guaranteeing thorough coverage and traceability. Here’s a sample:

Requirement ID	Requirement Description	Test Case ID(s)
FR-01	User Registration	TC-01, TC-02
FR-03	Product Search	TC-10, TC-11
FR-04	Shopping Cart	TC-15, TC-16
FR-06	Admin Product Management	TC-30, TC-31
The complete RTM is available in the RTM Document.

How to Contribute
Contributions to this project are welcome! To add new test cases, scenarios, or improve documentation, follow these steps:

Fork the Repository: Fork this repo to your GitHub account.
Create a Branch: Create a new branch for your feature or improvement.
Submit a Pull Request: After making your changes, submit a pull request. Ensure all new additions are well-documented.
For significant changes, please open an issue first to discuss your ideas.

License
This project is licensed under the MIT License. See the LICENSE file for details.
