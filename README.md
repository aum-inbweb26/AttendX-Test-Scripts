# AttendX — Student Attendance App Automation Suite

[![Quality Assurance](https://img.shields.io/badge/QA-Selenium%20WebDriver-green.svg)](#)
[![Version Control](https://img.shields.io/badge/VCS-Git%20%26%20GitHub-blue.svg)](#)

## 📌 Project Overview
**AttendX** is a cloud-based student attendance tracking portal used by university faculty and administrators. This repository centralizes all automated QA regression test scripts under Git version control to prevent file overwrite conflicts, maintain audit histories, and allow collaborative test development across QA engineers.

---

## 📂 Repository Contents
- **`test_login.py`**: Automated test suite for user authentication, role-based login validation, and blank input error handling.
- **`test_attendance.py`**: Automated test suite for single student attendance marking, bulk "Mark All Present" features, and database submission persistence.
- **`README.md`**: Project setup instructions, execution steps, and version control guidelines.

---

## 🚀 Setup & Execution Instructions

### Prerequisites
1. Python 3.10+ installed
2. Selenium WebDriver (`pip install selenium`)
3. Google Chrome & Chromedriver installed

### Running the Test Suites
Run individual test suites via Python's built-in `unittest` runner:

```bash
# Run Login Test Suite
python -m unittest test_login.py

# Run Attendance Test Suite
python -m unittest test_attendance.py
```

---

## 👥 QA Team Workflow & Collaboration Rules
1. **Never share test scripts via Email or USB drives.**
2. Always pull latest remote changes before beginning local test authoring:
   ```bash
   git pull origin main
   ```
3. Commit with semantic, meaningful commit messages.
4. Push all tested changes to GitHub for review:
   ```bash
   git push origin main
   ```
