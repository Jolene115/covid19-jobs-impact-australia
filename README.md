# 📊 Australia's Jobs in Crisis: Tracking COVID-19’s Economic Shockwave (2020–2021)

This repository presents a data analysis project exploring the impact of the COVID-19 pandemic on industry-specific employment trends across Australia. Using weekly payroll job index data from the Australian Bureau of Statistics (ABS), the project provides visual insights into how different sectors responded during 2020–2021.

---

## 🧪 Interactive Notebook

Click below to open and run the notebook in **Google Colab** (no setup required):

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jolene115/covid19-jobs-impact-australia/blob/main/covid_analysis.ipynb)

> **Note**: To run the notebook in Colab, you may need to upload the dataset file (`payroll_jobs_table1.xlsx`) manually.

---

## 📁 Project Structure

📦 covid19-jobs-impact-australia

├── covid_analysis.ipynb # Main analysis notebook

├── payroll_jobs_table1.xlsx # Raw dataset from ABS

└── README.md # Project documentation


---

## 📊 Project Objectives

- Analyze weekly payroll job indexes from ABS (2020–2021)
- Compare trends across key Australian industries:
  - Accommodation & Food Services
  - Retail Trade
  - Health Care & Social Assistance
  - Mining
  - Other Services
- Visualize COVID-19’s impact on workforce size and recovery

---

## 📈 Key Insights

- Significant job losses were observed in **hospitality and retail** sectors during lockdowns.
- **Health care and mining** showed stronger resilience.
- Recovery patterns varied sharply between industries post-lockdown.

**Deep Dive: Pre- vs During-COVID Impact by Industry**
To quantify the economic shock, we compared the average payroll jobs index **before** and **during** COVID-19 for selected industries:

| Industry Division                     | Pre-COVID Avg | COVID Avg | % Change   |
| ------------------------------------- | ------------- | --------- | ---------- |
| Accommodation & Food Services         | 98.59         | 94.35     | **-4.30%** |
| Rental, Hiring & Real Estate Services | 99.28         | 96.79     | -2.51%     |
| Transport, Postal & Warehousing       | 99.63         | 97.17     | -2.46%     |
| Education & Training                  | 99.79         | 97.37     | -2.42%     |
| Wholesale Trade                       | 99.85         | 97.96     | -1.89%     |

🧠 Interpretation
- **Accommodation & Food Services** faced the sharpest decline (~4.3%), reflecting vulnerability to lockdowns.
- Other industries experienced moderate declines between **~1.9% to 2.5%**.
- No sector in this subset fully returned to pre-pandemic levels by mid-2021.

> 📅 **Periods Used**:  
> - Pre-COVID: `2020-03-07` to `2020-04-04`  
> - COVID Impact: `2020-04-05` to `2021-06-26`

**Figure 1: Percentage change in Payroll Jobs Index**  
This bar chart shows the percentage drop in payroll jobs for selected Australian industries during the COVID-19 period (April 2020 – June 2021), compared to the pre-COVID baseline.  
Sectors like *Accommodation & Food Services* experienced the sharpest declines.

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/c74fc8e9-c410-4dce-92af-8747ef900b80" />

**Figure 2: Weekly Payroll Jobs Trends (2020–2021)**  
This line chart visualizes weekly changes in payroll jobs across industries.  
Notable drops align with national lockdowns (March–April 2020) and show varying recovery patterns.

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/df723c5c-5b18-46e7-8266-15831eb093cd" />

- **Accommodation & Food Services** had the **sharpest drop** (−4.3%)
- Other sectors saw **moderate declines** between −1.9% to −2.5%
---

## 📚 Data Source

- **Dataset**: [Payroll Jobs Index – Table 1](https://www.abs.gov.au/statistics/labour/jobs/payroll-jobs/latest-release)
- **Publisher**: Australian Bureau of Statistics (ABS)
- **Format**: Excel `.xlsx`

---

## 💻 Technologies Used

- Python
- Google Colab / Jupyter Notebook
- pandas
- matplotlib
- openpyxl

---

## 📝 Conclusion

The Australian job market experienced uneven disruptions due to COVID-19. Industries like **hospitality** and **real estate** were more sensitive to lockdowns, while sectors like **wholesale trade** showed better resilience. These insights provide critical signals for policymakers and economic recovery planning.

## Fast Summary (Statistics and Influence Expectation)

**Key Statistics (Quantitative Impact)**
- **Accommodation and food services:** largest decline in payroll jobs during covid-19, averaging a **-4.30% drop** in job index.
- **Transport, Education, and Rental sectors:** all saw **2%-2.5% drops**, showing moderate disruption.
- **Wholesale Trade:** remained the most stable, with just a **-1.89% drop**, also the least drop and to be likely due to its essential role in supply chains.

**Impacted Populations**
- Analysis focused on Australia (National level) and All Age Groups.
- Highlights how specific industries were more vulnerable to lockdowns and policy measures.
- Ties back to real economic and social outcomes: **school closure, hospitality shutdowns, logistics restrictions.** 

**Data-driven Influence and Insights**
- This analysis helps policymakers and economic planners identify which sectors needed more financial support.
- Could be used by businesses to **anticipate risk in similar future** **scenarios** and disruptions.
- Reinforces the value of data storytelling: combining time-series trends, milestones (lockdowns), and annotated visualisations to communicate findings clearly.

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Jolene115/covid19-jobs-impact-australia.git
