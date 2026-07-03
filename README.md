# Tichi App - QA Automation

## Assignment

QA Intern Technical Assignment for Tichi Application.

**App:** https://tichi-app-webapp-stage.web.app

---

## Tasks Completed

### Task 1: Test Case Creation
- **54 test cases** (Login: 23, Signup: 31)
- Coverage: I explore the website and test the functionalities of the Sign Up and Login modules. I had covered most of the happy, negative and edge cases.
- Document: `Katomaran_test_case.xlsx`

### Task 2: Defect Reporting
- **3 defects found and documented:**
  - DEF-001: Invalid email format accepted
  - DEF-002: Deleted account can be recreated
  - DEF-003: Password rules not enforced
- Document: `Defect_Report.pdf`

### Task 3: Automation (Completed)
- **11 automated test scripts** using Playwright + TypeScript
- Login tests, Signup tests, Defect validation
- Framework: Page Object Model (POM)

---

## How to Run Tests

```bash
npm install
npm install @playwright/test

# Run tests (single worker - stable)
npx playwright test --workers=1

# Run with browser visible
npx playwright test --headed

# View report
npx playwright show-report
```

---

## Test Results

- Total: 11 tests
- Pass: 8 ✅
- Fail: 3 ❌ (Intentional - defects documented)
- Duration: 2-3 minutes

---

## Deliverables

- ✅ Test Cases Document
- ✅ Defect Report
- ✅ Automation Source Code
- ✅ Execution Report

---

## Project Structure
