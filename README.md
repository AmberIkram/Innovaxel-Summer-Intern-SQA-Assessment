# Innovaxel SQA Assessment

This repository contains my submission for the Innovaxel Summer Internship (SQA) assessment. The project includes manual testing artifacts for a selected mobile application, including test cases, bug reports, screenshots, and a test summary report.
# Microsoft To Do — SQA Take-Home Assessment

This repository contains the manual QA testing artifacts for the **Innovaxel SQA Summer Intern Assessment**, performed on the **Microsoft To Do** mobile application.

## 📱 App Under Test
**App Name:** Microsoft To Do
**Platform:** [Android]
**Device Used:** [redmi]
**App Version:* [2.169.1015.00 build #399]

## 📂 Repository Contents

| File | Description |
|---|---|
| `Microsoft_ToDo_TestCases.xlsx` | Full test suite (25 test cases) covering core workflows — task creation, editing, deletion, lists, search, reminders, navigation, and edge cases |
| `Microsoft_ToDo_BugReport.xlsx` | Documented bugs/usability issues found during manual testing, with severity ratings and a summary dashboard |
| `Test_Summary_Report.pdf` | 1-page summary covering what was tested, key findings, usability feedback, and improvement suggestions |
| `screenshots/` | Screenshot evidence for each reported bug |

## 🧪 Testing Scope

The following core workflows were tested:
- Sign-in / authentication
- Task creation, editing, and deletion
- Due dates and reminders
- List creation and management
- Search functionality
- Sub-steps within tasks
- Dark mode and offline behavior

## 🐛 Bugs Found

| Bug ID | Title | Severity |
|---|---|---|
| BUG-001 | App freezes briefly on cold start | High |
| BUG-003 | Due date picker does not block past dates | Medium |
| BUG-005 | Very long task title overflows UI | Medium |
| BUG-006 | Reminder notification not fired when app is force-closed | High |
| BUG-008 | Completed task counter shows wrong count after undo | Medium |

> See `Microsoft_ToDo_BugReport.xlsx` for full steps to reproduce, expected vs actual results, and screenshot references.

## 🖼️ Screenshot Evidence

Screenshots for each reproducible bug are stored in the `/screenshots` folder, named by Bug ID:
