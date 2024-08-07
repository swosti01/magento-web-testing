# Magento-web-testing
Manual Testing on a Magento Website

## Project Overview

This repository contains the test cases, bug reports, and improvement areas identified while performing manual testing on a [Magento](https://magento.softwaretestingboard.com/). This project aims to provide comprehensive testing documentation and insights to enhance the quality and performance of the Magento website.

## Test Cases

This section includes detailed test cases for various functionalities of the Magento website. Each test case is designed to ensure the proper functioning of different components and features.

### Example Test Case
Login:

**Test Case ID**: M_01

**Title**: Verify the login functionality with valid credentials

**Preconditions**:
-The user is on the Magento login page.

**Steps**:
1. Enter a valid username.
2. Enter a valid password.
3. Click on the 'Login' button.

**Expected Result**:
-The user should be redirected to the dashboard page.

**Actual Result**:
- With a valid email and password, the system logged in successfully and redirected to the My Account page.




## Bug Reports

This section contains documented bug reports identified during the manual testing process. Each report includes details on reproducing the issue, the expected result, and the actual result.

### Example Bug Report

**Bug ID**: BUG001

**Title**: Login page does not display an error message for invalid credentials

**Description**:
When a user enters invalid credentials and clicks on the 'Login' button, the system does not display an appropriate error message.

**Steps to Reproduce**:
1. Go to the Magento login page.
2. Enter an invalid username.
3. Enter an invalid password.
4. Click on the 'Login' button.

**Expected Result**:
- An error message should be displayed indicating invalid credentials.

**Actual Result**:
- No error message is displayed.

**Severity**: Medium

**Priority**: High

## Improvement Areas

This section highlights potential improvement areas identified during the testing process. These suggestions aim to enhance the user experience, performance, and overall quality of the Magento website.

### Example Improvement Area

**Area**: User Interface

**Description**:
The login page UI can be improved by providing clearer error messages and enhancing the visual design to make it more user-friendly.

**Suggestions**:
1. Implement more descriptive error messages for failed login attempts.
2. Enhance the visual design with better use of colors and layout for input fields and buttons.

---

This README provides a comprehensive overview of the manual testing project, including test cases, bug reports, and suggested improvement areas. It serves as a guide for understanding the testing efforts and findings related to the Magento website.
