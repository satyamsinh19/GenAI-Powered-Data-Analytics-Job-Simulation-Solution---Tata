<h1 align="center"> GenAI Powered Data Analytics Job Simulation Solution Tata (Forage)</h1>
<h1 align="center">Geldium Loan Delinquency Prediction & Ethical AI Collections System 🚀</h1>

A comprehensive data science project outlining a predictive model for loan delinquency and proposing an ethical, AI-driven strategy for customer collections management.

---

## 💡 Overview and Business Context

This project was developed to provide **Geldium's Collections Team** with advanced insights and an automated system to proactively manage financial risk. [cite_start]It moves beyond traditional methods by integrating **Exploratory Data Analysis (EDA)**, **Machine Learning (ML) prediction**, and **Responsible AI governance** into a scalable collections workflow.

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

The initial analysis assessed data quality and identified early risk indicators to prepare the dataset for modeling.

### Key Findings & Risk Indicators
* **High Credit Utilization** (>$0.6$) indicates financial overextension and high repayment stress.
* **Missed\ Payments** $\ge 4$ is a direct behavioral signal of high delinquency risk.
* **Debt\_to\_Income\_Ratio** $> 0.4$ suggests poor affordability and high default probability.
* **Low Credit\_Score** $(<500)$ strongly predicts delinquency.

### Data Quality & Treatment
Data cleaning was required to address inconsistencies like unrealistic Credit\_Utilization values and inconsistent categorical labels.

| Variable | Treatment Method | Justification |
| :--- | :--- | :--- |
| `Credit_Utilization` | Impute (Median) | Reduces impact of outliers and preserves distribution. |
| `Income` | Synthetic Generation | Generated using age and employment status to maintain realism. |
| `Monthly Payment Status` | Impute (Mode) | Retains most common behavior for categorical modeling. |

---

## 📈 Task 2: Predictive Model Plan

A structured approach was developed to forecast customer delinquency, prioritizing accuracy and interpretability.

### Model Choice and Logic
* **Model:** **Gradient Boosting Classifier (e.g., XGBoost)**.
* **Justification:** Selected for its high predictive accuracy and ability to model non-linear relationships and feature interactions, which is essential for complex financial risk prediction. It also provides **feature importance scores** to support explainability and auditability.
* **Key Features:** `Missed_Payments`, `Credit_Utilization`, `Debt_to_Income_Ratio`, `Credit_Score`, and `Account_Tenure'.

### Evaluation Strategy
The model's success is measured across performance and fairness.
* **Performance Metrics:** **AUC-ROC** (distinction ability), **F1 Score** (precision/recall balance), and Accuracy.
* **Fairness Checks:** **Demographic Parity** (equal positive prediction rates) and **Equal Opportunity** (consistent true positive rates across demographics).

---

## 🎯 Task 3: Business Recommendation

Insights were translated into a strategic, actionable recommendation for the Collections team, backed by the model's findings.

### Core Recommendation
* **Restated Insight:** High credit utilization (>0.6) is the strongest predictor of delinquency and affects a large customer segment.
* **SMART Goal:** **Launch a proactive engagement program** targeting customers with Credit\_Utilization > 0.6 to reduce delinquency risk.
    * **Measurable:** Achieve a **15% reduction in delinquency** among this segment within one quarter.
* **Ethical Consideration:** The recommendation promotes **early intervention** rather than punitive action, supporting financial health and customer retention.

### Fairness & Mitigation
| Fairness Risk | Mitigation Strategy |
| :--- | :--- |
| Model may disproportionately flag unemployed/low-income customers. | Apply **fairness-aware algorithms** and monitor disparate impact metrics. |
| Historical bias in credit scoring could reinforce systemic disadvantages. | **Reweight training data** and conduct regular fairness audits. |

---

## 🤖 Task 4: AI-Driven Collections Strategy

A high-level concept for a scalable, autonomous, and responsible AI-powered collections system.

### End-to-End System Workflow
1.  **Data Ingestion:** Collect demographics, credit behavior, and real-time payment updates.
2.  **Risk Prediction:** ML model scores delinquency and segments customers (Low/Med/High).
3.  **Targeted Actions:** Automated reminders, restructuring, and personalized repayment plans.
4.  **Learning Loop:** Feedback + outcomes $\rightarrow$ model retraining & quarterly fairness audits.

### Autonomy vs. Human Oversight
| Autonomous Activities  | Human Oversight Required  |
| :--- | :--- |
| Risk scoring via the predictive model  | Reviewing flagged edge cases  |
| Automated outreach (email/SMS nudges)  | Approving restructuring plans for high-risk cases  |
| Monitoring repayment behavior  | Conducting fairness and compliance audits  |

### Responsible AI Guardrails
* **Fairness Audits:** Regular bias checks across income, gender, and geography.
* **Explainability Tools:** Feature importance dashboards for internal teams and transparent logic for customer decisions.
* **Human-in-the-Loop:** Manual review of sensitive or disputed decisions.

---

## 🙋‍♀️ About Me

👤 **Satyam Kumar**  
📍 Data Science & Analytics Enthusiast  
📧 *satyamkv123@gmail.com*  
🔗 [LinkedIn](https://www.linkedin.com/in/satyam-kumar-5a229222b)  
