# AI Customer Churn & Retention System

## Overview

An AI-assisted customer churn analysis and retention strategy project developed using Power BI, Power Query, DAX, and generative AI.

The project analyzes telecom customer data to identify customer segments associated with higher churn, understand potential business drivers, create a transparent rule-based churn risk score, and translate analytical findings into practical retention strategies.

## Business Problem

A telecom company is experiencing customer churn and wants to understand:

* Which customer segments show higher churn?
* Which contract and service patterns are associated with churn?
* Does customer tenure relate to churn?
* How do monthly charges relate to churn?
* Which customers fall into higher-risk segments?
* What retention actions could be tested?

## Objective

Identify important patterns associated with customer churn and develop an AI-assisted customer retention strategy supported by data analysis.

## Tools Used

* Kaggle — Dataset
* Microsoft Excel — Initial data inspection
* Power BI — Data analysis and visualization
* Power Query — Data cleaning and transformation
* DAX — KPI calculations and risk scoring
* ChatGPT — AI-assisted business interpretation and retention recommendations
* GitHub — Project documentation and version control

## Project Workflow

```text
Kaggle Dataset
      ↓
Data Inspection
      ↓
Power Query Cleaning
      ↓
Data Transformation
      ↓
DAX Measures
      ↓
Power BI Analysis
      ↓
Rule-Based Churn Risk Score
      ↓
AI-Assisted Business Insights
      ↓
Retention Strategy
```

## Data Preparation

The dataset was prepared using Power Query.

Key preparation steps included:

* Duplicate customer checks
* Missing-value investigation
* Data type correction
* Customer tenure grouping
* Monthly charge categorization
* Business-friendly churn categories

## Key KPIs

The Power BI dashboard tracks:

* Total Customers
* Churned Customers
* Churn Rate
* Average Monthly Charges
* Total Revenue
* Revenue associated with churned customers
* Customer Risk Category

## Dashboard

### Executive Overview

![Executive Dashboard](screenshots/executive_dashboard.png)

### Churn Analysis

![Churn Analysis](screenshots/churn_analysis.png)

### AI Retention Strategy

![Retention Recommendations](screenshots/retention_recommendations.png)

## Churn Risk Scoring

A transparent rule-based scoring framework was created to segment customers into:

* Low Risk
* Medium Risk
* High Risk

The score considers selected customer characteristics such as:

* Contract type
* Tenure
* Monthly charges
* Technical support
* Online security

This is a business-rule scoring framework and is not presented as a machine-learning prediction model.

## AI-Assisted Analysis

Generative AI was used to interpret the actual Power BI findings and convert observed data patterns into potential business hypotheses and retention strategies.

The analysis was designed to distinguish:

**Observed pattern → Business interpretation → Recommended action → KPI**

## Business Recommendations

Potential retention strategies include:

1. Strengthening onboarding for short-tenure customers.
2. Testing contract-conversion incentives for month-to-month customers.
3. Investigating value perceptions among higher-charge customer segments.
4. Offering proactive support to relevant customer segments.
5. Monitoring churn and retention KPIs after each intervention.

Recommendations should be validated through controlled business experiments before being treated as proven causal solutions.

## Project Outcome

This project demonstrates the ability to:

* Translate a business problem into analytical questions.
* Clean and transform business data.
* Build interactive Power BI dashboards.
* Develop business KPIs using DAX.
* Segment customers using transparent business rules.
* Interpret data from a business perspective.
* Use generative AI for structured business analysis.
* Convert analytical findings into actionable retention strategies.

## Repository Structure

```text
AI-Customer-Churn-Retention-System/
│
├── README.md
├── dataset/
├── powerbi/
├── documentation/
├── screenshots/
└── report/
```

## Disclaimer

The risk score is a rule-based analytical framework created for portfolio and demonstration purposes. It is not a validated predictive machine-learning model and should not be used for real customer decisions without further testing and validation.
