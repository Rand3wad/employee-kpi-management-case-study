# Employee Performance & KPI Management Platform — Case Study

> Sanitized portfolio case study based on a real internal system developed during my Software Engineering Co-op. Internal data, credentials, organization-specific rules, and proprietary source code are intentionally excluded.

## Overview

This project digitized an employee achievement and KPI workflow involving employees, managers, approvals, weighted scores, comments, assignments, and performance-related reporting.

## Problem

The existing process required a more structured way to:

- Submit employee achievements
- Review requests consistently
- Approve or decline submissions
- Capture manager feedback
- Apply weighted scores
- Track request status
- Manage reusable task templates
- Assign work
- Support performance reporting

## Solution

The system introduced a role-based workflow:

```text
Employee Submission
        ↓
Manager Review
        ↓
Approve / Decline
        ↓
Comment / Weight
        ↓
Status Update
        ↓
Performance Reporting
```

## User Roles

### Employee

- View dashboard
- Submit achievements/tasks
- Choose an existing task or enter another
- Track pending, approved, and declined requests
- View manager feedback
- Manage profile information

### Manager

- Review employee submissions
- Approve and assign a weight
- Decline with comments
- Search and review employee records
- Manage task templates
- Assign tasks
- Configure KPI-related values
- Monitor performance-related information

## Technology

- PHP
- MySQL
- HTML
- CSS
- JavaScript
- PHPMailer

## My Role

I contributed across analysis, implementation, testing, and validation, including:

- Working with directors, managers, and employees to understand the existing process
- Clarifying business rules and approval logic
- Translating requirements into workflows and system functionality
- Contributing to database and workflow design
- Frontend and backend development
- Role-based access and validation logic
- Functional testing
- User validation / UAT
- Iterative improvements based on stakeholder feedback
- Technical and user documentation

## Business Rules

Examples of rules translated into system behavior included:

- Requests can be pending, approved, or declined
- Managers can provide comments on declined submissions
- Approved submissions contribute weighted values
- Reusable task templates can support consistent submission options
- Role permissions determine which actions and views are available

## Testing & UAT

Testing and validation included:

- Authentication and role behavior
- Submission workflows
- Approval and decline actions
- Weight handling
- Manager comments
- Permission checks
- Data validation
- Employee and manager views
- Retesting after stakeholder feedback

Users and managers participated in validation sessions, and changes were made based on observed needs and feedback.

## Security & Configuration

The original private implementation was later cleaned to remove hardcoded database and SMTP credentials from the latest code version. Runtime configuration is handled through environment variables.

## What This Project Demonstrates

This project demonstrates experience with:

- Requirements gathering
- Business-process analysis
- Systems analysis
- Role-based application design
- PHP/MySQL development
- Approval workflows
- UAT and stakeholder validation
- Data validation
- Technical documentation
- Translating business rules into software behavior

## Confidentiality

The original codebase remains private.

This public case study intentionally excludes:

- Real employee data
- Internal organizational structure
- Production credentials
- Internal email accounts
- Proprietary screenshots
- Sensitive business rules not appropriate for public sharing
