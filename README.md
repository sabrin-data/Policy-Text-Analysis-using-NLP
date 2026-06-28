# AI-Assisted Policy Text Analysis

## Project Overview

This project analyzes sample insurance policy wording data to identify text differences, wording variations, benefit-level changes, and coverage amount changes across policy documents.

The project uses Python and Pandas for data cleaning, text preparation, policy comparison, change classification, visualization, and Excel report generation. Large Language Models (LLMs), such as ChatGPT, were used manually as an AI-assisted tool to summarize key wording differences and create clear reporting notes.

This project uses sample training data created for analysis purposes and does not contain real customer or confidential policy information.

---

## Objectives

* Clean and organize sample policy wording data
* Compare old and new versions of policy text
* Identify added and removed wording
* Detect benefit-level and coverage amount changes
* Classify changes as Major, Moderate, or Minor
* Use LLM-assisted summaries to support reporting
* Create simple visualizations for analysis
* Export structured findings into an Excel report

---

## Dataset

The dataset contains sample insurance policy records with the following columns:

* Policy_ID
* Policy_Group
* Version
* Category
* Policy_Text
* Benefit_Level
* Coverage_Amount

Each policy group includes an old and new policy version to allow comparison.

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Excel
* Jupyter Notebook
* Large Language Models (LLMs)
* AI-assisted text analysis

---

## Project Structure

```text
AI-Assisted-Policy-Text-Analysis/
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
├── README.md
└── requirements.txt
```

---

## Analysis Steps

1. Created and loaded sample policy wording data
2. Cleaned policy text by standardizing text format
3. Compared old and new policy versions by policy group
4. Identified added and removed words
5. Detected benefit-level and coverage amount changes
6. Classified changes by impact level
7. Added LLM-assisted summaries for reporting
8. Created visualizations to show policy changes
9. Exported the final analysis into an Excel report

---

## LLM-Assisted Analysis

Large Language Models (LLMs), such as ChatGPT, were used manually as an AI-assisted tool to summarize policy wording differences and generate reporting notes.

No API integration was used in this project.

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

## Visualizations

The notebook includes visualizations for:

* Policy changes by change type
* Coverage amount change by policy group
* Average coverage change by category

These visualizations help summarize the impact of wording and benefit-level changes across different policy categories.

---

## Output

The final output is an Excel report:

```text
outputs/policy_comparison_report.xlsx
```

The report includes:

* LLM-assisted summary
* Policy group
* Category
* Old and new benefit levels
* Benefit-level change status
* Old and new coverage amounts
* Coverage amount change
* Added wording
* Removed wording
* Old policy text
* New policy text
* Change type

---

## Key Results

* Total policies analyzed: 10
* Total policy groups compared: 5
* Major changes identified: 5
* Average coverage change: 1210

---

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```text
notebooks/policy_text_analysis.ipynb
```

4. Run all cells in order.
5. Review the generated Excel report in the `outputs` folder.

---

## Project Value

This project demonstrates practical data analysis skills, including data cleaning, text analysis, policy comparison, reporting, visualization, and AI-assisted summarization.

It is especially relevant for Data Analyst roles involving document comparison, benefit analysis, reporting, and the use of Large Language Models as productivity tools.
