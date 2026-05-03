# IT23829442 - Assignment 1 (Option 1)

## Student Information
- **Name:** Dharmasiri A.W.L.I
- **Registration Number:** IT23829442
- **Module:** IT3040 – ITPM (Semester 1)
- **Assignment:** Transliteration Accuracy Testing (Option 1)

---

## Project Overview

This repository contains the automated testing solution for evaluating the **Chat Sinhala Transliteration** functionality of the web application available at [https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator).

The project identifies **50 negative test cases** (scenarios where the system fails or produces incorrect output) covering all **24 Singlish input types** specified in the assignment.

---

## Features
- Automated testing using **Playwright**
- Excel-based test case management
- Automatic result recording (Actual Output & Status)
- Supports 50 failing test cases covering all required Singlish input types

---

## Folder Structure
T23829442/

├── test_automation/                              # Automation folder
  ├── test_automation.py                          # Main Playwright script
  └── IT23829442_Assignment_1_Test_Cases.xlsx     # Completed test cases with results


---

## How to Run the Automation

### Prerequisites
- Python 3.11 or 3.12
- Google Chrome browser

### Installation Steps

1. Open Command Prompt
2. Navigate to the project:
   ```cmd
   cd /d D:\test_automation

3.Install dependencies:
pip install playwright openpyxl
playwright install

Run the Tests
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200

Test Cases Summary

Total Test Cases: 50 (All Negative - "Neg_xxxx")
Coverage: All 24 Singlish input types (minimum 2 per type)
Input Length Types: S, M, and L


Submission Files

Completed Excel file with Actual Output, Status, and analysis columns (G & H)
Full Playwright automation project
Public GitHub repository


Submitted to: SLIT - BSc (Hons) in Information Technology
Date: May 2026

GitHub Repository: https://github.com/Lahindu2001/IT23829442-Assignment-1.git
