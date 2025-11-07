[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/livingemoji/churn/HEAD?filepath=Predicting_Customer_Churn.ipynb)


[Open in Google Colab](https://colab.research.google.com/github/livingemoji/churn/blob/main/Predicting_Customer_Churn.ipynb)



# Customer Churn Prediction – Machine Learning Project

This project builds a machine learning model that predicts customer churn using the Telco Customer Churn dataset.  
Customer churn refers to customers who stop using a company's service. Predicting churn helps businesses take action to retain customers and reduce revenue loss.


##  Project Goal
To develop a model that can identify customers likely to leave (churn) based on:
- Contract information  
- Payment behavior  
- Internet service usage  
- Demographics  
- Monthly charges and tenure



##  Technologies Used
- **Python**
- **Pandas** – data manipulation and cleaning  
- **NumPy** – numeric operations  
- **Matplotlib / Seaborn** – visualization  
- **Scikit-learn** – machine learning

---

##  Steps Performed

###  1. Data Loading
We loaded the Telco dataset and inspected it using `head()`, `shape`, and summary statistics.

###  2. Data Preprocessing
- Removed unnecessary columns  
- Converted categorical data to numerical form using `OneHotEncoder`  
- Handled missing values  
- Split data into **training** and **testing sets**

###  3. Model Building
We used **Logistic Regression**, a classification model suitable for predicting binary outcomes:
- 1 = Customer will churn
- 0 = Customer will not churn

###  4. Model Evaluation
We used:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**
  - Precision
  - Recall
  - F1-score

These metrics show how well the model predicts churn.


##  Why Churn Prediction Matters
Churn costs companies a lot of money.  
Acquiring a new customer is **5–7 times more expensive** than keeping an existing one.

Businesses use churn prediction to:
- Identify at-risk customers
- Offer promotions or discounts
- Improve customer service
- Increase retention and reduce losses


##  Results
The model successfully:
- Learned customer behavior patterns
- Predicted future churn
- Identified which features influence churn the most  
  (e.g., Monthly charges, Contract type, Tenure)


##  Future Improvements
- Try advanced models (Random Forest, XGBoost)
- Use SMOTE to handle class imbalance
- Deploy model as a web app or API
- Create a dashboard for visual insights


##  How to Run
1. Install required libraries:
2. Run the notebook or `.py` script
3. Upload the dataset:
   

##  Output
The program will display:
- First rows of the dataset  
- Training vs test accuracy
- Confusion matrix
- Churn predictions



##  Author
Machine Learning Churn Prediction Project – Telco Dataset  
Designed for training, academic, and real-world business use by Alex wanyonyi.



