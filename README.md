# Heart Disease Prediction

## 📌 Overview
This project focuses on predicting heart disease using machine learning techniques. The dataset was sourced from **Kaggle** and underwent thorough preprocessing before applying various models. The final model, **XGBoost**, achieved a **cross-validation score of 99%** on accuracy.

---

## 📂 Dataset
- **Source**: Kaggle
- **Type**: Structured medical data
- **Target Variable**: Presence of heart disease (Binary Classification: 0 = No Disease, 1 = Disease)

---

## 🛠 Data Preprocessing
1. **Exploratory Data Analysis (EDA)**:
   - Identified missing values and inconsistencies.
   - Checked class distribution and feature importance.

2. **Feature Encoding**:
   - Converted **categorical variables** to **numerical** using **OneHotEncoder** and **LabelEncoder**.

3. **Feature Scaling**:
   - Applied **StandardScaler** to ensure all features were on a similar scale.

---

## 📊 Model Training & Evaluation
### **1️⃣ Logistic Regression**
- **Accuracy**: 0.20
- Initial model with poor performance.

### **2️⃣ Polynomial Logistic Regression (Degree = 3)**
- **Accuracy**: 0.91
- Improvement by adding polynomial features.

### **3️⃣ Decision Tree Classifier**
- **Accuracy**: 0.88
- Performed well but prone to overfitting.

### **4️⃣ Random Forest Classifier (with GridSearchCV)**
- **Accuracy**: 0.98
- Used **GridSearchCV** to tune hyperparameters.

### **5️⃣ XGBoost Classifier (Final Model)**
- **Cross-Validation Score**: 0.99 (Accuracy)
- Best-performing model.
- Tuned hyperparameters using **GridSearchCV**.

---

## 🚀 Conclusion
After testing multiple models, **XGBoost** was selected as the final model due to its superior accuracy and generalization performance. This model can be further improved with feature engineering and hyperparameter tuning.

---

## 📌 How to Run the Project
1. Clone the repository:
   ```sh
[ [ git clone https://github.com/your-username/your-repo.git](https://github.com/adityajoshi1362/Data-Analysis-and-EDA)]
   ```

2. Train & Evaluate models using the provided code.

---

## 📜 License
This project is open-source and available under the **MIT License**.

---

## 🔗 References
- [Kaggle Dataset](https://www.kaggle.com/)
- [Scikit-Learn Documentation](https://scikit-learn.org/)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)

