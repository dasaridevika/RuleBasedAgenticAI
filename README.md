# 🤖 Rule-Based AI Data Analyst Agent

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Agentic%20AI-Rule%20Based-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Multi--Agent-System-orange?style=for-the-badge"/>
</p>

---

# 🚀 Overview

The **Rule-Based AI Data Analyst Agent** is a multi-agent analytical framework designed to automate end-to-end data analysis workflows.

Inspired by the concept of **Agentic AI**, this project simulates how a real-world data analyst works by decomposing analytical tasks into multiple specialized agents. Each agent is responsible for a specific task such as data understanding, cleaning, exploratory analysis, visualization, insight generation, and reporting.

The system minimizes manual effort and provides an automated analytical pipeline for structured datasets.

---

# ✨ Features

## 📂 Dataset Loader Agent

* Loads CSV datasets.
* Initializes the analytical workflow.

## 🔍 Dataset Understanding Agent

Performs automatic dataset profiling:

* Dataset shape
* Column information
* Data types
* Missing values analysis
* Numerical and categorical feature identification

## 🧹 Data Cleaning Agent

Automates:

* Missing value handling
* Duplicate removal
* Basic preprocessing
* Data quality enhancement

## 🚨 Outlier Detection Agent

* Detects anomalies using the Interquartile Range (IQR) technique.
* Generates column-wise outlier reports.

## 📊 Exploratory Data Analysis (EDA) Agent

Performs:

* Summary statistics generation
* Correlation analysis
* Distribution analysis
* Feature relationship analysis

## 📈 Visualization Agent

Automatically generates visualizations including:

* Histograms
* Boxplots
* Countplots
* Correlation Heatmaps

## 💡 Insight Generation Agent

Extracts meaningful business insights from the dataset.

Examples:

* Trend identification
* Statistical observations
* Feature-level insights
* Data quality findings

## 📄 Report Generator Agent

Creates consolidated analytical reports containing:

* Dataset overview
* Cleaning summary
* Outlier analysis
* EDA findings
* Generated insights

## 💬 Query Agent

Allows interaction with the dataset using natural language-like queries.

Example:

```text
Show top 5 rows

Display missing values

Show summary statistics

What are the column names?

Display dataset shape
```

---

# 🧠 Agent Workflow

```text
Dataset Input
      │
      ▼
Loader Agent
      │
      ▼
Dataset Understanding Agent
      │
      ▼
Cleaning Agent
      │
      ▼
Outlier Detection Agent
      │
      ▼
EDA Agent
      │
      ▼
Visualization Agent
      │
      ▼
Insight Generation Agent
      │
      ▼
Report Generation Agent
      │
      ▼
User Query Handling
```

---

# 🏗️ Architecture

```text
                    Master AI Analyst Agent
                                   │
 ┌────────────────────────────────────────────────────┐
 │                                                    │
 ▼                                                    ▼

Dataset Loader Agent                      Query Agent
            │
            ▼
Dataset Understanding Agent
            │
            ▼
Data Cleaning Agent
            │
            ▼
Outlier Detection Agent
            │
            ▼
EDA Agent
            │
            ▼
Visualization Agent
            │
            ▼
Insight Generation Agent
            │
            ▼
Report Generator Agent
```

---

# 🛠️ Tech Stack

| Technology | Purpose                   |
| ---------- | ------------------------- |
| Python     | Core Development          |
| Pandas     | Data Manipulation         |
| NumPy      | Numerical Computation     |
| Matplotlib | Data Visualization        |
| Seaborn    | Statistical Visualization |
| OOP        | Agent Architecture        |

---

# 📂 Project Structure

```bash
📦 Rule-Based-AI-Data-Analyst
│
├── 03_Advanced_Ai_Data_Analyst.ipynb
├── sample_dataset.csv
├── generated_charts/
├── analysis_report.txt
└── README.md
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Rule-Based-AI-Data-Analyst.git

cd Rule-Based-AI-Data-Analyst
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

---

# ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
03_Advanced_Ai_Data_Analyst.ipynb
```

Run all cells sequentially to execute the complete analytical pipeline.

---

# 📚 Key Learnings

Through this project, I gained practical experience in:

✅ Agentic AI Design Principles
✅ Rule-Based Multi-Agent Systems
✅ Object-Oriented Programming (OOP)
✅ Automated Data Cleaning
✅ Exploratory Data Analysis (EDA)
✅ Outlier Detection Techniques
✅ Data Visualization Automation
✅ Insight Generation
✅ Analytical Report Automation

---

# 🔮 Future Enhancements

* Integrate Large Language Models (LLMs)
* Build Autonomous Decision-Making Agents
* Develop Streamlit-based UI
* Add SQL Database Support
* Enable Voice-based Queries
* Integrate LangChain
* Implement Retrieval-Augmented Generation (RAG)

---

# 👨‍💻 Author

**Dasari Devika**

Aspiring Data Analyst | AI Enthusiast | Building Intelligent Data Systems

---

⭐ If you found this project useful, consider giving it a star!
