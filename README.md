# Group 6 – Bug Busters  
**CSC256 · Software Quality Assurance · Fall 2025**

---

## 🧩 Project Overview
This repository contains the final group project for CSC256: Software Quality Assurance.  
Our goal is to extend the Sprint 5 Task Tracker application and apply **hybrid testing** and **CI/CD best practices** across all layers — unit, integration, BDD, and Robot acceptance tests.

---

## 🧠 Team Roles
| Role | Member | Responsibilities |
|------|---------|------------------|
| **Project Lead** | *Mariam Faragalla* | Organize board, assign issues, track milestones |
| **DevOps / CI Lead** | *Evan Pavone* | Configure GitHub repo, CI workflows, branch protection, and evidence |
| **QA / Test Lead** | *Henry Vogel* | Maintain pytest + Robot test suites |
| **Documentation Lead** | *Jacob Reilly* | Manage traceability and final test report |
| **Developer** | *Joseph Baynard* | Implement new features, refactor validation logic, and resolve issues flagged in CI |

---

## ⚙️ CI/CD Summary
- **Workflows:** python-app.yml (unit/integration), ui-tests.yml, bdd-tests.yml, robot.yml  
- **Triggers:** path filters, PR labels (`run-e2e`, `run-bdd`, `run-robot`), and manual dispatch  
- **Artifacts:** Robot logs (`log.html`, `report.html`) uploaded per run  
- **Branch Protection:** PR required, 1 review, status checks enforced  

---

## 🧪 Testing Layers
| Type | Tool | Folder | CI Label |
|------|------|---------|-----------|
| Unit / Integration | Pytest | `tests/api`, `tests/storage` | `ci:workflow` |
| UI / E2E | Playwright / Selenium | `tests/ui` | `test:ui` |
| BDD | Behave / Gherkin | `tests/bdd` | `test:bdd` |
| Acceptance | Robot Framework | `tests/acceptance/robot` | `test:robot` |

---

## 📋 Traceability
See **`traceability.md`** for mapping between requirements, test cases, and automation evidence.

---

## 🧾 Appendix Evidence
All CI screenshots, Robot artifacts, and coverage reports will be stored under:
