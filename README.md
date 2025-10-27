# Financial Transaction Fraud Analytics
This project focuses on analyzing financial transaction data to detect fraudulent activities using machine learning techniques.
The dataset consists of approximately 6.3 million transactions, obtained from Kaggle: Fraud Detection Dataset.




# About the Dataset

->Source: Kaggle – https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset

->Records: 6,362,620
Features:

->type – Transaction type (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER)

->amount – Transaction amount

->oldbalanceOrg – Sender’s balance before transaction

->newbalanceOrig – Sender’s balance after transaction

->oldbalanceDest – Receiver’s balance before transaction

->newbalanceDest – Receiver’s balance after transaction

->isFraud – 1 if transaction is fraudulent, else 0


# Model Performance

After preprocessing and feature engineering, several algorithms were tested.
The Random Forest Classifier provided the best results.

The final model achieved:

Accuracy: 98.6%

Precision: 97.9%

Recall: 98.3%

F1-Score: 98.1%

These metrics show that the model is highly effective in detecting fraudulent transactions while maintaining strong precision and recall balance.

# Features


 Clean EDA with visual insights

 Machine Learning model trained on large-scale transaction data

 Real-time fraud prediction app using Streamlit

 Kaggle dataset integration and open-source reproducibility



# How to Run


1️. Clone the Repository

"git clone https://github.com/rakesh007-DS/Fraud_Detection_App.git"

"cd Fraud_Detection_App"

2️. Install Required Packages

"pip install -r requirements.txt"

3️. Run Streamlit App

"streamlit run fraud_detection.py"

4️. Use the App

->Choose the transaction type

->Enter transaction details

->Click Predict Fraud to see the result






# Tech Stack

1.Python 3.10+

2.Pandas, NumPy – Data cleaning and manipulation

3.Scikit-learn – Model training and evaluation

4.Matplotlib, Seaborn – Data visualization and EDA

5.Streamlit – Web app for live predictions

6.Jupyter Notebook – For analysis and model building




# Example Output


Input:

Type: TRANSFER

Amount: 2500

Old Balance (Sender): 5000

New Balance (Sender): 2500

Output:

⚠️ The transaction may be fraudulent.



