# Meghana Foods – AI-Powered Restaurant Intelligence & Decision Support Platform

![Restaurant Banner](https://github.com/HackThePath/End-to-End-Projects-/blob/3081a7eedddb89c2669203057f801eb661c2cee4/Meghana-Foods-AI-Powered-Restaurant-Intelligence-And-Decision-Support-Platform/img.png)

## Project Overview

Meghana Foods operates multiple restaurant branches across Bengaluru and generates large volumes of operational, customer, menu, and review data every month.

The challenge is not collecting data.

The challenge is converting that data into actionable business decisions.

This project was developed to help restaurant owners identify operational risks, customer churn risks, revenue opportunities, menu performance issues, and future demand trends using Analytics, Machine Learning, NLP, Forecasting, and Business Intelligence.

The platform transforms raw restaurant data into executive-ready insights, recommendations, and strategic action plans.

---

## Business Problem

Restaurant owners often struggle to answer questions such as:

👉 Which branches are performing well and which require intervention?

👉 Which branches are at risk of losing customers?

👉 What operational issues are impacting performance?

👉 Which dishes should be promoted, improved, or removed?

👉 What are customers actually saying in reviews?

👉 How much revenue and demand can be expected in the future?

👉 What actions should management take to improve business performance?

This platform was built to answer those questions using data-driven decision making.

---

## Project Architecture


```text
Raw Business Data
        ↓
Data Quality Assessment
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Machine Learning Models
        ↓
Forecasting & Intelligence
        ↓
Business Recommendations
        ↓
Executive Dashboard & Reports
```

---

## Datasets Used

### 1. Branch Performance Dataset

This dataset contains operational and performance information for restaurant branches.

Columns:

```text
Branch_ID
Branch_Name
Region
Month
Orders
Revenue
Avg_Rating
Customer_Count
Repeat_Customers
New_Customers
Complaints
Delivery_Time_Min
Performance_Level
Branch_Status
Reason
```

Purpose:

👉 Analyse branch performance

👉 Identify operational issues

👉 Track customer behaviour

👉 Monitor revenue and service quality

---

### 2. Feature Engineered Dataset

This dataset was created from the Branch Performance Dataset and contains advanced business metrics used for analytics and machine learning.

Columns:

```text
Revenue_Per_Order
Revenue_Per_Customer
Customer_Loyalty_Score
Operational_Risk_Score
Repeat_Customer_Rate
Complaint_Rate
Service_Quality_Score
Customer_Acquisition_Score
Complaint_Per_1000_Orders
Revenue_Growth_Pct
Repeat_Customer_Growth_Pct
Churn_Risk
Operational_Risk
```

Purpose:

👉 Churn Risk Prediction

👉 Operational Risk Prediction

👉 Revenue Analysis

👉 Demand Forecasting

👉 Business Performance Evaluation

---

### 3. Menu Dataset

This dataset contains menu-level information used for Menu Intelligence.

Columns:

```text
Menu_ID
Dish_Name
Main_Category
Sub_Category
Bestseller
Price
Rating
Reviews
Calories
Protein_g
Carbs_g
Fat_g
Serves
Spice_Level
```

Purpose:

👉 Identify Hero Products

👉 Discover Hidden Growth Opportunities

👉 Detect Underperforming Dishes

👉 Generate Menu Optimization Strategies

---

### 4. Customer Review Dataset

This dataset contains customer feedback and sentiment information.

Columns:

```text
Review_ID
Rating
Review_Text
Sentiment
Complaint_Category
Churn_Risk
```

Purpose:

👉 Sentiment Analysis

👉 Complaint Detection

👉 Customer Satisfaction Analysis

👉 Customer Retention Insights

---

## Analytics & Intelligence Modules

### Data Quality Assessment

Checks:

• Missing Values

• Duplicate Records

• Invalid Ratings

• Invalid Delivery Times

• Revenue Outliers

Output:

👉 Data Quality Report

👉 Data Health Score

👉 Data Readiness Assessment

---

### Data Cleaning Engine

Performs:

• Missing Value Handling

• Duplicate Removal

• Branch Name Standardization

• Invalid Value Correction

• Revenue Outlier Treatment

Output:

👉 Clean Business Dataset

👉 Cleaning Summary Report

---

### Exploratory Data Analysis (EDA)

Analyses:

• Revenue Trends

• Customer Behaviour

• Ratings Distribution

• Complaints Analysis

• Branch Performance

Output:

👉 Business Insights

👉 KPI Reports

👉 Performance Trends

---

### Churn Risk Prediction

Model Used:

```text
Random Forest Classifier
```

Predicts:

• High Risk Branches

• Medium Risk Branches

• Low Risk Branches

Output:

👉 Branch-wise Churn Risk Status

👉 Recovery Recommendations

👉 Customer Retention Actions

---

### Operational Risk Prediction

Model Used:

```text
Random Forest Classifier
```

Identifies:

• Service Risks

• Delivery Risks

• Complaint Risks

• Operational Weaknesses

Output:

👉 Branch-wise Risk Assessment

👉 Operational Improvement Plan

---

### Revenue Forecasting

Forecasts:

• January Revenue

• Q1 Revenue

• Annual Revenue

Output:

👉 Growth Outlook

👉 Forecast Confidence

👉 Revenue Action Plan

---

### Demand Forecasting

Forecasts:

• Future Orders

• Capacity Requirements

• Inventory Planning

• Staffing Requirements

Output:

👉 Demand Forecast Report

👉 Operational Planning Strategy

---

### Customer Review Intelligence

Uses NLP-based sentiment analysis to identify:

• Customer Satisfaction Drivers

• Complaint Themes

• Service Issues

• Customer Expectations

Output:

👉 Customer Experience Report

👉 Retention Recommendations

---

### Menu Intelligence

Identifies:

• Hero Products

• Hidden Opportunity Products

• Growth Items

• Underperforming Items

Output:

👉 Menu Optimization Report

👉 Marketing Recommendations

👉 Revenue Growth Opportunities

---

## Technologies Used

```text
Python
Pandas
Scikit-Learn
Natural Language Processing (NLP)
Random Forest
Matplotlib
Seaborn
Streamlit
Machine Learning
Forecasting Techniques
Business Analytics
```

---

## Key Project Highlights

👉 Built an end-to-end Restaurant Intelligence Platform integrating Analytics, Machine Learning, NLP, Forecasting, and Executive Decision Support.

👉 Developed Random Forest-based Churn Risk and Operational Risk models with branch-level business recommendations.

👉 Implemented NLP-driven Customer Review Intelligence to uncover customer sentiment, complaint themes, and service improvement opportunities.

👉 Designed Revenue Forecasting and Demand Forecasting modules supporting inventory planning, staffing decisions, and revenue growth strategies.

👉 Built Menu Intelligence capabilities to identify hero products, hidden growth opportunities, and menu optimization strategies.

👉 Deployed an interactive Streamlit application delivering automated insights, forecasts, recommendations, dashboards, and downloadable business reports.

