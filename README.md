# Sentinel_Project_BW

**Automated Testing Framework using Selenium**

## 🚀 Project Overview

This project focuses on building and running automated **UI test cases using Selenium**.
It is designed for beginners learning test automation — covering browser setup, test scripts, element locators, assertions, and basic framework structure.

The main objective is to test the **data integrity and UI flow** of a sample SaaS dashboard (Sentinel).

---

## 🧩 Key Features

* Automates web-based functional test cases
* Uses Selenium WebDriver for browser interactions
* Implements Page Object Model (POM) structure for better maintainability
* Supports multiple browsers (Chrome, Edge, Firefox)
* Validates core user journeys (login, dashboard view, data validation)
* Includes simple reporting (console or HTML report)
* Easy to extend with new test cases

---

## 🎯 Technologies Used

* **Language:** Java 
* **Testing Framework:** TestNG 
* **Automation Tool:** Selenium WebDriver
* **Build Tool:** Maven / Gradle (Java) 
* **IDE:**STS
* **Browser Drivers:** ChromeDriver

---

## 📁 Repository Structure

```
Sentinel_Project_BW/
│
├── src/
│   ├── test/
│   │   ├── java/ (or python/)
│   │   │   ├── pages/         # Page Object classes
│   │   │   ├── tests/         # Test scripts
│   │   │   ├── utils/         # Utility functions
│   │   │   └── BaseTest.java  # Setup & teardown
│
├── reports/                   # Test reports
├── drivers/                   # Browser drivers
├── pom.xml / requirements.txt # Dependencies
└── README.md
```

---


---

## ✅ Example Test Case

**Login Test:**

* Open browser and navigate to the dashboard login page
* Enter valid credentials
* Verify that the user is redirected to the dashboard
* Validate the page title and visible data

---

## 📊 Future Enhancements

* Add CI/CD integration (GitHub Actions / Jenkins)
* Implement data-driven testing using Excel / CSV
* Add screenshot capture for failed tests
* Integrate Allure or Extent Reports for better visuals

---



