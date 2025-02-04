# Big Data Analytics Final Project - Property Assessment for Cook County, Illinois
## **Overview**
This project aims to develop a predictive model for assessing residential property values in **Cook County, Illinois**. Using historical property sales data and various property features, I applied  **machine learning techniques in R** to estimate property values and minimize prediction error.

## **Project Objectives**
- Predict the fair market value of **10,000 properties** based on given property features.
- Utilize **historical property sales data (50,000 records)** to train predictive models.
- Evaluate the model’s performance using **Mean Squared Error (MSE)**.
- Deliver accurate property assessments to aid the **Cook County Assessor’s Office (CCAO)** in valuation tasks.

## **Dataset Description**
The project involves the following datasets:
1. **predict_property_data.csv** – 10,000 properties requiring value prediction.
2. **historic_property_data.csv** – 50,000 properties with known sale prices for model training.
3. **codebook.csv** – Description of dataset variables.

## **Methodology**
1. **Data Preprocessing**
   - Handling missing values and categorical variables.
   - Exploratory Data Analysis (EDA) for feature selection.
   
2. **Model Selection & Training**
   - Using regression and machine learning models covered in class.
   - Feature engineering for improved predictions.
   
3. **Performance Evaluation**
   - Computing **Mean Squared Error (MSE)** to measure prediction accuracy.
   - Comparing results against actual property sale prices.

## **Project Files**
- 📄 `README.md` – This document.
- 📜 `Project_Report.pdf` – Executive summary detailing methodology and results.
- 📂 `assessed_value.csv` – Final property assessment file (contains `pid` and predicted `assessed_value`).
- 📜 `Cook_county_MSE.ipynb` – R script for data preprocessing, modeling, and predictions.

