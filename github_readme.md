# Global Developer Ecosystem & Technology Trends Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![IBM Cognos](https://img.shields.io/badge/BI-IBM%20Cognos%20Analytics-052FAD.svg)](https://www.ibm.com/products/cognos-analytics)

An end-to-end business intelligence and data analytics capstone project completed as part of the **IBM Data Analyst Professional Certificate**. This project investigates global developer demographics, benchmarks existing production technology stacks, and forecasts industry adoption trends using Python, SQL, and IBM Cognos Analytics.

---

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [Key Questions Answered](#key-questions-answered)
- [Analytics Architecture & Workflow](#analytics-architecture--workflow)
- [Key Dashboard Insights](#key-dashboard-insights)
- [Technology Stack](#technology-stack)
- [Repository Structure](#repository-structure)
- [Setup & Reproduction Guide](#setup--reproduction-guide)
- [Author & Acknowledgments](#author--acknowledgments)

---

## 🎯 Project Overview

In today's fast-moving software industry, technology leaders face ongoing challenges in selecting tech stacks, sourcing specialized talent, and structuring technical upskilling initiatives. 

This project utilizes real-world developer survey datasets to deliver decision-ready business intelligence. Through systematic data wrangling, exploratory data analysis, and interactive dashboard authoring, the resulting deliverables provide actionable visibility into:
1. Current market adoption rates across languages, frameworks, and databases.
2. High-velocity technology shifts and developer migration interest.
3. Global talent distribution, experience levels, and demographic profiles.

---

## 🔍 Key Questions Answered

* Which programming languages and database engines anchor current enterprise production workloads?
* What emerging technologies exhibit the highest developer desire for adoption in the next 1–2 years?
* How are developer age brackets, formal educational attainments, and regional hubs distributed globally?
* Where should organizations allocate tech training budgets to match emerging technical demands?

---

## 🏗 Analytics Architecture & Workflow

```text
Raw Survey Data (.csv / Web Scraping / APIs)
                    │
                    ▼
       Data Ingestion & Cleaning
       • Missing value imputation
       • Deduplication & type conversions
       • Python (pandas, NumPy)
                    │
                    ▼
      Exploratory Data Analysis (EDA)
       • Statistical aggregations & filtering
       • Relational queries & schema joins
       • Python & SQL
                    │
                    ▼
    Interactive Business Intelligence
       • Multi-panel dashboard views
       • Metric KPIs & hierarchy drill-downs
       • IBM Cognos Analytics
                    │
                    ▼
     Executive Reporting & Storytelling
       • Strategic stakeholder presentation
       • Business impact recommendations
```

---

## 📊 Key Dashboard Insights

The project is structured into three executive dashboard tabs within IBM Cognos Analytics:

### 1. Current Technology Adoption
* **Foundational Dominance:** Production systems remain heavily anchored in web standards (**HTML/CSS**, **JavaScript**) and **SQL**.
* **Database Infrastructure:** Relational databases (**MySQL**, **PostgreSQL**, **Microsoft SQL Server**) represent the primary backbone of current enterprise data persistence.

### 2. Future Technology Demand
* **Language Trajectory:** Developer migration trends reveal accelerated interest in **Python** and **TypeScript** for both backend workflows and scalable web development.
* **Cloud & Microservices:** Containerization platforms (**Docker**, **Kubernetes**) and public cloud infrastructure (**AWS**, **Azure**) represent the top forecasted technical investments.

### 3. Workforce Demographics & Talent Distribution
* **Age Demographics:** The workforce is heavily concentrated within the **25–34 age cohort**, indicating an experienced yet adaptable talent pool.
* **Educational Background:** Over **70% of respondents** hold formal higher-education credentials (Bachelor’s or Master’s degrees).
* **Workplace Dynamics:** Analysis reveals shifting preferences toward hybrid and remote technical employment across primary geographic hubs.

---

## 🛠 Technology Stack

| Category | Tools & Libraries |
| :--- | :--- |
| **Business Intelligence** | IBM Cognos Analytics, Microsoft Excel |
| **Programming Language** | Python 3.8+ |
| **Data Analysis & EDA** | `pandas`, `NumPy` |
| **Data Visualization** | `Matplotlib`, `Seaborn` |
| **Database & Querying** | SQL (Relational database querying, aggregation, filtering, joins) |
| **Documentation & Slides** | Markdown, Executive Slide Deck Presentation |

---

## 📂 Repository Structure

```text
├── data/
│   ├── raw/                           # Original survey data files
│   └── processed/                     # Cleaned, model-ready datasets
├── notebooks/
│   └── exploratory_data_analysis.ipynb # Jupyter Notebook containing Python cleaning & EDA
├── dashboards/
│   ├── screenshots/                   # Exported visuals of the Cognos dashboard tabs
│   │   ├── current_tech.png
│   │   ├── future_trends.png
│   │   └── demographics.png
│   └── cognos_specs/                  # Dashboard report specifications (.json / export)
├── reports/
│   └── capstone_final_presentation.pdf # Final stakeholder slide presentation
├── requirements.txt                   # Required Python libraries
├── LICENSE                            # MIT License
└── README.md                          # Project documentation
```

---

## 🚀 Setup & Reproduction Guide

### Prerequisites
* Python 3.8 or higher installed on your system.
* Jupyter Notebook or VS Code with Jupyter extension.

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/developer-tech-trends-analysis.git
cd developer-tech-trends-analysis
```

### 2. Configure Virtual Environment
```bash
# macOS/Linux
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Analysis Notebook
```bash
jupyter notebook notebooks/exploratory_data_analysis.ipynb
```

---

## 👤 Author & Acknowledgments

**Jean Marie Kenne**  
* Bilingual Data Analyst & BI Developer  
* [LinkedIn Profile](https://www.linkedin.com/) | [GitHub Profile](https://github.com/)

Special thanks to **IBM** and **Coursera** for providing the curriculum, tools, and dataset framework for the IBM Data Analyst Professional Certificate Capstone.