<img width="691" height="547" alt="image" src="https://github.com/user-attachments/assets/2d22a131-312e-4488-b172-2380cc481ff1" />
<img width="691" height="547" alt="image" src="https://github.com/user-attachments/assets/d2a4e1f8-4365-4993-948a-2b3475437e42" />
<img width="554" height="427" alt="image" src="https://github.com/user-attachments/assets/f2bbadcd-38da-4d8f-8362-48289a1610e8" />
<img width="554" height="427" alt="image" src="https://github.com/user-attachments/assets/4e58d3e3-ff9c-4350-8a95-2009e6a914ea" />
<img width="576" height="409" alt="image" src="https://github.com/user-attachments/assets/f8204a95-9b7e-4a66-ad8a-1719f7d3f09d" />
<img width="545" height="420" alt="image" src="https://github.com/user-attachments/assets/13c67533-fcb6-4a64-af8a-483129d8ba97" />
<img width="663" height="366" alt="image" src="https://github.com/user-attachments/assets/cebaf95c-db7e-44a1-8d00-fa3a32026f07" />
<img width="656" height="366" alt="image" src="https://github.com/user-attachments/assets/871174e1-faac-4f15-a2fe-7e7d379b8f71" />
<img width="1016" height="328" alt="image" src="https://github.com/user-attachments/assets/048465d4-26db-40cf-b622-97f85dd25b9c" />
# Fraud Detection System - Machine Learning Project

## 📌 Overview
This project builds a **real-time fraud detection system** for financial transactions.  
The goal is to **detect fraudulent transactions** while minimizing false positives.

## 🔧 Steps
1. Data Preprocessing
   - Handle missing values
   - Encode categorical features (Location, MerchantCategory)
   - Scale numerical features (Amount, Time, CardHolderAge)
   - Handle imbalance with SMOTE
2. Model Development
   - **Random Forest** (primary model)
   - **Logistic Regression** (comparison)
3. Evaluation
   - Metrics: Precision, Recall, F1-score, ROC-AUC
   - Logistic Regression performed better on fraud detection due to extreme imbalance.

## 📊 Results
- Random Forest: Recall = 0.00, ROC-AUC = 0.27  
- Logistic Regression: Recall = 0.40, ROC-AUC = 0.38  

➡️ Logistic Regression chosen as the best model (higher fraud recall).

## 🚀 Next Steps
- Hyperparameter tuning
- Try XGBoost/LightGBM
- Collect more balanced data

## 📂 Files
- `fraud_detection.ipynb` → Google Colab notebook with full pipeline
- `requirements.txt` → dependencies
