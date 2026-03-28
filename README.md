# 🧠 Dynamic SQL-Driven Quiz Engine
**Version 1.0.0 | High-Performance Python-MySQL Integration**

---

## ⚡ Executive Summary
A streamlined, command-line interface (CLI) application designed for persistent data management and interactive testing. This engine bridges the gap between Relational Database Management Systems (RDBMS) and user-facing logic, utilizing `mysql-connector` for real-time data injection and retrieval.

### 🛠 Tech Stack & Architecture
* **Language:** Python 3.x
* **Database:** MySQL 8.0+
* **Core Libraries:** `mysql-connector-python`, `random`, `sys`
* **Logic Gate:** Implements `random.sample` to ensure non-linear, unique question selection per session.

---

## 🚀 Deployment Intelligence

### 1. Environment Configuration
Ensure your local environment has the necessary database driver installed:
```bash
pip install mysql-connector-python
```

### 🛡 System Integrity & Error Handling

**Input Validation:** Wrapped in try-except blocks to prevent crashes on invalid data types (ValueErrors).

**Memory Management:** Explicitly closes cursors and database connections upon exit.

**Randomization:** Logic ensures that no two questions are repeated within the same attempt count.


### 👤 Credits & Branding

Lead Developer: ItzAirlok
Engineered for performance, persistence, and scale.
