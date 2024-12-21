# Selenium-Python-Example

This repository provides a foundational setup for a UI testing project utilizing Python, Selenium WebDriver, and the Page Object Model (POM) design pattern.

The example included demonstrates a simple DuckDuckGo search to verify that results are displayed correctly.

---

## Requirements

- **Python**: Version 3.12.3
- **pip**: Version 24.0 or newer, along with setuptools
- **Virtual Environment**: [venv](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) (recommended)

---

## Installation

1. Clone or download this repository.
2. Open a terminal.
3. Navigate to the project’s root directory: `/selenium-python-example/`.
4. Create a virtual environment using the command:  
   ```bash
   py -m venv venv
   ```
5. Activate the virtual environment:  
   ```bash
   .\venv\Scripts\activate
   ```
6. Install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```

---

## Running Tests

1. Open a terminal.
2. From the root directory of the project, execute:  
   ```bash
   pytest -v --html=results/report.html
   ```

---

## Configuration

- Tests are set to run on Chrome in normal mode by default.  
- To modify preferences, update the configuration file located at: `/data/config.yaml`.

---

## Viewing Results

After test execution, open the file `/results/report.html` to view the report.

---

## Resources

- [Selenium-Python Documentation](https://selenium-python.readthedocs.io/)  
- [WebDriver Manager for Python](https://github.com/SergeyPirogov/webdriver_manager)  
