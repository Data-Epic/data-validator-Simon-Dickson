# data-validator-simon-dickson
simon-datavalidator is a Python package that uses Object-Oriented Programming (OOP) to validate various data types, including emails, phone numbers, dates, and URLs, using regular expressions. It also includes comprehensive unit tests to ensure accuracy and reliability.
---

## Features

- Validate **email addresses** with robust pattern matching.
- Validate **phone numbers** supporting international formats.
- Validate **dates** in formats `YYYY-MM-DD` and `YYYY/MM/DD`.
- Validate **URLs** for both HTTP and FTP protocols.
- Comprehensive **unit testing** with `pytest`.

---

## Project Structure

### File Breakdown

#### `validator.py`
Defines the `DataValidator` class with the following methods:
- `validate_email()`: Validates email addresses using a regular expression.
- `validate_phone()`: Validates phone numbers with support for international formats.
- `validate_date()`: Validates date strings in both `YYYY-MM-DD` and `YYYY/MM/DD` formats.
- `validate_url()`: Validates URLs supporting both HTTP and FTP protocols.

#### `test_validator.py`
Contains unit tests for each validation method using **pytest**. The tests cover:
- Valid and invalid email addresses.
- Valid and invalid phone numbers.
- Valid and invalid date formats.
- Valid and invalid URLs.

#### `setup.py`
Handles the package setup and metadata, including author information and version.

---

## Prerequisites

Ensure you have Python **3.7 or later** installed.

### Install Dependencies

No external libraries are required, as the project only uses Python’s built-in modules.

To install `pytest` for testing, run:
```bash
pip install pytest
```
## Cloning the Project

To get started, clone the repository:

```bash
git clone https://github.com/Data-Epic/data-validator-simon-dickson.git
```
---

## Running Tests with Pytest

This project includes unit tests to validate its functionality. To run the tests, execute:
```bash
pytest -v
```

---

## Installation

To install the package locally, run:
```bash
pip install simon-datavalidator
```

---

## Author

Name: Simon Dickson
Email: simonoche987@gmail.com# data-validator-Simon-Dickson
