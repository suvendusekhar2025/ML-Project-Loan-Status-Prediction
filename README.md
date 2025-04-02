# ML-Project-Loan-Status-Prediction
Here's a well-structured description for the project:  

---

**Loan Status Prediction Using Machine Learning**  

This project focuses on predicting loan eligibility based on a given dataset using machine learning techniques. The dataset consists of **614 rows and 13 columns** stored in a CSV file. The objective is to classify loan applicants as either **eligible** or **not eligible** for a loan based on various financial and demographic features.  

### **Technologies and Dependencies Used:**  
- **Python Libraries:** NumPy, Pandas (for data manipulation and preprocessing), Seaborn (for data visualization).  
- **Data Preprocessing:**  
  - All categorical/text labels were converted into numerical labels using the **replace** command (Label Encoding).  
  - Missing values were handled, and relevant transformations were applied to prepare the data for model training.  
- **Model Selection:**  
  - Used **train-test split** from the (sklearn.model_selection) module to divide the dataset into training and testing sets.  
  - Implemented **Support Vector Machine (SVM) with a linear kernel** (Support Vector Classifier - SVC) for classification.  
- **Evaluation Metrics:**  
  - **Accuracy Score:**  
    - Training Accuracy: **79.8%**  
    - Testing Accuracy: **83.33%**  
  - Model performance was evaluated using (accuracy_score from )(sklearn.metrics).  

### **Conclusion:**  
The model successfully predicts loan eligibility with a high accuracy of **83.33%** on test data. The approach of **Label Encoding** helped in handling categorical variables effectively, and the **SVM classifier** with a linear kernel proved to be a suitable choice for classification. Further improvements can be made by experimenting with different feature engineering techniques and hyperparameter tuning.  

---
