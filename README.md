# 👨‍💻 Garala Ramakrishna — QA Testing Portfolio

🎓 B.Tech CSE | KPRIT Hyderabad | 2022–2026  
🔍 Aspiring Manual QA Engineer | Software Testing Intern  
📧 ramakrishna13808@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ramakrishna-garala-aa02a8262/)

---

## 🧪 About This Portfolio

This repository contains real-world manual QA work including
bug reports, test cases, and defect logs created during 
internship assignments and self-practice projects.

All bugs are documented with:
- ✅ Steps to Reproduce
- ✅ Expected vs Actual Results
- ✅ Severity & Priority Ratings
- ✅ Screenshots
- ✅ Logged in Jira

---

## 📁 Projects

---

### 1️⃣ HighScores QA Assignment
**Website Tested:** next.practiz.xyz  
**Organization:** HighScores.ai  
**Type:** Manual Exploratory + Functional Testing  
**Date:** March 2026  

#### 🔍 What I Tested
- Student Registration Flow
- Payment & Checkout
- Assessments / Test Taking
- Navigation & Sidebar Links
- Calendar UI
- Collaboration / Chat

#### 🐛 Bugs Found: 10 (9 Functional + 1 UI/UX)

| Bug ID | Title | Severity | Priority |
|--------|-------|----------|----------|
| BUG-001 | Date of Birth allows year 2024 – no age check | High | High |
| BUG-002 | Parent email accepted without verification | High | High |
| BUG-003 | Weak passwords accepted – no special char required | Medium | Medium |
| BUG-004 | HTML code showing as plain text in cart | High | High |
| BUG-005 ⭐ | Premium package purchased for $0.00 | **Critical** | High |
| BUG-006 | Continue Shopping button throws 404 error | Medium | Medium |
| BUG-007 | Question text invisible + graph image broken | High | High |
| BUG-008 | Calendar dates invisible in Month and Week view | Medium | Medium |
| BUG-009 | Chat shows 0 participants despite active users | Medium | Medium |
| BUG-010 | Code Editor, Resume, Marketplace all give 404 | High | High |

#### ⭐ Most Critical Finding
**BUG-005 — Payment Bypass:**  
Premium package worth $199 could be purchased for $0.00.  
Checkout completed with Payment Status = Confirmed  
and Amount Paid = $0.00. Direct revenue loss to business.

#### 📄 Full Bug Report
[View PDF Bug Report](./HighScores-QA/Bug-Report.pdf)

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Jira | Bug tracking & defect management |
| Google Chrome | Primary test browser |
| Browser DevTools | Inspecting elements & network |
| Postman | API Testing (basics) |
| GitHub | Portfolio documentation |

---

## 🎯 QA Skills

- Manual Testing
- Functional Testing
- Exploratory Testing  
- Regression Testing
- Negative Testing
- Bug Reporting & Documentation
- STLC & SDLC
- Equivalence Partitioning (EP)
- Boundary Value Analysis (BVA)
- Smoke & Sanity Testing
- API Testing (Postman – basics)

---

*This portfolio is actively updated as I complete
more QA projects and assignments.*
