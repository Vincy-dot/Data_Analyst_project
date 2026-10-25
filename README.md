# 📊 Sales Method & Revenue Analysis | Data Analyst Portfolio

## 📌 Business Overview
This project evaluates the performance of different sales approaches (**Call**, **Email**, and **Email + Call**) to understand their impact on revenue generation. The primary goal is to provide data-driven insights to optimize customer outreach strategies and improve overall operational efficiency.

---

## 🛠️ Tech Stack & Methods
* **Language:** Python
* **Environment:** Jupyter Notebook (`Data_Analyst_Exam.ipynb`)
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Analytical Focus:** Exploratory Data Analysis (EDA), Statistical Distribution (Boxplots), Cohort/Weekly Revenue Tracking

---
## 📝 Task List

Your written report should include written text summaries and graphics of the following:
- Data validation:   
  - Describe validation and cleaning steps for every column in the data 
- Exploratory Analysis:  
  - Include two different graphics showing single variables only to demonstrate the characteristics of data  
  - Include at least one graphic showing two or more variables to represent the relationship between features
  - Describe your findings
- Definition of a metric for the business to monitor  
  - How should the business use the metric to monitor the business problem
  - Can you estimate initial value(s) for the metric based on the current data
- Final summary including recommendations that the business should undertake

---

## 📈 Key Findings & Insights
**Revenue Distribution across Channels and weekly performance trends:**
   * **Email + Call:** Generates significantly higher individual revenue per customer compared to single-channel methods, though requiring higher time investment.
   * **Email:** Produces consistent, scalable revenue.
   * **Call:** Yields lower average revenue per conversion and exhibits lower operational leverage.
<img width="500" height="400" alt="boxplot_total revenue" src="https://github.com/user-attachments/assets/edbead1c-ade9-4789-a487-8467a005eb38" />

<img width="500" height="400" alt="spread of revenue by method" src="https://github.com/user-attachments/assets/70a626de-72a2-4ea9-ba70-d39a6818696f" />

<img width="600" height="500" alt="trend by week" src="https://github.com/user-attachments/assets/eb2a5eac-845e-478f-9ca7-03e3b255df91" />

---

## 💡 Strategic Recommendations
* **Focus on High-Value Leads:** Prioritize the combined **Email + Call** approach for high-priority/enterprise leads to maximize deal size.
* **Automate Outreach:** Utilize pure **Email** sequences for early-stage leads to maintain broad pipeline coverage efficiently.

---

## 📂 Repository Structure
```text
├── notebook.ipynb    # Main Jupyter Notebook containing code, charts, and analysis
└── README.md         # Project documentation and executive summary
