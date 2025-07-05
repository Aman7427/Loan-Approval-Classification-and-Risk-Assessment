# Predictive Analytics for Lending Decisions 🏦📊

This project applies machine learning techniques to predict **loan approval status** and assess **applicant risk scores** using a real-world financial dataset. Developed as part of the **Analytics Lab (MSL71440)** at **IIT Jodhpur**, this work demonstrates end-to-end modeling from **data preprocessing** to **model training, evaluation, and interpretation**.

## 📁 Project Structure

- **Data Overview**: Includes demographic, financial, credit, and loan application details.
- **EDA & Visualization**: Analyzed the impact of features like employment, education, marital status, and loan purpose on approvals.
- **Preprocessing Pipeline**: Built using `scikit-learn`’s `Pipeline` and `ColumnTransformer` with standard scaling and one-hot encoding.
- **Model Training**: Trained classification and regression models using:
  - `Logistic Regression`, `Random Forest`, `Decision Tree`, `KNN`, `Naive Bayes`, `XGBoost`
  - Evaluation metrics: **Accuracy**, **Precision**, **Recall**, **F1-Score**, **ROC-AUC**
- **Model Evaluation**:
  - **Logistic Regression** achieved **99.98% accuracy** with perfect **100% recall**.
  - For risk score prediction, **XGBoost Regressor** achieved an **R² = 0.9743** with low **MSE = 0.0046**.

## 🛠️ Tools & Libraries

- **Python**, **NumPy**, **Pandas**
- **Matplotlib**, **Seaborn** (for data visualization)
- **Scikit-learn**, **XGBoost**
- **Jupyter Notebook**

## 🔍 Key Insights

- Education, employment, and loan purpose strongly influence approval decisions.
- Classification models with high precision and recall (LogReg, RF) are ideal for minimizing financial risk.
- Feature engineering and robust preprocessing significantly improved predictive performance.

## 📈 Performance Summary

| Model                | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 99.98%   | 99.90%    | 100.00%| 99.95%   |
| Random Forest       | 99.10%   | 98.52%    | 97.94% | 98.22%   |
| Decision Tree       | 99.00%   | 98.13%    | 97.94% | 98.03%   |

| Regressor              | Validation R² | Validation MSE |
|------------------------|---------------|----------------|
| XGBoost Regressor      | 0.9743        | 0.0046         |
| Random Forest Regressor| 0.9715        | 0.0051         |

## 👨‍💻 Contributors

- Aman Kanshotia (M21MA201)  
- Sahil Sharma (M21MA210)  
- Abhas Malguri (M23MA1001)  
**Program:** M.Sc - M.Tech (Data and Computational Sciences)  
**Department:** Mathematics, IIT Jodhpur

## 📄 License

This project is for educational use as part of coursework and is not intended for commercial deployment.

---

