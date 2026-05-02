# Predicting Fit Success for Custom Footwear using Machine Learning

## Overview
This project aims to predict whether a shoe will fit a customer successfully before production using simulated foot scan data.

The goal is to demonstrate how data analytics can support decision-making in custom footwear manufacturing systems.

---

## Problem Statement
In 3D-printed or custom footwear, predicting fit before manufacturing is critical. Poor fit can lead to customer dissatisfaction and wasted production resources.

This project explores how machine learning can be used to estimate the likelihood of a successful fit.

---

## Approach
- Created a synthetic dataset representing foot measurements and product features  
- Performed Exploratory Data Analysis (EDA) to identify key factors affecting fit  
- Built a Random Forest classification model  
- Compared performance with Logistic Regression  
- Introduced a **Fit Risk Score** to convert predictions into actionable decisions  

---

## Key Insights
- Higher asymmetry reduces fit success  
- Increased pressure points are associated with poor comfort  
- Moderate arch height improves fit outcomes  
- Foot structure has a stronger impact than design type  

---

## Model Application
The model generates a **Fit Risk Score**:

- Above 80% → Safe to print  
- 50% to 80% → Needs adjustment  
- Below 50% → High risk, review before production  

This enables data-driven decision-making before manufacturing.

---

## Business Impact
- Reduces failed prints and material waste  
- Improves customer satisfaction  
- Supports scalable on-demand manufacturing  
- Bridges the gap between digital design and physical product performance  

---

## Files
- `predicting_fit_success_ml.ipynb` → Full analysis and model  
- `foot_data.csv` → Simulated dataset  

---

## Conclusion
This project demonstrates how machine learning can be applied to predict product performance and support smarter manufacturing decisions in custom footwear systems.
