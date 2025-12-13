# Multi-Disease Patient Readmission Prediction Using Machine Learning

## Project Description

Hospital readmissions place a significant burden on healthcare systems by increasing costs, resource usage, and patient risk. This project focuses on predicting **30-day patient readmission risk** across multiple diseases using **machine learning models** and deploying the solution using **cloud-based infrastructure**.

By analyzing patient demographics, clinical indicators, and treatment history, the system identifies high-risk patients before discharge. This enables healthcare providers to take preventive actions, improve patient outcomes, and optimize hospital resource planning.

## Objectives

* Predict hospital readmission risk for patients with multiple diseases
* Compare multiple machine learning models for performance
* Build a scalable backend using cloud technologies
* Provide an efficient and reusable ML pipeline for healthcare analytics

## Technologies Used

###  Programming & ML

* Python
* NumPy
* Pandas
* Scikit-learn
* XGBoost (if applicable)
* Matplotlib / Seaborn

###  Backend & Deployment

* Flask
* REST API
* Cloud Platform (AWS / Azure / GCP)
* Joblib (model persistence)

###  Tools

* Jupyter Notebook
* Git & GitHub

## Dataset Description

The dataset contains anonymized hospital records including:

* Patient demographics
* Clinical measurements
* Hospital stay details
* Treatment history
* Readmission label (target variable)

### Target Variable

* **Readmitted**: Indicates whether a patient was readmitted within 30 days

##  Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Feature scaling

2. **Exploratory Data Analysis**

   * Distribution analysis
   * Correlation analysis
   * Feature importance exploration

3. **Model Training**

   * Logistic Regression
   * Random Forest
   * Gradient Boosting / XGBoost

4. **Model Evaluation**

   * Accuracy
   * Precision
   * Recall
   * F1-Score
   * Confusion Matrix

5. **Model Deployment**

   * Flask REST API
   * Cloud hosting for scalability
  
##  How to Run the Project

###  Step 1: Clone the Repository

```bash
git clone https://github.com/sahithi7810/Multi-Disease-Patient-Readmission-Prediction-Using-ML-and-Cloud.git
cd Multi-Disease-Patient-Readmission-Prediction-Using-ML-and-Cloud
```

###  Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

###  Step 3: Run the Application

```bash
python app.py
```

The API will start locally and can be accessed through browser or Postman.

---

##  Model Performance (Sample)

Multiple machine learning models were evaluated to identify the most reliable approach for predicting patient readmission across different diseases. After comparative analysis, Random Forest was selected as the final model because it consistently delivered higher accuracy and better generalization across all disease categories.

Random Forest performed particularly well due to its ability to handle non-linear relationships, feature interactions, and imbalanced healthcare data. By combining predictions from multiple decision trees, the model reduced overfitting and produced stable results for diverse patient conditions.

As a result, Random Forest proved to be the most effective model for multi-disease readmission prediction in this project.


##  Cloud Deployment

* Model hosted using a Flask backend
* Cloud platform enables scalability and remote access
* Predictions can be integrated with hospital systems or dashboards

##  Key Features

* Multi-disease readmission prediction
* ML model comparison and evaluation
* Cloud-ready architecture
* Modular and reusable codebase
* Secure model storage and loading

##  Future Enhancements

* Integration with real-time hospital data
* Deep learning models (LSTM, ANN)
* Patient-doctor dashboard UI
* Automated retraining pipeline
* Explainable AI (SHAP, LIME)

##  Use Case

* Hospitals and clinics
* Healthcare analytics teams
* Academic research projects
* Predictive healthcare systems
