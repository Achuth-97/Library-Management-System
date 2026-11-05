# Library Management System - Test Cases

## 1. Introduction

This document contains test cases designed to verify the functionality of the Library Management System. The purpose is to ensure that the system works correctly and meets the expected requirements.

## 2. Test Cases

### TC_01: User Login

- **Test Scenario:** Verify login with valid credentials.
- **Test Input:** Valid username and password.
- **Expected Result:** User should successfully log in.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_02: Invalid Login

- **Test Scenario:** Verify login with incorrect credentials.
- **Test Input:** Invalid username or password.
- **Expected Result:** System should display an error message.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_03: Add New Book

- **Test Scenario:** Verify adding a new book.
- **Test Input:** Valid book name, author, and book ID.
- **Expected Result:** Book should be added successfully.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_04: Search Book

- **Test Scenario:** Search for an existing book.
- **Test Input:** Valid book name or book ID.
- **Expected Result:** Matching book details should be displayed.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_05: Search Non-Existing Book

- **Test Scenario:** Search for a book that is not available.
- **Test Input:** Invalid or unavailable book name.
- **Expected Result:** System should display a book not found message.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_06: Issue Book

- **Test Scenario:** Verify issuing an available book.
- **Test Input:** Valid student ID and available book ID.
- **Expected Result:** Book should be issued successfully.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_07: Return Book

- **Test Scenario:** Verify returning an issued book.
- **Test Input:** Valid issued book ID.
- **Expected Result:** Book should be returned and availability updated.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_08: Calculate Fine

- **Test Scenario:** Verify fine calculation for a late book return.
- **Test Input:** Book returned after the due date.
- **Expected Result:** Fine should be calculated according to the library's fine rules.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_09: Delete Book

- **Test Scenario:** Verify deleting an existing book.
- **Test Input:** Valid book ID.
- **Expected Result:** Book should be removed from the system.
- **Actual Result:** Not tested.
- **Status:** Not Run.

### TC_10: View Book Details

- **Test Scenario:** Verify viewing book information.
- **Test Input:** Existing book ID.
- **Expected Result:** Book name, author, and availability should be displayed.
- **Actual Result:** Not tested.
- **Status:** Not Run.

## 3. Conclusion

The above test cases are designed to verify the major functionalities of the Library Management System. Testing helps identify errors and ensures that the system performs according to the specified requirements.
