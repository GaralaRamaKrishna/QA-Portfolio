# Garala Ramakrishna — QA Portfolio

B.Tech CSE | KPRIET Hyderabad | 2022–2026
Aspiring QA Engineer | Open to Remote QA Internships

ramakrishna13808@gmail.com
linkedin.com/in/ramakrishna-garala-aa02a8262
github.com/GaralaRamaKrishna/selenium-qa-practice
garalaramakrishna.github.io

---

## About This Portfolio

This repository contains real-world manual QA work —
bug reports, test cases, API tests, and defect logs
from live platform testing and self-practice projects.

For automation work (Selenium, PyTest, SQL) see:
github.com/GaralaRamaKrishna/selenium-qa-practice

---

## Projects

---

### 1. Manual QA Testing — HighScores.ai

Platform: next.practiz.xyz
Date: January 2026
Tools: Chrome DevTools, Jira, GitHub

**What I tested:**
- Student registration flow
- Payment and checkout
- Assessments and test taking
- Navigation and sidebar links
- Calendar UI
- Collaboration and chat

**Bugs found: 10 (9 Functional + 1 UI/UX)**

| Bug ID | Title | Severity | Priority |
|--------|-------|----------|----------|
| BUG-001 | DOB allows year 2024 — no age check | High | High |
| BUG-002 | Parent email accepted without verification | High | High |
| BUG-003 | Weak passwords accepted | Medium | Medium |
| BUG-004 | HTML showing as plain text in cart | High | High |
| BUG-005 | CRITICAL — Premium package purchased for $0.00 | Critical | High |
| BUG-006 | Continue Shopping button throws 404 | Medium | Medium |
| BUG-007 | Question text invisible + graph broken | High | High |
| BUG-008 | Calendar dates invisible in both views | Medium | Medium |
| BUG-009 | Chat shows 0 participants | Medium | Medium |
| BUG-010 | Code Editor, Resume, Marketplace — all 404 | High | High |

**Most critical finding — BUG-005:**
Premium subscription worth $199 purchased for $0.00.
Checkout completed with Payment Status = Confirmed
and Amount Paid = $0.00. Direct revenue loss to business.

[Download Bug Report PDF](./BugReport_HighScores_RamakrishnaGarala.pdf)

---

### 2. REST API Testing — JSONPlaceholder

API: jsonplaceholder.typicode.com
Tool: Postman
Date: February 2026

| # | Method | Endpoint | Expected | Result |
|---|--------|----------|----------|--------|
| 1 | GET | /users | 200 OK | Pass |
| 2 | GET | /users/1 | 200 OK | Pass |
| 3 | GET | /users/999 | 404 Not Found | Pass |
| 4 | GET | /posts | 200 OK | Pass |
| 5 | POST | /users | 201 Created | Pass |

5/5 tests passed. pm.test() assertions added to all 5.

[Download Postman Collection](./JSONPLaceholder%20API%20Tests.postman_collection.json)

---

### 3. Manual QA Testing — SecondBrainLabs

Platform: app.secondbrainlabs.com
Tools: Chrome DevTools, Android Chrome
Date: February 2026

| Metric | Count |
|--------|-------|
| Test Cases Executed | 10 |
| Passed | 8 |
| Failed | 2 |
| Bugs Reported | 9 |

Testing focus: onboarding, input validation,
mobile responsiveness, workflow behavior.

Key bugs: phone field accepting invalid +91 format,
email verification not restricting platform access,
mobile UI overlap on Campaigns and Chats pages.

[Download QA Report PDF](./Ramakrishna_Garala_QA_Assignment_SecondBrainLabs.pdf)

---

### 4. Test Automation — Selenium + PyTest

Repo: github.com/GaralaRamaKrishna/selenium-qa-practice
Date: March 2026
Tools: Python 3.13, Selenium 4, PyTest 9.0

- 16 automation scripts — browser control, login forms,
  XPath (5 methods), POM, alert handling, screenshots
- 17 PyTest tests passing — fixtures, parametrize,
  class-based suite, HTML reports
- GitHub Actions CI configured

---

### 5. SQL Database Validation

Repo: github.com/GaralaRamaKrishna/selenium-qa-practice
Date: April 2026
Tools: Python, SQLite3, PyTest

- 5 SQL scripts covering full CRUD operations
- QA validation report detecting 8 database bugs
  including NULL fields, duplicate emails,
  and $0.00 payment bypass
- 7 PyTest database validation tests
- SQL connected directly into PyTest test suite

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Jira | Bug tracking and defect management |
| Postman | API testing |
| Selenium 4 | Browser automation |
| PyTest | Test framework |
| Python | Automation scripting |
| SQLite3 | Database validation |
| GitHub Actions | CI/CD pipeline |
| Chrome DevTools | Element inspection and network |
| Git/GitHub | Version control |

---

## Skills

Manual Testing: Functional, Regression, Smoke,
Sanity, Negative, Exploratory, Cross-Browser

Test Design: Test Plan Writing, Test Case Design,
BVA, Equivalence Partitioning

Automation: Selenium WebDriver, Page Object Model,
XPath, Explicit Wait, Screenshots on Failure

Framework: PyTest, Fixtures, Data Driven Testing,
HTML Reports, conftest.py

API Testing: Postman, REST API, GET/POST,
Status Code Validation, pm.test() assertions

Database: SQL, SQLite, CRUD, JOIN, GROUP BY,
NULL checks, Duplicate Detection

Concepts: STLC, SDLC, Agile, Bug Life Cycle,
Defect Tracking, Defect Reporting

Languages: Python, SQL, HTML/CSS

---

## Automation Repository

All Selenium, PyTest, and SQL scripts are in
a separate repo kept clean and well-documented:

github.com/GaralaRamaKrishna/selenium-qa-practice

---

*Updated April 2026 — actively maintained.*
