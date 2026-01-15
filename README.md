# Playwright TypeScript Hybrid Testing Framework

## 🎯 Project Overview
Senior SDET portfolio project demonstrating advanced test automation skills with Playwright + TypeScript.

**Application Under Test:** [SauceDemo](https://www.saucedemo.com)

---

## 🧪 Test Coverage Matrix
| Layer | Count | |
| :--- | :---: | :--- |
| **E2E UI Tests** | 25-30 | 
| **API Tests** | 15-18  |
| **Hybrid Tests** | 8-10  |
| **Total** | **~60** |

---

## 🚀 Getting Started

### Prerequisites
* **Node.js:** 18.0 or higher
* **npm:** (included with Node.js)

### Installation
1.  **Clone the repo:** `git clone https://github.com/Erick-oGarcia/Playwright-Typescript-Hybrid-Testing.git`
2.  **Install deps:** `npm install`
3.  **Setup browsers:** `npx playwright install`

---

## 🛠️ Execution Commands

| Command | Action |
| :--- | :--- |
| `npm run test` | Run all tests (Headless) |
| `npm run test:ui` | Open Playwright UI Mode (Interactive) |
| `npm run test:e2e` | Run only End-to-End UI tests |
| `npm run test:api` | Run only API tests (Fast feedback) |
| `npm run test:hybrid` | Run tests combining API + UI |
| `npm run report` | Open the latest HTML test report |

---

## 📁 Project Structure
```text
playwright/
├── api/          # API Clients & Controllers
├── fixtures/     # Custom Test Fixtures (Auth JSONs, Data)
├── pages/        # Page Object Models (POM)
├── tests/        # Test Specifications
│   ├── e2e/      # Pure UI Interaction tests
│   ├── api/      # Schema & Endpoint validation
│   └── hybrid/   # Performance-optimized hybrid scenarios
└── utils/        # UserFactory, Data Generators, and Helpers




## 🛠️ Tech Stack
Playwright
TypeScript
Axios (API calls)
AJV (Schema validation)
Faker.js (Test data generation)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## ✍️ Author

-   **Erick Garcia**
    -   GitHub: [@Erick-oGarcia](https://github.com/Erick-oGarcia)
    -   LinkedIn: [erick-garcia](https://www.linkedin.com/in/erick-garcia-399b2b161/)