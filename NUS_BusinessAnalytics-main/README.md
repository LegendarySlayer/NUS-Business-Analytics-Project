# Health Insurance Cross-Sell Prediction (Orange ML + PowerBI Project)

This project predicts whether health insurance policyholders are likely to buy vehicle insurance using machine learning models in Orange and visualizes results in PowerBI.

---

## 🧠 Project Objective

To help an insurance company identify customers likely to purchase vehicle insurance based on existing health insurance data.

---

## 🔧 Tools Used

- **Orange** (Visual Machine Learning Tool)
- **PowerBI** (Data Visualization)
- **CSV Dataset** (training and testing)

---

## 📁 Project Structure

```
📦Cross-Sell-Prediction-Orange
 ┣ 📄 training_data.csv
 ┣ 📄 testing_data.csv (optional)
 ┣ 📄 AIMLBAproject.ows        # Orange workflow file
 ┣ 📄 PowerBI_Report.pbix      # PowerBI visualization file
 ┗ 📄 README.md
```

---

## 🧪 ML Models Used

- Logistic Regression
- Naive Bayes
- k-Nearest Neighbors (kNN)

---

## 🔍 Orange Workflow

1. **Load Data**: Import training data.
2. **Preprocess**:
   - Select columns
   - Set target (`Response`) in Edit Domain
3. **Sample**: Use Data Sampler for splitting
4. **Train Models**: Logistic Regression, Naive Bayes, kNN
5. **Evaluate**: Use Test & Score to compare model metrics
6. **Save & Load Models** for later use
7. **Predict**: Run test data through saved model

---

## 📊 PowerBI Report

PowerBI is used to visualize:
- Distribution of target classes (`Response`)
- Model prediction outputs
- Feature importance (if exported)
- Probability of cross-sell based on demographic segments

---

## 🏁 How to Use

1. Open `AIMLBAproject.ows` in Orange
2. Ensure training and test datasets are connected
3. Open `PowerBI_Report.pbix` in PowerBI Desktop to view visuals
4. Make sure prediction CSV output is imported into PowerBI for live visuals

---

## 🎯 Target Variable

- **`Response`**:
  - `1` – Likely to purchase vehicle insurance
  - `0` – Not interested

---

## 🧑‍💻 Author

Shrey Yadav  
B.Tech CSE, KIIT University  
GitHub: [@Hayzzy](https://github.com/Hayzzy)
