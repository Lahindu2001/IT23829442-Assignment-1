# IT23829442 - Assignment 1 (Option 1)

## Student Information
- **Name:** Dharmasiri A.W.L.I  
- **Registration Number:** IT23829442  
- **Module:** IT3040 – ITPM (Semester 1)  
- **Assignment:** Transliteration Accuracy Testing (Option 1)  

---

## Project Overview

This repository contains the automated testing solution for evaluating the **Chat Sinhala Transliteration** functionality of the web application available at:

🔗 https://www.pixelssuite.com/chat-translator

The project identifies **50 negative test cases** (scenarios where the system fails or produces incorrect output) covering all **24 Singlish input types** specified in the assignment.

---

## Features

✅ Automated testing using **Playwright**  
✅ Excel-based test case management  
✅ Automatic result recording (**Actual Output & Status**)  
✅ Supports **50 failing test cases** covering all required Singlish input types  

---

## Folder Structure

```bash
IT23829442/
│
├── test_automation/
│   ├── test_automation.py
│   └── IT23829442_Assignment_1_Test_Cases.xlsx
│
└── README.md
```

---

## Prerequisites

Before running the project, make sure you have:

- Python 3.11 or 3.12
- Google Chrome Browser
- Internet Connection

---

## Installation Steps

### 1. Clone the Repository

```bash
git clone https://github.com/Lahindu2001/IT23829442-Assignment-1.git
```

### 2. Navigate to Project Folder

```bash
cd IT23829442/test_automation
```

### 3. Install Dependencies

```bash
pip install playwright openpyxl
playwright install
```

---

## Run the Automation

Execute the following command:

```bash
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200
```

---

## Test Cases Summary

| Item | Details |
|------|---------|
| Total Test Cases | 50 |
| Test Type | Negative Testing |
| Naming Format | Neg_xxxx |
| Coverage | All 24 Singlish Input Types |
| Input Length | S, M, L |

---

## Submission Files

The repository contains:

- Completed Excel file with Actual Output, Status, and analysis columns
- Full Playwright automation project
- Public GitHub repository

---

## Submission Information

**University:** SLIIT – BSc (Hons) in Information Technology  
**Submission Date:** May 2026  

---

## Repository Link

🔗 https://github.com/Lahindu2001/IT23829442-Assignment-1

---

## Author

**Dharmasiri A.W.L.I**  
IT23829442
