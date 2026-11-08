# CredCart – Selenium Python Pytest Automation Framework

## Project Overview

This project is an automation testing framework developed for the login module of the CredCart e-commerce web application using Python, Selenium WebDriver and Pytest.

The framework follows a structured project architecture with Page Object Model (POM), reusable utilities, configuration management, Excel-based test data handling, logging and HTML reporting.

## Technologies Used

- Python
- Selenium WebDriver
- Pytest
- pytest-html
- Oracle SQL (separate technical skill)
- Microsoft Excel

## Project Structure

```text
Project/
├── Configurations/
│   └── config.ini
├── Logs/
│   └── log_file.log
├── Reports/
│   └── report.html
├── Screenshots/
├── TestData/
│   └── test_data.xlsx
├── pageObjects/
│   └── LoginPage.py
├── testCases/
│   ├── conftest.py
│   └── test_Login.py
├── utilities/
│   ├── Logger.py
│   ├── ReadProperties.py
│   └── XLUtils.py
└── pytest.ini
```

## Testing Scope

The current project focuses on Login Module Automation.

### Automated Test Scenarios

1. Login with valid username and password.
2. Login with invalid username and password.
3. Login with invalid username and valid password.
4. Login with valid username and invalid password.
5. Login button functionality.

## Framework Features

- Page Object Model (POM)
- Pytest fixtures
- Shared fixtures using conftest.py
- Pytest configuration using pytest.ini
- Test organization using Pytest markers
- Excel-based test data utilities
- Configuration management using INI files
- Logging utility
- HTML test reporting using pytest-html
- Organized screenshot storage

## Execution

Install dependencies:

```bash
pip install selenium pytest pytest-html openpyxl
```

Run tests:

```bash
pytest -v -s
```

Generate HTML report:

```bash
pytest -v -s --html=Reports/report.html --self-contained-html
```

## Test Execution Result

All implemented test cases passed during the reported execution.

No defects were identified within the tested login scenarios.

## Project Objective

To develop practical skills in Python-based automation testing, Selenium WebDriver, Pytest framework organization, reusable test components and structured test execution.
