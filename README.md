# manual-ticket-purchase-testing
Manual QA project testing an online ticket purchase flow. Includes functional test cases, validation checks, UI/UX observations, and edge case scenarios. Focused on evaluating usability and form validation from an end-user perspective.

Manual Testing Project – Ticket Purchase Flow
Test Plan Summary
Feature: Online Ticket Purchase
Application: Public event ticketing website
Test Type: Manual Functional Testing
Tester: Marina Oliveira
Environment: Production (Read-only testing)

Objective
To validate the ticket purchase flow of a public event ticketing website (name withheld for confidentiality, ensuring users can select tickets, enter required information, and navigate the purchase process smoothly and intuitively. Everything was tested from the perspective of an external user.

In Scope
Ticket selection and quantity updates
Cart and order summary
User information form validation
UI/UX behavior
Basic accessibility checks
Error handling and edge cases

Out of Scope
Completing real payments
Verifying payment gateway transactions
Receiving confirmation emails
Backend data validation
(Payment-related test cases are marked as Blocked.)

Test Approach
Manual exploratory and functional testing
Expected behavior inferred from common e-commerce standards
Observations recorded when behavior cannot be confirmed due to missing requirements or access limitations

Test Deliverables
Test cases spreadsheet
Observations and blocked scenarios
Test plan summary

Risks & Limitations
No access to requirements or documentation
No test environment or sandbox payment method
Production testing without completing purchases

Defining assumptions 
Fields marked with * are required
Email field should accept valid email formats
Phone number should accept only numeric characters
Postal/ZIP code should accept the correct format for the country
Required fields should block progression if empty or invalid
Error messages should be visible, clear, and close to the field or on top of the page
Navigation via Continue button should only work when required info is valid

Priority, Severity & Status Definitions (Add as a Separate Sheet)

Priority (Business Impact)
High – Prevents ticket purchase or key user flow
Medium – Affects usability but workaround exists
Low – Cosmetic or minor UX issue

Severity (Technical Impact)
High – System failure, data loss, payment issues
Medium – Incorrect behavior, broken validation
Low – UI alignment, text issues

Status
Blocked – Cannot proceed due to scope or access limitations
Pass – Expected behavior observed
Fail – Expected behavior not met

Conclusion
The ticket purchase feature was reviewed for usability, validation, and flow consistency. While payment confirmation could not be fully tested, key pre-payment functionality and user interactions were evaluated, and potential risks were identified.

Marina Oliveira
Junior QA | Manual Testing | Test Case Design | Bug Reporting
