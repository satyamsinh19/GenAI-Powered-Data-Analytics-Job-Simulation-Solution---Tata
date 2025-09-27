<h1 align="center"> GenAI Powered Data Analytics Job Simulation Solution Tata (Forage)</h1>
<h1 align="center">Geldium Loan Delinquency Prediction & Ethical AI Collections System 🚀</h1>

A comprehensive data science project outlining a predictive model for loan delinquency and proposing an ethical, AI-driven strategy for customer collections management.

---

## 💡 Overview and Business Context

This project was developed to provide **Geldium's Collections Team** with advanced insights and an automated system to proactively manage financial risk. [cite_start]It moves beyond traditional methods by integrating **Exploratory Data Analysis (EDA)**, **Machine Learning (ML) prediction**, and **Responsible AI governance** into a scalable collections workflow[cite: 52, 107].

### Project Deliverables
All final reports, plans, and presentations are available as PDF and PowerPoint files in the project directory.

| Task ID | Focus Area | Deliverable File |
| :--- | :--- | :--- |
| **Task 1** | Exploratory Data Analysis (EDA) and Risk Profiling | `Task 1.pdf` |
| **Task 2** | Predictive Model Plan and Justification | `Task 2.pdf` |
| **Task 3** | Business Recommendation Report (SMART Goal) | `Task 3.pdf` |
| **Task 4** | AI-Driven Collections System Executive Briefing | `Task 4.pptx` |

---

## ✅ Task 1: Exploratory Data Analysis (EDA) Summary

[cite_start]The initial analysis assessed data quality and identified early risk indicators to prepare the dataset for modeling[cite: 53].

### Key Findings & Risk Indicators
* [cite_start]**High Credit Utilization** (>$0.6$) indicates financial overextension and high repayment stress[cite: 83, 90].
* [cite_start]**Missed\_Payments** $\ge 4$ is a direct behavioral signal of high delinquency risk[cite: 90].
* [cite_start]**Debt\_to\_Income\_Ratio** $> 0.4$ suggests poor affordability and high default probability[cite: 83, 90].
* [cite_start]**Low Credit\_Score** $(<500)$ strongly predicts delinquency[cite: 84].

### Data Quality & Treatment
[cite_start]Data cleaning was required to address inconsistencies like unrealistic Credit\_Utilization values and inconsistent categorical labels[cite: 71, 72].

| Variable | Treatment Method | Justification |
| :--- | :--- | :--- |
| `Credit_Utilization` | Impute (Median) | [cite_start]Reduces impact of outliers and preserves distribution[cite: 80]. |
| `Income` | Synthetic Generation | [cite_start]Generated using age and employment status to maintain realism[cite: 80]. |
| `Monthly Payment Status` | Impute (Mode) | [cite_start]Retains most common behavior for categorical modeling[cite: 80]. |

---

## 📈 Task 2: Predictive Model Plan

[cite_start]A structured approach was developed to forecast customer delinquency, prioritizing accuracy and interpretability[cite: 20].

### Model Choice and Logic
* [cite_start]**Model:** **Gradient Boosting Classifier (e.g., XGBoost)**[cite: 4, 21].
* [cite_start]**Justification:** Selected for its high predictive accuracy and ability to model non-linear relationships and feature interactions, which is essential for complex financial risk prediction[cite: 21]. [cite_start]It also provides **feature importance scores** to support explainability and auditability[cite: 24].
* [cite_start]**Key Features:** `Missed_Payments`, `Credit_Utilization`, `Debt_to_Income_Ratio`, `Credit_Score`, and `Account_Tenure`[cite: 7, 14].

### Evaluation Strategy
[cite_start]The model's success is measured across performance and fairness[cite: 27].
* [cite_start]**Performance Metrics:** **AUC-ROC** (distinction ability), **F1 Score** (precision/recall balance), and Accuracy[cite: 29, 32, 33].
* [cite_start]**Fairness Checks:** **Demographic Parity** (equal positive prediction rates) and **Equal Opportunity** (consistent true positive rates across demographics)[cite: 35, 36].

---

## 🎯 Task 3: Business Recommendation

[cite_start]Insights were translated into a strategic, actionable recommendation for the Collections team, backed by the model's findings[cite: 155].

### Core Recommendation
* [cite_start]**Restated Insight:** High credit utilization (>0.6) is the strongest predictor of delinquency and affects a large customer segment[cite: 170].
* [cite_start]**SMART Goal:** **Launch a proactive engagement program** targeting customers with Credit\_Utilization > 0.6 to reduce delinquency risk[cite: 172, 174].
    * [cite_start]**Measurable:** Achieve a **15% reduction in delinquency** among this segment within one quarter[cite: 176].
* [cite_start]**Ethical Consideration:** The recommendation promotes **early intervention** rather than punitive action, supporting financial health and customer retention[cite: 194].

### Fairness & Mitigation
| Fairness Risk | Mitigation Strategy |
| :--- | :--- |
| [cite_start]Model may disproportionately flag unemployed/low-income customers[cite: 187]. | [cite_start]Apply **fairness-aware algorithms** and monitor disparate impact metrics[cite: 188]. |
| [cite_start]Historical bias in credit scoring could reinforce systemic disadvantages[cite: 189]. | [cite_start]**Reweight training data** and conduct regular fairness audits[cite: 190]. |

---

## 🤖 Task 4: AI-Driven Collections Strategy

[cite_start]A high-level concept for a scalable, autonomous, and responsible AI-powered collections system[cite: 106].

### End-to-End System Workflow
1.  [cite_start]**Data Ingestion:** Collect demographics, credit behavior, and real-time payment updates[cite: 109].
2.  [cite_start]**Risk Prediction:** ML model scores delinquency and segments customers (Low/Med/High)[cite: 110, 115, 117].
3.  [cite_start]**Targeted Actions:** Automated reminders, restructuring, and personalized repayment plans[cite: 111, 119].
4.  [cite_start]**Learning Loop:** Feedback + outcomes $\rightarrow$ model retraining & quarterly fairness audits[cite: 112, 121].

### Autonomy vs. Human Oversight
| [cite_start]Autonomous Activities [cite: 123] | [cite_start]Human Oversight Required [cite: 128] |
| :--- | :--- |
| [cite_start]Risk scoring via the predictive model [cite: 124] | [cite_start]Reviewing flagged edge cases [cite: 129] |
| [cite_start]Automated outreach (email/SMS nudges) [cite: 125] | [cite_start]Approving restructuring plans for high-risk cases [cite: 130] |
| [cite_start]Monitoring repayment behavior [cite: 126] | [cite_start]Conducting fairness and compliance audits [cite: 132] |

### Responsible AI Guardrails
* [cite_start]**Fairness Audits:** Regular bias checks across income, gender, and geography[cite: 134].
* [cite_start]**Explainability Tools:** Feature importance dashboards for internal teams and transparent logic for customer decisions[cite: 135].
* [cite_start]**Human-in-the-Loop:** Manual review of sensitive or disputed decisions[cite: 137].

---

## 🙋‍♀️ About Me

👤 **Satyam Kumar**  
📍 Data Science & Analytics Enthusiast  
📧 *satyamkv123@gmail.com*  
🔗 [LinkedIn](https://www.linkedin.com/in/satyam-kumar-5a229222b)  
