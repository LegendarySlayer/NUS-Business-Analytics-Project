# Health Insurance Cross-Sell Prediction & Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Orange-F97321?style=for-the-badge&logo=orange&logoColor=white" alt="Orange ML">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
</p>

This project, developed as part of a group collaboration at the National University of Singapore (NUS), predicts whether existing health insurance policyholders are likely to purchase vehicle insurance. It leverages machine learning models built in **Orange** and visualizes key business insights using interactive dashboards in **Power BI**.

---

## 🧠 Project Objective

To develop a data-driven strategy for an insurance company to effectively cross-sell vehicle insurance to its existing health insurance customers, thereby increasing revenue and customer retention.

---

## 📊 Sample Insights & Outcomes

-   **📈 Predicted Customer Churn:** Utilized decision tree models in Orange to identify customers at high risk of churning.
-   **🧠 Customer Segmentation:** Performed k-means clustering to group customers into distinct behavioral segments for targeted marketing.
-   **💬 Identified Sales Trends:** Uncovered key sales patterns across different regions and demographic segments.
-   **📌 Dynamic Dashboards:** Built region-wise revenue dashboards in Power BI with dynamic filters and slicers to explore data interactively.
-   **🏆 Final Presentation:** The project culminated in a team presentation to NUS faculty and industry mentors, covering the entire lifecycle from problem statement to business recommendations.

---

## 🔧 Tools & Technologies

-   **Machine Learning:** Orange (Visual ML Tool)
-   **Data Visualization:** Power BI
-   **Core Concepts:** Exploratory Data Analysis (EDA), Classification, Clustering, Feature Engineering
-   **Dataset:** CSV files for training and testing

---

## 🧪 Machine Learning Workflow

The end-to-end ML pipeline was designed and executed in Orange:

1.  **Load Data**: Imported the training dataset (`training_data.csv`).
2.  **Preprocessing**: Selected relevant features and defined the target variable (`Response`) using the Edit Domain widget.
3.  **Sampling**: Split the data into training and testing sets using the Data Sampler.
4.  **Model Training**: Trained and compared three different classification models:
    -   Logistic Regression
    -   Naive Bayes
    -   k-Nearest Neighbors (kNN)
5.  **Evaluation**: Used the Test & Score widget to evaluate model performance based on metrics like Accuracy, Precision, and Recall.
6.  **Prediction**: Deployed the best-performing model to predict the likelihood of cross-selling on new or unseen data.

---

## 📌 My Contributions

As a member of the project team, my primary contributions included:
-   Creating multiple Power BI dashboards with advanced filters, slicers, and DAX metrics for in-depth analysis.
-   Building and evaluating ML pipelines in Orange, specifically focusing on decision trees and k-means clustering.
-   Contributing to the final presentation design, business interpretation of results, and overall group strategy.
-   Actively participating in the final presentation delivered to NUS faculty and industry mentors.

---

## 📁 Project Structure

📦 Cross-Sell-Prediction-NUS/
┣ 📂 assets/
┃ ┣ 📜 dashboard-sample.png
┃ ┗ 📜 orange-flow.png
┣ 📜 training_data.csv
┣ 📜 testing_data.csv
┣ 📜 AIMLBAproject.ows      # Orange workflow file
┣ 📜 PowerBI_Report.pbix    # PowerBI visualization file
┗ 📜 README.md


---

## 🏁 How to Use

1.  **Orange:** Open `AIMLBAproject.ows` in the Orange Data Mining tool. Ensure the File widgets are correctly linked to the `training_data.csv` and `testing_data.csv` files.
2.  **Power BI:** Open `PowerBI_Report.pbix` in PowerBI Desktop to view the interactive dashboards and analysis.

---

## 👥 Collaborators

This was a group project. My personal repository version is hosted here.
-   **GitHub:** [@Ashutosh Jha](https://github.com/LegendarySlayer)

---

> **Note:** This repository contains my personal contribution files and presentation materials. Raw data and some project files have been anonymized or excluded to maintain confidentiality.
