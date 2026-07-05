# Policy Text Analysis using NLP

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-green)
![NLP](https://img.shields.io/badge/NLP-Text%20Analysis-orange)
![Excel](https://img.shields.io/badge/Excel-Reporting-brightgreen)
![LLMs](https://img.shields.io/badge/LLMs-AI%20Assisted-purple)

## 📌 Project Overview

This project applies **NLP-based text analysis** to sample insurance policy wording data in order to compare old and new policy versions, identify wording differences, detect benefit-level changes, and analyze coverage amount changes.

The project uses **Python**, **Pandas**, **Matplotlib**, and **Excel** for text preprocessing, policy comparison, change detection, visualization, and report generation.

Large Language Models (LLMs), such as ChatGPT, were used manually as an AI-assisted tool to summarize key wording differences and prepare clear reporting notes.

> This project uses sample training data created for analysis purposes and does not contain real customer or confidential policy information.

---

## 🎯 Objectives

- Clean and prepare sample policy wording data
- Apply basic NLP text preprocessing
- Compare old and new versions of policy text
- Identify added and removed wording
- Detect benefit-level and coverage amount changes
- Classify changes as Major, Moderate, or Minor
- Use LLM-assisted summaries to support reporting
- Create simple visualizations for analysis
- Export structured findings into an Excel report

---

## 🗂️ Dataset

The dataset contains sample insurance policy records.

| Column | Description |
|---|---|
| Policy_ID | Unique policy record ID |
| Policy_Group | Group used to compare old and new policy versions |
| Version | Old or New policy version |
| Category | Policy category such as Medical, Dental, Vision, or Life Insurance |
| Policy_Text | Policy wording text |
| Benefit_Level | Benefit level such as Low, Medium, or High |
| Coverage_Amount | Coverage amount value |

Each policy group includes an old and new version to allow text comparison and change detection.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Python | Data analysis and text processing |
| Pandas | Data cleaning and comparison |
| Matplotlib | Data visualization |
| Excel | Final report output |
| Visual Studio Code | Development environment |
| LLMs | AI-assisted summarization and reporting notes |

---

## 📁 Project Structure

```text
Policy-Text-Analysis-using-NLP/
│
├── data/
│   └── policy_samples.csv
│
├── notebooks/
│   └── policy_text_analysis.ipynb
│
├── outputs/
│   └── policy_comparison_report.xlsx
│
├── images/
│   ├── Policy_Report.png
│   └── Coverage_Visualization.png
│
├── README.md
└── requirements.txt
