# 🏦 ParaBank Online Banking Automation

![Playwright](https://img.shields.io/badge/Automation-Playwright-green)
![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue)
![Framework](https://img.shields.io/badge/Framework-POM-orange)
![Testing](https://img.shields.io/badge/TestRunner-Playwright_Test-red)
![Report](https://img.shields.io/badge/Reports-Allure-purple)
![Version](https://img.shields.io/badge/Version_Control-Git%2FGitHub-black)

---

## 📌 Project Overview

ParaBank is a demo online banking application used for practicing and implementing automation testing scenarios.

This project automates banking workflows using:

🚀 **Playwright**
💻 **TypeScript**
🏗️ **Page Object Model (POM)**
📊 **HTML & Allure Reporting**

The framework is designed with reusable components, maintainable page classes, test data management, assertions, and automation best practices.

---

# 🔥 Automation Modules Covered

| Module                        | Status      |
| ----------------------------- | ----------- |
| 👤 Customer Registration      | ✅ Automated |
| 🔐 Login Authentication       | ✅ Automated |
| 💳 Account Overview           | ✅ Automated |
| 🏦 Open New Account           | ✅ Automated |
| 💸 Transfer Funds             | ✅ Automated |
| 🧾 Bill Payment               | ✅ Automated |
| 📜 Transaction History        | ✅ Automated |
| 👨‍💼 Customer Profile Update | ✅ Automated |
| 💰 Loan Request               | ✅ Automated |
| 🚪 Logout                     | ✅ Automated |

---

# 🏗️ Framework Architecture

```
                 Test Cases
                     |
                     ↓
              Action Layer
                     |
                     ↓
              Page Objects
                     |
                     ↓
            Playwright Engine
                     |
                     ↓
             ParaBank Website
```

---
## 📁 Complete Project Structure

```text
ParaBank-Playwright-Automation
│
├── src
│   │
│   ├── pages
│   │   ├── LoginPage.ts
│   │   ├── RegistrationPage.ts
│   │   ├── AccountOverviewPage.ts
│   │   ├── OpenAccountPage.ts
│   │   ├── TransferFundsPage.ts
│   │   ├── BillPaymentPage.ts
│   │   ├── TransactionPage.ts
│   │   ├── ProfilePage.ts
│   │   ├── LoanPage.ts
│   │   └── LogoutPage.ts
│   │
│   ├── actions
│   │   ├── LoginAction.ts
│   │   ├── RegistrationAction.ts
│   │   ├── AccountAction.ts
│   │   ├── TransferAction.ts
│   │   ├── BillPaymentAction.ts
│   │   ├── TransactionAction.ts
│   │   ├── ProfileAction.ts
│   │   └── LoanAction.ts
│   │
│   ├── testData
│   │   ├── userData.json
│   │   └── accountData.json
│   │
│   └── utils
│       ├── TestBase.ts
│       └── Constants.ts
│
├── tests
│   ├── Registration.spec.ts
│   ├── Login.spec.ts
│   ├── AccountOverview.spec.ts
│   ├── OpenAccount.spec.ts
│   ├── TransferFunds.spec.ts
│   ├── BillPayment.spec.ts
│   ├── Transaction.spec.ts
│   ├── ProfileUpdate.spec.ts
│   └── LoanRequest.spec.ts
│
├── allure-results
│
├── allure-report
│
├── playwright.config.ts
├── package.json
├── package-lock.json
└── README.md
```

### Folder Description

| Folder/File          | Purpose                                       |
| -------------------- | --------------------------------------------- |
| 📂 pages             | Contains all Page Object classes and locators |
| 📂 actions           | Contains reusable business actions            |
| 📂 testData          | Stores test data files                        |
| 📂 utils             | Common utilities and base classes             |
| 📂 tests             | Contains Playwright test scenarios            |
| 📂 allure-results    | Stores Allure execution results               |
| 📂 allure-report     | Generated Allure HTML report                  |
| playwright.config.ts | Playwright configuration                      |
| package.json         | Project dependencies and scripts              |
| README.md            | Project documentation                         |

```
```

# 🛠️ Tech Stack

| Technology         | Usage                |
| ------------------ | -------------------- |
| 🎭 Playwright      | Web Automation       |
| 📘 TypeScript      | Programming Language |
| 🏗️ POM            | Framework Design     |
| 🧪 Playwright Test | Test Execution       |
| 📊 Allure          | Test Reporting       |
| 🔧 GitHub          | Source Control       |

---

# ▶️ Execution Commands

## Install Dependencies

```bash
npm install
```

---

## Run Test Cases

```bash
npx playwright test
```

---

## Run Test With Browser

```bash
npx playwright test --headed
```

---

# 📊 Allure Report Setup

## Install Allure Reporter

```bash
npm install -D allure-playwright
```

---

## Execute Tests With Allure

```bash
npx playwright test --reporter=allure-playwright
```

Generated folder:

```
allure-results
```

---

## Generate Allure Report

```bash
npx allure generate allure-results --clean -o allure-report
```

---

## Open Allure Dashboard

```bash
npx allure open allure-report
```

---

# ⭐ Key Features

✅ Page Object Model Framework
✅ Reusable Page Actions
✅ Dynamic Locators
✅ Test Data Management
✅ Assertions & Validations
✅ Cross Browser Execution
✅ HTML Reporting
✅ Allure Reporting
✅ GitHub Integration

---

# 👨‍💻 Author

**Lalit Gupta(Quality Engineer - Digital Assurance)**

---

⭐ If you find this project useful, feel free to explore and contribute.
