# ✈️ Optimizing Airline Loyalty & Retention Using Customer Analytics and Machine Learning

## 📌 Overview

Customer loyalty programs are essential for airlines to encourage repeat travel, increase customer lifetime value, and strengthen long-term customer relationships. However, customer inactivity, declining engagement, and churn can significantly impact loyalty program effectiveness and revenue generation.

This project combines **Customer Analytics, Business Intelligence, and Machine Learning** to identify valuable customer segments, predict churn risk, evaluate loyalty program performance, and recommend targeted retention strategies.

The solution integrates **SQL-based data preparation**, **Power BI dashboards**, and **Machine Learning models** to transform raw airline loyalty data into actionable business insights.

---

## 🎯 Business Problem

The airline sought to answer four critical business questions:

1. Which customers generate the highest value?
2. Which customers are most likely to churn?
3. How effective is the loyalty rewards program?
4. What actions can improve customer retention and reduce revenue loss?

Traditional reporting methods provided limited visibility into customer behavior, making proactive retention efforts difficult.

---

## 📊 Dataset

The project uses airline loyalty program data containing:

### Customer Information

* Loyalty Number
* Gender
* Marital Status
* Education
* Salary
* Province & City

### Loyalty Program Information

* Loyalty Card Type
* Enrollment & Cancellation Dates
* Customer Lifetime Value (CLV)

### Flight Activity Information

* Monthly Flights
* Distance Traveled
* Points Accumulated
* Points Redeemed

---

# ⚙️ Project Workflow

## 1. Data Cleaning & Preparation

Performed extensive preprocessing to ensure data quality:

* Handled missing values and created missing-value indicators
* Standardized column names and formats
* Corrected date and numeric data types
* Validated customer identifiers
* Checked data consistency across datasets

---

## 2. Data Integration

Merged customer profile and monthly flight activity datasets using:

`loyalty_number`

Created customer-level aggregated metrics:

* Total Flights
* Total Distance Traveled
* Total Points Accumulated
* Total Points Redeemed
* Months Recorded

---

## 3. Feature Engineering

Developed business-focused features to support analytics and modeling.

### Customer Metrics

* Points Balance
* Redemption Rate
* Average Flights per Customer
* Customer Lifetime Value (CLV)

### Segmentation Features

* CLV Band
* Activity Segment
* Customer Segment

### Churn Indicators

* Cancelled Flag
* Salary Missing Flag
* Consecutive Inactivity
* Flight Activity Trend

---

# 👥 Customer Segmentation

Customers were segmented using:

* Customer Lifetime Value (CLV)
* Flight Activity
* Points Balance
* Redemption Behavior

### Segments Identified

A total of **12 customer segments** were created.

Key segments include:

### High Value Active

* Highest CLV
* Frequent travelers
* Strong loyalty engagement

### High Value At Risk

* High revenue contribution
* Signs of declining engagement

### Medium Value Regular

* Largest customer segment
* Moderate activity
* Strong growth opportunity

### Medium Value Casual

* Moderate value
* Lower engagement
* Elevated churn risk

### Key Finding

The largest segment was **Medium Value Regular**, while **High Value Active** customers generated a disproportionately large share of customer value.

---

# 📈 Power BI Dashboard

An interactive Power BI dashboard was developed to provide decision-makers with a consolidated view of customer performance.

### Dashboard Modules

* Executive Overview
* Customer Segmentation Analysis
* Churn Risk Analysis
* Flight Activity Analysis
* Rewards & Points Analysis
* Retention Action Center

### Dashboard Features

* Dynamic filtering
* Customer drill-downs
* Loyalty card analysis
* Province-level insights
* KPI monitoring
* Segment comparison

---

# 🤖 Machine Learning Solution

## Objective

Predict customers likely to churn and classify them into risk categories.

---

## Models Developed

### Logistic Regression

Purpose:

* Baseline interpretable model

Advantages:

* Easy interpretation
* Fast training

---

### Random Forest

Purpose:

* Capture nonlinear customer behavior

Advantages:

* Handles complex interactions
* Improved predictive performance

---

### XGBoost

Purpose:

* Advanced gradient boosting model

Advantages:

* Strong predictive capability
* Better handling of feature interactions
* Superior generalization

---

## Model Selection

XGBoost was selected as the final model because it provided the strongest balance between:

* Accuracy
* Generalization
* Risk Identification Capability

---

# 🔍 Key Findings

## Customer Segmentation

* Identified **12 customer segments**
* Medium Value Regular emerged as the largest segment
* High Value Active customers generated the highest value

---

## Churn Analysis

### Loyalty Card Insights

* Nova cardholders exhibited the highest churn rates
* Star cardholders demonstrated stronger retention

### Geographic Insights

* Several provinces showed above-average churn concentrations

### Behavioral Insights

Top churn drivers identified:

1. Consecutive Inactivity
2. Declining Flight Activity
3. Reduced Loyalty Engagement

---

## Loyalty Program Insights

### Strong Customer Engagement

Customers accumulated more than:

**48 Million Loyalty Points**

demonstrating strong participation in the loyalty ecosystem.

### Low Redemption Behavior

Only a small percentage of available points were redeemed, indicating substantial unused loyalty value.

### Retention Link

Customers who:

* Redeem points
* Maintain higher point balances
* Engage actively in loyalty programs

showed significantly lower churn tendencies.

---

# 🚨 Results

## High-Risk Customers Identified

**165 customers** were classified as high-risk through churn prediction modeling.

---

## Revenue at Risk

Approximately:

**$776K Customer Lifetime Value**

was identified as being at risk due to potential customer churn.

---

## Customer Insights Generated

* 12 customer segments identified
* High-risk customers detected
* Revenue-at-risk quantified
* Churn drivers uncovered
* Loyalty engagement patterns analyzed

---

# 💡 Business Recommendations

## 1. Protect High-Value Customers

### Target

High Value At Risk segment

### Actions

* Personalized retention offers
* Bonus mile campaigns
* Dedicated customer outreach

### Expected Impact

Reduce revenue loss from high-risk customers.

---

## 2. Increase Reward Redemption

### Actions

* Redemption reminders
* Limited-time reward promotions
* Simplified redemption process

### Expected Impact

Increase customer engagement and loyalty.

---

## 3. Early Churn Intervention

### Actions

* Detect inactivity trends early
* Trigger personalized campaigns
* Offer flight incentives

### Expected Impact

Reduce churn before customers disengage completely.

---

# 📊 Business Impact

✅ Identified **165 high-risk customers**

✅ Estimated **~$776K revenue at risk**

✅ Created **12 actionable customer segments**

✅ Built a churn prediction framework using Logistic Regression, Random Forest, and XGBoost

✅ Developed executive Power BI dashboards for decision-makers

✅ Generated data-driven retention strategies

✅ Enabled proactive customer retention and loyalty optimization

---

# 🛠️ Tech Stack

### Data Processing

* SQL
* Python
* Pandas
* NumPy

### Machine Learning

* Scikit-Learn
* Logistic Regression
* Random Forest
* XGBoost

### Business Intelligence

* Power BI
* DAX
* Data Modeling

### Visualization

* Matplotlib
* Seaborn

### Development

* Jupyter Notebook
* Git
* GitHub

---
# 📌 Conclusion

This project demonstrates how Customer Analytics, Business Intelligence, and Machine Learning can be combined to improve airline loyalty management. By identifying high-value customers, predicting churn risk, quantifying revenue exposure, and recommending targeted retention actions, the solution enables proactive decision-making and stronger customer retention outcomes.

The framework can be extended to support real-time churn monitoring, personalized marketing campaigns, and enterprise-scale customer retention strategies.
