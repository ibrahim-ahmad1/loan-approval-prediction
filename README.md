# Loan Approval Prediction

## Project Overview
This project predicts whether a loan application will be **approved or rejected** using Machine Learning.  
The model is trained on a **Kaggle loan dataset** and achieves an **accuracy of 90%**.

---

## Objective
To build an efficient and reliable machine learning model that helps financial institutions make faster and data-driven loan approval decisions.

---

## Dataset
- **Source:** Kaggle  
- **Format:** CSV  
- **Type:** Structured data  
- **Key Features:**
  - Applicant Income  
  - Coapplicant Income  
  - Loan Amount  
  - Loan Amount Term  
  - Credit History  
  - Gender, Marital Status, Education, Property Area  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Data Preprocessing
- Handled missing values  
- Applied **Label Encoding** for categorical features  
- Applied **Standard Scaler** to normalize numerical features  

---

## Machine Learning Model
- **Algorithm:** Logistic Regression  
- **Problem Type:** Binary Classification  
- **Accuracy Achieved:** **90%**

---

## Workflow
1. Load Kaggle dataset  
2. Clean and preprocess the data  
3. Encode categorical variables using Label Encoder  
4. Scale features using Standard Scaler  
5. Train Logistic Regression model  
6. Evaluate model performance  
7. Predict loan approval status  

---

## Model Output
- `1` → Loan Approved  
- `0` → Loan Rejected  

---

## Results
The Logistic Regression model achieved **90% accuracy**, demonstrating strong performance in predicting loan approval outcomes based on applicant information.

---

## Conclusion
This project demonstrates a complete end-to-end machine learning pipeline, from data preprocessing to model evaluation, using Logistic Regression for accurate loan approval prediction.

---

## Future Scope
- Experiment with advanced models like Random Forest or XGBoost  
- Perform hyperparameter tuning to further improve accuracy  
- Deploy the model using Flask or Streamlit  

---

## Project Structure
