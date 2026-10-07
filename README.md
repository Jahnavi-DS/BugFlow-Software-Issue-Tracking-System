# BugFlow – Intelligent Software Defect Tracking & Resolution Platform

BugFlow is a web-based software issue tracking and resolution platform designed to help development, testing, and project teams manage software defects throughout their complete lifecycle.

It provides centralized issue reporting, role-based access control, workflow management, duplicate detection, sprint planning, analytics, collaboration, reporting, and rule-based resolution assistance.

---

## 🚀 Key Features

### 🔐 Authentication & Role-Based Access Control
- Secure user registration and login
- JWT-based authentication
- Role-based authorization
- Supports:
  - ADMIN
  - DEVELOPER
  - TESTER
  - TRIAGER
  - STAKEHOLDER
- Role-specific dashboards and permissions

### 🐞 Issue Management
- Create and manage software issues
- Support different issue types
- Severity and priority classification
- Project and category management
- Issue assignment and reassignment
- Issue filtering and pagination
- Detailed issue information and reproduction steps

### 🔍 Duplicate Detection
- Detects potentially similar issues
- Uses similarity matching to identify duplicate reports
- Helps reduce repeated issue submissions

### 🔄 Issue Lifecycle Management

BugFlow follows a structured issue workflow:

```text
REPORTED
    ↓
TRIAGED
    ↓
IN_PROGRESS
    ↓
CODE_REVIEW
    ↓
QA_VERIFICATION
    ↓
RESOLVED
    ↓
CLOSED
