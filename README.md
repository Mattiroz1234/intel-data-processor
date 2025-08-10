# 📡 Intel Data Processor

**Intel Data Processor** – A Python-based Army Intelligence Data Processor, built as a collaborative **Git** & **Trello** exercise.
This **command-line application** processes mission data and personnel records to generate intelligence summaries, filter information, and export reports.

---

## 📌 Features

### 🗂 Mission Data Processing

* Load and filter missions by status
* Count missions by priority level

### 👤 Personnel Data Analysis

* Filter personnel by clearance level
* Group personnel by unit

### 📄 Report Generation

* Mission summary reports
* Personnel clearance reports
* Export data to file

### 💻 Interactive Command-Line Interface

* Menu-driven navigation for easy use

---

## 🛠 Technologies & Tools

* **Python 3.x** – Core application logic
* **Git & GitHub** – Version control and collaboration
* **Trello** – Task management and workflow tracking

---

## 📂 Project Structure

```
intel-data-processor/
├── mission_processor.py      # Mission data functions
├── personnel_analyzer.py     # Personnel data functions
├── report_generator.py       # Report generation functions
├── main.py                   # Integrated CLI application
├── test_data.py               # Simple functional tests
├── .gitignore                # Ignore sensitive/temp files
└── README.md                 # Project documentation
```

---

## 🚀 Getting Started

1️⃣ **Clone the repository**

```bash
git clone https://github.com/<your-username>/intel-data-processor.git
cd intel-data-processor
```

2️⃣ **Run the application**

```bash
python main.py
```

3️⃣ **Run tests**

```bash
python test_data.py
```

---

## 📋 Example Usage

```
=== ARMY INTELLIGENCE DATA PROCESSOR ===

1. Mission Summary
2. Personnel Report
3. Filter Active Missions
4. Show Top Secret Personnel
5. Exit
```

---

## 👥 Team Workflow

**Branch workflow**:

* `feature-mission-data` → Mission data processing
* `feature-personnel` → Personnel data analysis
* `feature-reports` → Report generation

Merged into `main` via Pull Requests.

**Key Git concepts practiced**:

* Local vs remote repositories
* Branch creation and merging
* Pull Requests and code reviews
* Conflict resolution
* Revert commits
* `.gitignore` usage

**Trello workflow**:

* **Backlog → In Progress → Code Review → Done**
* Cards assigned to team members with due dates

---

## 🔒 Security

`.gitignore` ensures **sensitive data** (classified files, keys, temporary files) are **not committed**.

---

## 🧑‍💻 Team Members

* **Student A** – Mission Data Processor
* **Student B** – Personnel Analyzer & Final Integration
* **Student C** – Report Generator

---

## 📅 Reflection

* **Branches**: Allowed isolated work without overwriting teammates’ code
* **Conflicts**: Learned how to resolve merge conflicts in Git
* **Code Review**: Improved code quality through peer review
* **Data Processing**: Functions could be adapted for real-world intelligence analysis
