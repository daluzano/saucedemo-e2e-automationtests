# SauceDemo End2End AutomationTests
A Java-based Selenium automation framework for end-to-end testing of the SauceDemo e-commerce web application, using TestNG, Page Object Model, and Allure Reports with screenshot capture on failures.

# 🔧 Tech Stack 
- Language: Java 8+
- Automation Tool: Selenium WebDriver
- Test Framework: TestNG
- Build Tool: Maven
- Design Pattern: Page Object Model (POM)
- Test Data: TestNG DataProvider
- Reporting: Allure Report
- Browser: Google Chrome

# 🌍 Test Application
URL: https://www.saucedemo.com/

# ✅ Test Coverage
- Login with valid credentials
- Product selection and cart management
- Checkout process and order completion

# 📊 Reporting
This framework integrates **_Allure Report_** to provide:

- Pass / Fail status per test
- Step-by-step execution details
- Test severity, epic, and feature tags
- Automatic screenshot attachment on failure

## 📸 Sample Allure Screenshots

>**Allure Overview Report**

>**Project Suites**

# How to Run the Tests

1.- **Prerequisites**
- Java 8 or higher installed
- Maven installed
- Google Chrome installed
- Allure Commandline installed

2.- **Execute Tests**
```
mvn clean test
```
3.- **Generate and View Allure Report**
```
allure serve allure-results
```
> [!NOTE]
> This will open the Allure report in your default browser
