# IRCTC Registration Page – Manual Testing Project
## LINK https://docs.google.com/spreadsheets/d/1J-KfJif3J-BfHthT1FtDbSoAPSa4T-OKfvA0IYQVG1g/edit?gid=0#gid=0
## 📌 Project Overview

This project focuses on **Manual Testing of the IRCTC User Registration Page**.

The objective is to verify whether the registration form works correctly, validates user inputs, displays appropriate error messages, and handles valid and invalid test data properly.

## 🎯 Module Tested

**Module:** Register Page

### Registration Form Components

1. Username
2. Full Name
3. Password
4. Confirm Password
5. Mobile Number
6. Email
7. Verify Button
8. FAQ Section
9. Cancel Button

## 🧪 Testing Type

- Manual Testing
- Functional Testing
- Validation Testing
- Positive Testing
- Negative Testing
- UI Testing
- Test Metrics & Analytics

## 📋 Test Case Documentation

The test cases were maintained in **Microsoft Excel / Google Sheets**.

Each test case contains:

- Test Case ID
- Test Type
- Manual Testing Scenario
- Expected Output
- Actual Result
- Status
- Explanation

### Example

| Test Case | Type | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC_01 | Valid | Username | Username should be accepted | Username accepted | Pass |
| TC_02 | Valid | Username length | 3–35 characters allowed | Validation works | Pass |
| TC_05 | Invalid | Password ≠ Confirm Password | Password mismatch message | Incorrect validation | Fail |
| TC_07 | Invalid | Email without @ | Email should be rejected | Email accepted | Fail |

## 🔍 Test Scenarios Covered

### Username
- Valid username
- Minimum character validation
- Maximum character validation
- Numeric values
- Special characters
- Invalid username formats

### Full Name
- Valid full name
- Empty field
- Numeric characters
- Special characters

### Password
- Empty password
- Minimum length
- Maximum length
- Uppercase requirement
- Lowercase requirement
- Numeric requirement
- Special character requirement
- Repeated/sequential character validation

### Confirm Password
- Matching password
- Different password
- Empty confirm password

### Mobile Number
- Valid 10-digit number
- Less than 10 digits
- More than 10 digits
- Alphabetic characters
- Special characters

### Email
- Valid email
- Missing @ symbol
- Invalid domain
- Missing domain
- Empty email

### Other UI Components
- Verify button
- FAQ accordion
- FAQ expand/collapse
- Cancel button

