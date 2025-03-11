Python API Automation Framework

Tech Stack
- Python 3.12
- Requests - HTTPS Request
- PyTest - Testing Framework
- Reporting - Allure Reports, PyTest HTML
- Test Data - CSV, Excel, JSON, Faker
- Advance API Testcase - JSONSchema
- Parallel Execution - x distribute (xdist)

How to Install Packages?
```
pip install requests pytest pytest-html faker allure-pytest jsonschema
```

How to run Testcase Parallel
```
pip install pytest=xdist
```

How to run the Basic Testcase with Allure Report
```
pytest tests/tests/crud/test_create_booking.py --alluredir=allure_result -s -v
```