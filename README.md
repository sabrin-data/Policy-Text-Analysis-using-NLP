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
```

---

## 🔍 Analysis Workflow

1. Created and loaded sample insurance policy wording data
2. Cleaned and standardized policy text
3. Applied basic NLP text preprocessing
4. Compared old and new policy versions by policy group
5. Identified added and removed words
6. Detected benefit-level and coverage amount changes
7. Classified policy changes by impact level
8. Used LLM-assisted summaries for reporting notes
9. Created visualizations to show policy changes
10. Exported the final analysis into an Excel report

---

## 🤖 NLP and LLM-Assisted Analysis

This project combines basic NLP-style text processing with AI-assisted summarization.

The NLP-related analysis includes:

- Text cleaning and standardization
- Old vs. new policy text comparison
- Added and removed word detection
- Change detection across policy versions
- Benefit-level and coverage change analysis
- Structured text findings for reporting

Large Language Models (LLMs), such as ChatGPT, were used manually as an AI-assisted tool to summarize policy wording differences and generate reporting notes.

Prompt used:

```text
Compare the following two policy wording samples.

Old Policy:
[Old policy text]

New Policy:
[New policy text]

Please summarize:
1. Key wording differences
2. Added benefits
3. Removed or changed terms
4. Benefit-level impact
5. A short reporting note for a data analyst
```

---

## 📊 Visualizations

The notebook includes visualizations for:

- Policy changes by change type
- Coverage amount change by policy group
- Average coverage change by category

These visualizations help summarize the impact of wording and benefit-level changes across different policy categories.

---

## 📸 Project Screenshots

### Excel Policy Report

![Excel Policy Report](images/Policy_Report.png)

### Coverage Amount Change Visualization

![Coverage Amount Change Visualization](images/Coverage_Visualization.png)

---

## 📤 Output

The final output is an Excel report:

```text
outputs/policy_comparison_report.xlsx
```

The report includes:

| Output Field | Description |
|---|---|
| LLM_Assisted_Summary | AI-assisted summary of the policy change |
| Policy_Group | Policy comparison group |
| Category | Policy category |
| Old_Benefit_Level | Previous benefit level |
| New_Benefit_Level | Updated benefit level |
| Coverage_Change | Difference in coverage amount |
| Added_Words | New wording added |
| Removed_Words | Wording removed from old policy |
| Change_Type | Major, Moderate, or Minor change |

---

## ✅ Key Results

| Metric | Value |
|---|---:|
| Total policies analyzed | 10 |
| Total policy groups compared | 5 |
| Major changes identified | 5 |
| Average coverage change | 1,210 |

---

## ▶️ How to Run the Project

1. Clone or download this repository.

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the analysis notebook in Visual Studio Code:

```text
notebooks/policy_text_analysis.ipynb
```

4. Select a Python environment.

5. Run all cells in order.

6. Review the generated Excel report in the `outputs` folder.

---

## 💡 Project Value

This project demonstrates practical data analysis and text analysis skills, including:

- Data cleaning
- NLP-based text comparison
- Text preprocessing
- Change detection
- Policy comparison
- Benefit-level analysis
- Reporting
- Visualization
- AI-assisted summarization

It is especially relevant for **Data Analyst** and entry-level **NLP / AI-assisted analysis** roles involving document comparison, text analysis, reporting, and the use of Large Language Models as productivity tools.
