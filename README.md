<div align="center">

# 🧪 RESTful Product Catalog Service  
### Test-Driven & Behavior-Driven Development Project

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![TDD](https://img.shields.io/badge/TDD-Driven-red?style=for-the-badge) ![BDD](https://img.shields.io/badge/BDD-Validated-green?style=for-the-badge) ![Selenium](https://img.shields.io/badge/Selenium-Automated-43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![Coursera](https://img.shields.io/badge/Coursera-IBM-blue?style=for-the-badge&logo=coursera&logoColor=white)

</div>

---

## 📌 Overview

This project is a production-style RESTful Product Catalog API built using strict **Test-Driven Development (TDD)** and **Behavior-Driven Development (BDD)** practices.

It demonstrates how professional backend systems are developed:

- Tests written before implementation  
- API routes validated through automated test suites  
- End-to-end behavior verified with Selenium  
- Clean modular architecture  
- Full CRUD functionality with advanced filtering  

This repository represents disciplined engineering — not just code that works, but code that is **proven to work**.

---

## 🚀 Core Capabilities

### 🔧 REST API Features

- ➕ Create Products  
- 🔍 Retrieve Products by ID  
- ✏️ Update Existing Products  
- ❌ Delete Products  
- 📋 List All Products  
- 🔎 Search by Name  
- 🏷 Filter by Category  
- ✅ Filter by Availability  

All endpoints return proper HTTP status codes and follow REST conventions.

---

## 🧠 Engineering Approach

### 🔴 Test-Driven Development (TDD)

Every feature was implemented following the red-green-refactor cycle:

1. Write failing tests  
2. Implement minimal working code  
3. Refactor safely under passing tests  

This ensures correctness, maintainability, and regression protection.

### 🟢 Behavior-Driven Development (BDD)

- Gherkin feature files  
- Background data loading  
- Human-readable scenarios  
- Selenium automation for UI validation  

The application behavior is verified from a user perspective — not just at code level.

---

## 🧪 Test Coverage

✅ Model Unit Tests  
✅ Route & API Tests  
✅ Query Parameter Tests  
✅ Background Data Loader  
✅ Full CRUD BDD Scenarios  
✅ End-to-End Selenium Automation  

All scenarios pass with zero failures.

---

## ⚙ Installation

### Clone Repository

```bash
git clone https://github.com/ThatSunny/tdd-bdd-final-project.git
cd tdd-bdd-final-project
```

### Setup Environment

```bash
bash bin/setup.sh
exit
```

Restart your shell to activate the virtual environment.

---

## ▶ Running the Service

Start the application:

```bash
honcho start
```

The API will run at:

```
http://localhost:8080
```

---

## 🧪 Running Tests

### Unit & Route Tests

```bash
nosetests
```

### BDD Scenarios

Make sure the service is running, then:

```bash
behave
```

Expected result:

```
1 feature passed
7 scenarios passed
0 failed
```

---

## 📁 Project Structure

```
tdd-bdd-final-project/
│
├── service/
│   ├── models.py
│   ├── routes.py
│   └── common/
│
├── tests/
│   ├── test_models.py
│   └── test_routes.py
│
├── features/
│   ├── products.feature
│   └── steps/
│       ├── load_steps.py
│       └── web_steps.py
│
├── bin/
│   └── setup.sh
│
├── Procfile
├── requirements.txt
└── README.md
```

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| **Python** | Core language |
| **Flask** | REST framework |
| **SQLite** | Data storage |
| **Nose / PyUnit** | Unit testing |
| **Behave** | BDD testing |
| **Selenium** | UI automation |
| **Gunicorn** | Production WSGI server |
| **Honcho** | Process manager |

---

## 📊 What This Project Demonstrates

- RESTful API design principles  
- Enum validation & query filtering  
- Proper HTTP status handling  
- Test-first development workflow  
- Automation-driven validation  
- Clean, maintainable architecture  
- Production-style engineering discipline  

---

<div align="center">

### 🏆 Certification Project

Made with ❤️ as part of the **IBM Introduction to TDD/BDD Certification**

![IBM Badge](https://img.shields.io/badge/IBM-Certified-052FAD?style=for-the-badge&logo=ibm&logoColor=white)

</div>

---

## 📜 License

Licensed under the Apache License.

---
