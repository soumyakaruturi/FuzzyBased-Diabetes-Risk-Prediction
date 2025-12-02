

# 🩺 Diabetes Risk Prediction using Machine Learning & Fuzzy Logic

A hybrid system that predicts diabetes risk using **Machine Learning** and enhances interpretability with a **Fuzzy Logic Expert System**, followed by **personalized diet recommendations** based on each patient's risk score.

---

## 🚀 Project Overview

This project combines two techniques to assess diabetes risk:

1. **Machine Learning Model** – Predicts whether a patient is diabetic or non-diabetic.
2. **Fuzzy Logic System (FIS)** – Generates a human-like risk score based on Glucose, BMI, and Age.
3. **Diet Recommendation Engine** – Provides calorie guidelines, carb limits, foods to prefer, and foods to avoid.

The final output is saved in a CSV file containing:
✔ Predicted Diabetes Status
✔ Fuzzy Risk Score
✔ Diet Risk Category
✔ Personalized Diet Advice

---

## 📂 Features

* Data preprocessing & cleaning
* Exploratory data analysis (EDA)
* ML classification model (Logistic/Random Forest/etc.)
* Fuzzy logic-based risk assessment
* Automatic diet recommendation generation
* CSV export with full results

---

## 🧠 Technologies Used

| Category      | Tools/Libraries        |
| ------------- | ---------------------- |
| Programming   | Python                 |
| ML            | scikit-learn           |
| Fuzzy Logic   | scikit-fuzzy           |
| Data Handling | pandas, numpy          |
| Visualization | matplotlib, seaborn    |
| Notebook      | Jupyter / Google Colab |

---

## 📊 Dataset

The project uses the **PIMA Indians Diabetes Dataset**, which includes attributes:

* Glucose
* Blood Pressure
* BMI
* Age
* Insulin
* Pregnancies
* Skin Thickness
* Diabetes Outcome (0/1)

---

## 🔧 Workflow

### **1️⃣ Data Preprocessing**

* Handling missing values
* Scaling numerical features
* Splitting into train-test sets
* Generating visualizations for correlation & distribution

### **2️⃣ Machine Learning Model**

* Model training
* Predictions
* Performance metrics:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * Confusion Matrix
  * ROC Curve

### **3️⃣ Fuzzy Logic Risk Prediction**

Fuzzy Inputs:

* Glucose (Low, Medium, High)
* BMI (Low, Medium, High)
* Age (Young, Middle, Old)

Fuzzy Output:

* **Risk Score (0–100)**

Fuzzy rules example:

> *If glucose is HIGH and BMI is HIGH → Risk is HIGH*

### **4️⃣ Diet Recommendation System**

Based on the fuzzy risk score:

* Low Risk
* Medium Risk
* High Risk

Each category includes:

* Daily calorie advice
* Carb guidelines
* Foods to prefer
* Foods to avoid

### **5️⃣ Export Output**

* Results saved to:

  ```
  fuzzy_diabetes_results.csv
  ```

---

## 📁 Output Example

The generated CSV contains:

| Glucose | BMI | Age | ML_Prediction | FIS_RiskScore | Diet_Risk_Class | Foods_Prefer | Foods_Avoid |
| ------- | --- | --- | ------------- | ------------- | --------------- | ------------ | ----------- |

---

## 🧪 How to Run the Project

### **Clone the Repo**

```bash
git clone https://github.com/your-username/diabetes-risk-prediction.git
cd diabetes-risk-prediction
```

### **Install Dependencies**

```bash
pip install -r requirements.txt
```

### **Run Notebook**

Open the `.ipynb` file in Jupyter or Google Colab.

---

## 📌 Future Enhancements

* Web or mobile app deployment
* Implement deep learning models
* Add more health parameters (cholesterol, HbA1c)
* Real-time API for hospital use

---

## 👥 Team Contributions

* **Member 1:** Data collection, preprocessing, EDA
* **Member 2:** Machine learning model development
* **Member 3:** Fuzzy logic system design
* **Member 4:** Diet recommendation engine + documentation


