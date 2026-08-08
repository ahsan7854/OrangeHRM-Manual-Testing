# Leave Module – Requirements

## 1. Module Overview

The Leave module allows authorized users to manage employee leave
requests, leave balances, leave types, and leave-related information.

## 2. Objective

The objective of testing the Leave module is to verify that users can
correctly apply for, view, approve, reject, cancel, and manage leave
requests according to their permissions and business rules.

## 3. Functional Requirements

### FR-LEAVE-001 – Leave Navigation

The system shall allow authorized users to open the Leave module.

### FR-LEAVE-002 – Leave List

The system shall display available leave records to authorized users.

### FR-LEAVE-003 – Apply Leave

The system shall allow eligible employees to submit a leave request.

### FR-LEAVE-004 – Leave Type

The system shall allow users to select an available leave type.

### FR-LEAVE-005 – Leave Dates

The system shall allow users to select a valid leave period.

### FR-LEAVE-006 – Leave Balance

The system shall display or validate the employee's available leave balance
where applicable.

### FR-LEAVE-007 – Leave Reason

The system shall allow users to provide a reason or comment for a leave
request where applicable.

### FR-LEAVE-008 – Submit Leave

The system shall allow users to submit valid leave requests.

### FR-LEAVE-009 – Leave Validation

The system shall validate required fields and invalid leave information.

### FR-LEAVE-010 – View Leave Request

Authorized users shall be able to view leave request details.

### FR-LEAVE-011 – Approve Leave

Users with appropriate permissions shall be able to approve leave requests.

### FR-LEAVE-012 – Reject Leave

Users with appropriate permissions shall be able to reject leave requests.

### FR-LEAVE-013 – Cancel Leave

Users shall be able to cancel eligible leave requests.

### FR-LEAVE-014 – Search Leave

Users shall be able to search/filter leave records using available criteria.

### FR-LEAVE-015 – Leave Status

The system shall display the appropriate status of a leave request.

### FR-LEAVE-016 – Authorization

Only authorized users shall be able to approve, reject, or perform
restricted leave operations.

## 4. Non-Functional Requirements

### NFR-LEAVE-001 – Usability

The Leave module should be easy to understand and navigate.

### NFR-LEAVE-002 – Performance

Leave searches and operations should respond within an acceptable time.

### NFR-LEAVE-003 – Security

Leave information should only be accessible to authorized users.

### NFR-LEAVE-004 – Compatibility

The Leave module should work correctly on supported browsers.

### NFR-LEAVE-005 – Reliability

Leave requests and status changes should be saved correctly without
unexpected errors.

## 5. Testing Scope

Testing will cover:

- Functional Testing
- Positive Testing
- Negative Testing
- Validation Testing
- UI Testing
- Workflow Testing
- Authorization Testing
- Security Testing
- Compatibility Testing
- Performance Testing
- Exploratory Testing
- Regression Testing
- Smoke Testing
- Sanity Testing

## 6. Out of Scope

Third-party integrations and functionality outside the Leave module are
outside the primary scope unless required for integration or system testing.