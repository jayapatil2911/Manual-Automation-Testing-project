# OrangeHRM Manual & Automation Testing Project

## 📌 Project Overview

This project demonstrates **Manual Testing and Automation Testing** of the OrangeHRM web application.

The project includes test planning, test case design, test execution, defect reporting, requirement traceability, and Selenium automation using Java and TestNG.

## 🎯 Testing Scope

The following modules are covered:

* Login
* Dashboard
* PIM (Personnel Information Management)
* Leave
* Admin

## 🧪 Manual Testing

Manual testing activities include:

* Requirement analysis
* Test scenario preparation
* Test case preparation
* Test data preparation
* Functional testing
* Smoke testing
* Regression testing
* UI testing
* Test execution
* Defect identification
* Bug reporting
* Requirement Traceability Matrix (RTM)
* Test summary

### 📄 Manual Testing Documents

| Document     | Description                                              |
| ------------ | -------------------------------------------------------- |                       |
| Test Plan    | Testing scope, approach, environment, risks and schedule |
| Test Cases   | Functional and negative test cases                       |
| RTM          | Requirement-to-test-case mapping                         |
| Bug Reports  | Defects identified during testing                        |
| Test Summary | Overall test execution results                           |

## 🤖 Automation Testing

Automation testing is implemented using:

* **Java**
* **Selenium WebDriver**
* **TestNG**
* **Maven**
* **Page Object Model (POM)**
* **Apache POI**
* **Excel**
* **Git**
* **GitHub**

## 🔧 Automation Modules

### Login

* Valid username and password
* Invalid username
* Invalid password
* Blank username
* Blank password
* Invalid login combinations

### PIM

* Add Employee
* Search Employee
* Edit Employee
* Employee validation

### Leave

* Apply Leave
* Select Leave Type
* Select From Date
* Select To Date
* Submit Leave Request

### Admin

* Search User
* Add User
* User Role validation
* Status validation
* Username validation

## 📂 Project Structure

```text
OrangeHRM
│
├── Manual-Testing
│   ├── BRS
│   ├── SRS
│   ├── Test-Plan
│   ├── Test-Cases
│   ├── RTM
│   └── Bug-Reports
│
├── Automation-Testing
│   ├── src
│   │   ├── main
│   │   │   └── java
│   │   │       ├── base
│   │   │       └── pages
│   │   │
│   │   └── test
│   │       └── java
│   │           └── testcases
│   │
│   ├── test-data
│   │   └── OrangeHRMData.xlsx
│   │
│   ├── pom.xml
│   └── testng.xml
│
├── Screenshots
│
└── README.md
```

## 📊 Test Data

Excel files are used for data-driven testing.

Example:

```text
OrangeHRMData.xlsx
```

Test data includes login and module-specific test data used during automation.

## ▶️ How to Run Automation

### Prerequisites

* Java JDK installed
* Eclipse IDE
* Maven
* Chrome browser
* Selenium WebDriver
* TestNG

### Using Maven

Open the project in Eclipse or a terminal and run:

```bash
mvn clean test
```

### Using TestNG

Right-click:

```text
testng.xml
```

and select:

```text
Run As → TestNG Suite
```

## 📋 Test Execution

Automation execution results are generated through TestNG.

The test suite verifies the expected behavior of the OrangeHRM application and reports passed and failed test cases.

## 🐞 Defect Reporting

Defects identified during manual testing are documented with:

* Bug ID
* Module
* Test Case ID
* Bug Title
* Preconditions
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Status

## 🛠️ Skills Demonstrated

* Manual Testing
* Functional Testing
* Smoke Testing
* Regression Testing
* Test Case Design
* Bug Reporting
* RTM
* Selenium WebDriver
* Core Java
* TestNG
* Maven
* Page Object Model
* Data-Driven Testing
* Excel Data Handling
* Git
* GitHub

## 👩‍💻 Author

**Jaya Patil**

Software Testing / QA

## 🔗 GitHub Repository

This project is part of the:

**Manual-Automation-Testing-project**

repository.
