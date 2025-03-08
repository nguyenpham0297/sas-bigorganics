# SAS Viya - BigOrganics Business Case

## Overview
This project focuses on **Data Mining & Machine Learning** using **SAS Viya** to analyze and optimize predictive models for the **BigOrganics** business case. The goal is to find the best model using **Model Studio**, compare various machine learning techniques, and evaluate their performance. Additionally, the project includes **ROI analysis** to assess the financial impact of predictions.

## Project Structure
For a detailed understanding of the project, methodology, and results, refer to:
- **Project.docx** – Instructions and requirements from the professor.
- **Start_SSB_V4L3.5_DV_ML_en.pdf** – Contains exercise questions (page 43 and 73).
- **DSTI_Nguyen_SAS_Project.docx** – Full project report, including model selection, comparison, and conclusions.
- **Bayesian network - Target Gift Flag 2.xlsx** – ROI calculations for question 7 of the report.
- **DSTI_Nguyen_Report_page_43.pdf** – Solution for exercises on page 43.
- **DSTI_Nguyen_Report_page_73.pdf** – Solution for exercises on page 73.

## Model Selection & Comparison
The following models were tested and evaluated based on predictive performance:
1. **Decision Tree** – Youden Score: **0.1639**
2. **Bayesian Network** – Youden Score: **0.499** (Best Model)
3. **Gradient Boosting** – Youden Score: **0.3488**
4. **Forest Model** – Youden Score: **0.1563**
5. **Logistic Regression** – Youden Score: **0.1863**
6. **Neural Network** – Youden Score: **0**
7. **Support Vector Machine (SVM)** – Youden Score: **0.1783**

Based on the comparison, the **Bayesian Network model** performed best with a Youden score of **0.499**, making it the selected model for further analysis.

## ROI Analysis
Using the Bayesian Network model, an **ROI calculation** was conducted to determine the financial impact. The key findings include:
- The highest ROI is **$14,043.56**, achieved at the **30th percentile**.
- Selecting the **top 30% of potential donors** yields the best financial return.
- The ROI formula used:
  ```
  = 100000 * A2 / 100 * (-2 + 3 * F2 * 50 / 100)
  ```
  This formula considers:
  - **100,000 people in the PVA Table**
  - **50% likelihood of donation**
  - **$2 cost per solicitation**
  - **$3 profit margin per donation**
 
 ## Key Conclusions
- The **Bayesian Network model** provides the most accurate predictions.
- **30% of the population** should be targeted to maximize ROI.
- The findings demonstrate how **machine learning on SAS Viya** can optimize marketing campaigns for BigOrganics.
- Exercises on pages **43 and 73** further illustrate key business insights and predictive analytics methodologies.

## Exercise Solutions
### **Exercise Page 43**
The solution in **DSTI_Nguyen_Report_page_43.pdf** focuses on:
- **Product cost analysis** by facility continent and product line.
- **Unit capacity trends** over time.
- **Sales distribution** across different facility countries.
- **Customer satisfaction** trends across various regions and product brands.

### **Exercise Page 73**
The solution in **DSTI_Nguyen_Report_page_73.pdf** covers:
- **Frequency analysis of Target Gift Flag**.
- **Performance comparison of predictive models**.
- **Model evaluation metrics**, including confusion matrices, misclassification rates, and lift charts.
- **Feature importance ranking** for various machine learning models.

## Contributors
- **Phuc Nguyen Pham**
