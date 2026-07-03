# Tichi App - QA Testing Assignment

## Assignment

QA Intern Technical Assignment for Tichi Web Application.

**Application:** https://tichi-app-webapp-stage.web.app

---

## Task 1: Manual Test Case Creation

- Created **56 Manual Test Cases**
- Test cases are written in seperate pages in the Excel sheet like: `Sign Up Test Cases` and `Login Test Cases`.
- Tested Login and Sign Up functionalities
- Covered form validation, input fields, navigation, error messages, password validation, browser behavior and different user scenarios.
- Document: `Katomaran_test_case.xlsx`

---

## Task 2: Defect Reporting

- Identified and documented **6 Defects**
- Included Test Case ID, Defect ID, Steps to Reproduce, Expected Result, Actual Result, Severity, Priority and Screenshot.
- Document: `Defect_Report.docx`

---

## Task 3: Automation Testing

- Automated 10 Test Cases using Playwright with TypeScript.
- Included Login, Sign Up and Defect Validation scenarios.
- 3 automation scripts were created to validate the reported defects.
- Source Code: `Katomaran_QA.zip`
- The Automation test scripts are seperated as:
     1. Login/
         |_Login page test files
     2. Sign Up/
         |_Sign up test files.

  
### Steps to Run the Test Scripts

1. Download and extract the `Katomaran_QA.zip` file.
2. Open the `Katomaran_QA` folder in Visual Studio Code or any IDE.
3. Open the terminal in the project folder.
4. Install the required packages:

```bash
npm install
npm install @playwright/test
npx playwright install
```


---


## Automation Execution Report
- Document:  `Automation_execution.report.zip`
- Verify the file for automation test report which covers the passed and failed tests.
- Download the zip file and click the index.html for the execution report.

## How to Run the automation script

```bash
npm install
npm install @playwright/test
choose the required options.

# Run all tests(//cross browser testing)
npx playwright test --workers=1

# Run with browser visible
 1. Go to the playwright.config.ts
 2. Change: use: {
    headless: false,
    trace: 'on-first-retry',
  },

# View HTML Report
npx playwright show-report
```


---


## Project Structure
```
Project
│
├── Katomaran_test_case.xlsx
├── Defect_Report.docx
├── Katomaran_QA.zip
├── Automation_execution_report.zip
└── README.md
```


---


## Tools Used
- Playwright
- TypeScript
- Visual Studio Code
- Microsoft Excel
- Microsoft Word


---


## Author

**Balasurya G**
