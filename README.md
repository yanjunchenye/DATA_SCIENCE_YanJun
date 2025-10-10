# 🧠 DATA_SCIENCE_YanJun

Personal repository for the **Data Science** program completed at *The Bridge*.  
It includes Jupyter notebooks, exercises, and projects organized by modules — covering everything from programming fundamentals to *Machine Learning* and *Data Engineering*.

---

## 📂 Repository Structure

```
ONLINE_DS_THEBRIDGE_YanJun/
├── analytics/
│   └── EDA/                 # Exploratory Data Analysis
├── Machine Learning/        # Classical modeling and evaluation
├── Data Engineering/
│   └── LLM/                 # LLM experiments and data pipelines
├── fundamentals/
│   └── hundir la flota/     # Python fundamentals project (Battleship game)
└── CAPGEMINI/               # Business case project
```

---

## 🚀 Installation & Usage

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yanjunchenye/ONLINE_DS_THEBRIDGE_YanJun.git
cd ONLINE_DS_THEBRIDGE_YanJun
```

### 2️⃣ Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -U pip wheel
pip install jupyterlab numpy pandas matplotlib seaborn scikit-learn plotly tqdm joblib
# For LLMs or Data Engineering modules:
# pip install openai langchain tiktoken sentence-transformers sqlalchemy
```

### 4️⃣ Launch Jupyter Lab

```bash
jupyter lab
```

---

## 📘 Folder Overview

### 🧩 `analytics/EDA`
- Data cleaning and exploration  
- Visualization and profiling  
- Descriptive data analysis

### 🤖 `Machine Learning`
- Predictive modeling and classification  
- Evaluation with metrics and cross-validation  
- Building pipelines with `scikit-learn`

### ⚙️ `Data Engineering/LLM`
- Experiments with *Large Language Models (LLMs)*  
- Data ingestion and transformation  
- Automation and lightweight orchestration exercises

### 🐍 `fundamentals/hundir la flota`
- Python fundamentals project: *Battleship game implementation*  
- Focus on logic, control flow, and modular design

### 🏢 `CAPGEMINI`
- Real-world business case  
- Documentation, analysis, and notebooks

---

## 🧪 Recommended Data Structure

```
data/
├── raw/         # Original data
├── interim/     # Intermediate processed data
└── processed/   # Ready-to-model datasets
```

> ⚠️ Datasets are not included in the repository.  
> Add them locally inside the `data/` folder.

---

## 🧭 Best Practices

- Use clear notebook naming conventions:  
  `01_eda.ipynb`, `02_preprocessing.ipynb`, `03_model.ipynb`, etc.  
- Save trained models using `joblib` (`model.joblib`).  
- Store API keys or secrets in a `.env` file (for OpenAI or similar APIs).

---

## 📜 License

This project **does not have a public license**.  
All rights reserved (© Yan Jun).  
Reproduction, distribution, or usage of this code is not permitted without explicit authorization from the author.

---

## ✍️ Author

**Yan Jun**  
Data Science Student  
GitHub: [@yanjunchenye](https://github.com/yanjunchenye)

---

## 🌟 Final Notes

This repository showcases the progressive learning path throughout the *Data Science* program at **The Bridge**, combining theory, practice, and applied projects.  
Its goal is to demonstrate growth, organization, and technical skills across the full data lifecycle.
