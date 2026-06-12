


i need to create an git repo with this so can you guide me in depth with clear path
the repo plan:"Repo 1: manual-testing-portfolio

A README explaining what it contains
Test cases written in Excel/Google Sheets format (upload as .xlsx or .md tables)
Bug reports with proper format
Test a real website like OrangeHRM demo or OpenCart demo (free test environments)"

This is actually one of the best beginner QA portfolio projects because recruiters can open the GitHub repo and immediately see your testing skills.

Goal
Create a GitHub repository called:

manual-testing-portfolio
that contains:

manual-testing-portfolio/
│
├── README.md
│
├── Test-Cases/
│   ├── OrangeHRM-TestCases.xlsx
│   └── OrangeHRM-TestCases.md
│
├── Bug-Reports/
│   ├── Bug-001-Login-Error.md
│   ├── Bug-002-Search-Issue.md
│   └── Bug-003-UI-Issue.md
│
├── Test-Execution-Reports/
│   └── OrangeHRM-Execution-Report.xlsx
│
├── Screenshots/
│   ├── LoginPage.png
│   ├── Dashboard.png
│   └── BugEvidence.png
│
└── Documents/
    └── Test-Plan.md
STEP 1 — Create GitHub Account
If you don't already have one:

Go to:

GitHub

Create account

Verify email

Complete profile

Add:

Profile picture

Short bio

Example:

Aspiring QA Tester
Learning Manual Testing, API Testing, and Automation Testing
STEP 2 — Create Repository
Click:

New Repository
Repository Name:

manual-testing-portfolio
Description:

A portfolio showcasing manual testing skills including test cases, bug reports, and test execution reports.
Make it:

Public
Check:

✔ Add README
Click:

Create Repository
STEP 3 — Choose Website to Test
Use:

Option 1 (Recommended)
OrangeHRM Demo

Login:

Username: Admin
Password: admin123
Option 2
OpenCart Demo

I recommend OrangeHRM because:

Login

Logout

Search

Employee Management

Admin Module

Many features = More Test Cases

STEP 4 — Create Test Plan
Create:

Documents/Test-Plan.md
Example:

# Test Plan

## Project
OrangeHRM Demo Testing

## Objective
Verify major functionalities of OrangeHRM application.

## Scope
- Login
- Logout
- Dashboard
- Search
- Employee Management

## Testing Type
- Functional Testing
- UI Testing
- Positive Testing
- Negative Testing

## Environment
Browser: Chrome
OS: Windows 11

## Deliverables
- Test Cases
- Bug Reports
- Execution Report
STEP 5 — Write Test Cases
Create:

Test-Cases/OrangeHRM-TestCases.md
Format:

TC ID	Module	Test Scenario	Steps	Expected Result
TC001	Login	Valid Login	Enter valid username/password	Dashboard displayed
TC002	Login	Invalid Password	Enter wrong password	Error message shown
TC003	Login	Empty Username	Leave username blank	Validation message
TC004	Login	Empty Password	Leave password blank	Validation message
Target
Write:

20-30 test cases
Minimum:

20
Ideal:

30+
STEP 6 — Test Login Module
Create test cases for:

Positive Cases
Valid Login
Valid Logout
Negative Cases
Wrong Username
Wrong Password
Empty Username
Empty Password
Special Characters
SQL Injection Attempt
Example:

Username: Admin' OR '1'='1
Expected:

Login should fail
STEP 7 — Test Dashboard
Examples:

Verify Dashboard Loads
Verify Sidebar Visible
Verify User Profile Visible
Verify Navigation Menu Working
STEP 8 — Test Search Functionality
Examples:

Search Existing Employee
Search Non-existing Employee
Search Empty Value
Search Special Characters
STEP 9 — Execute Test Cases
Create Excel:

OrangeHRM-Execution-Report.xlsx
Columns:

TC ID	Result	Status
TC001	Login successful	Pass
TC002	Error displayed	Pass
TC003	Validation shown	Pass
STEP 10 — Find Bugs
You may find:

UI Bugs
Alignment issues
Spacing issues
Broken icons
Functional Bugs
Unexpected behavior
Validation missing
Usability Bugs
Confusing message
Poor navigation
STEP 11 — Create Professional Bug Reports
Folder:

Bug-Reports
Example:

# Bug ID: BUG-001

## Title
Login button remains enabled with empty fields

## Severity
Medium

## Priority
High

## Environment
Chrome Version 136

## Steps To Reproduce
1. Open Login Page
2. Leave Username Empty
3. Leave Password Empty

## Expected Result
Button should remain disabled

## Actual Result
Button remains enabled

## Status
Open
STEP 12 — Take Screenshots
Create:

Screenshots/
Capture:

Login Page
Dashboard
Search Page
Bug Evidence
Recruiters love screenshots.

STEP 13 — Create Professional README
This is the most important file.

Create:

README.md
Structure:

# Manual Testing Portfolio

## Project Overview

This repository demonstrates my Manual Testing skills through real-world testing of OrangeHRM Demo Application.

## Scope

- Login Testing
- Dashboard Testing
- Search Testing
- Employee Module Testing

## Testing Artifacts

### Test Cases
30+ test cases covering positive and negative scenarios.

### Bug Reports
Documented defects with severity and priority.

### Test Execution Report
Pass/Fail results for executed test cases.

## Tools Used

- Chrome Browser
- Microsoft Excel
- GitHub

## Skills Demonstrated

- Test Case Design
- Defect Reporting
- Functional Testing
- UI Testing
- Regression Testing

## Author

Sonu S S
STEP 14 — Push Everything to GitHub
Install Git:

Git Download Page

Commands:

git init

git add .

git commit -m "Initial QA Portfolio"

git branch -M main

git remote add origin https://github.com/USERNAME/manual-testing-portfolio.git

git push -u origin main
Final Recruiter-Ready Checklist
Before sharing the repo:

Item	Target
README	Complete
Test Cases	25-30
Bug Reports	5-10
Screenshots	5+
Test Plan	Added
Execution Report	Added
GitHub Public	Yes
After this repo is complete, your next portfolio repo should be:

qa-api-testing-portfolio
using Postman collections, API test cases, and API bug reports. Having both repositories gives you a much stronger profile for QA Internship and Junior QA Tester roles.


Repo 2: api-testing-postman

Export your Postman collections as JSON and upload
Write a README explaining what APIs you tested and what you verified
Use ReqRes.in or the OrangeHRM API

Repo 3: playwright-automation

3–5 simple test scripts
Login test, form validation test, navigation test
README explaining how to run them

These 3 repositories together form a very solid QA Portfolio for internships and entry-level QA roles.

Portfolio Roadmap
Repository	Skill Demonstrated
manual-testing-portfolio	Manual Testing
api-testing-postman	API Testing
playwright-automation	Test Automation
(Optional Later) qa-interview-notes	QA Knowledge
(Optional Later) bug-reporting-samples	Defect Management
Repo 2: api-testing-postman
Repository Name:

api-testing-postman
Objective
Show recruiters that you can:

Work with APIs

Use Postman

Validate responses

Verify status codes

Write API test cases

Perform CRUD testing

Recommended API
Option 1 (Easiest)
ReqRes API

Option 2 (Advanced)
OrangeHRM Demo API Documentation

Start with ReqRes.

Repository Structure
api-testing-postman/
│
├── README.md
│
├── Collections/
│   └── ReqRes_API_Collection.json
│
├── Environment/
│   └── ReqRes_Environment.json
│
├── Test-Cases/
│   └── API-TestCases.xlsx
│
├── Test-Results/
│   └── Newman-Report.html
│
└── Screenshots/
    ├── GET-Users.png
    ├── POST-User.png
    └── DELETE-User.png
APIs to Test
GET Users
GET /api/users?page=2
Verify:

Status code = 200

Response time acceptable

User list returned

GET Single User
GET /api/users/2
Verify:

Correct user details

Status 200

GET Invalid User
GET /api/users/999
Verify:

Status 404

POST Create User
POST /api/users
Body:

{
  "name": "Sonu",
  "job": "QA Tester"
}
Verify:

Status 201

ID generated

PUT Update User
PUT /api/users/2
Verify:

Updated response returned

DELETE User
DELETE /api/users/2
Verify:

Status 204

Create Postman Tests
Example:

pm.test("Status Code is 200", function () {
    pm.response.to.have.status(200);
});
pm.test("Response Time Less Than 1000ms", function () {
    pm.expect(pm.response.responseTime).to.be.below(1000);
});
Export Collection
Postman →

Collection
→ Export
→ Collection v2.1
Save:

ReqRes_API_Collection.json
Upload to GitHub.

README Example
Sections:

# API Testing Portfolio

## Overview

This repository contains API testing performed using Postman.

## APIs Tested

- GET Users
- GET User
- POST User
- PUT User
- DELETE User

## Validations

- Status Codes
- Response Body
- Response Time
- Schema Validation

## Tools

- Postman
- Newman
- GitHub

## Skills Demonstrated

- API Testing
- REST API Validation
- Test Case Design
- Automation with Postman Scripts
Repo 3: playwright-automation
Repository Name:

playwright-automation
Objective
Show recruiters:

"I can automate web applications."
This is huge because many QA jobs ask:

Manual + Automation
Technology
Use:

Playwright Official Website

Language:

JavaScript
(JavaScript is easiest for beginners.)

Installation
Install Node.js:

Node.js Downloads

Verify:

node -v
npm -v
Create Project
mkdir playwright-automation

cd playwright-automation

npm init -y

npm init playwright@latest
Choose:

JavaScript
Yes
Chrome
Repository Structure
playwright-automation/
│
├── README.md
│
├── tests/
│   ├── login.spec.js
│   ├── logout.spec.js
│   ├── navigation.spec.js
│   ├── search.spec.js
│   └── validation.spec.js
│
├── screenshots/
│
└── package.json
Script 1: Login Test
import { test, expect } from '@playwright/test';

test('Valid Login', async ({ page }) => {
  await page.goto('https://opensource-demo.orangehrmlive.com');

  await page.fill('input[name="username"]', 'Admin');
  await page.fill('input[name="password"]', 'admin123');

  await page.click('button[type="submit"]');

  await expect(page).toHaveURL(/dashboard/);
});
Script 2: Invalid Login
test('Invalid Login', async ({ page }) => {

  await page.goto('https://opensource-demo.orangehrmlive.com');

  await page.fill('input[name="username"]', 'wrong');
  await page.fill('input[name="password"]', 'wrong');

  await page.click('button[type="submit"]');

  await expect(page.locator('.oxd-alert-content')).toBeVisible();

});
Script 3: Navigation Test
Verify:

Dashboard
PIM
Admin
Leave
Open correctly.

Script 4: Form Validation
Verify:

Username empty
Password empty
Error messages appear
Script 5: Logout Test
Verify:

Profile Menu
Logout
Login Page displayed
Running Tests
npx playwright test
Run specific test:

npx playwright test login.spec.js
Generate Report
npx playwright show-report
Add screenshots of:

Passed tests

Report dashboard

Test execution

README Structure
# Playwright Automation Portfolio

## Overview

Automation framework built using Playwright and JavaScript.

## Application Tested

OrangeHRM Demo

## Automated Scenarios

- Login
- Logout
- Navigation
- Validation

## Tools

- Playwright
- JavaScript
- Node.js
- GitHub

## Run Tests

npx playwright test

## Generate Report

npx playwright show-report
What Recruiters Will See
After completing these 3 repositories:

manual-testing-portfolio

Test cases

Bug reports

Execution reports

api-testing-postman

API testing

Postman collections

REST validation

playwright-automation

Automation framework

Real test scripts

Reporting

This combination is enough to make your GitHub profile look like someone who has practical QA experience rather than someone who has only watched tutorials.


