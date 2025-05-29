# 📉 Customer Churn Prediction

A machine learning project to predict customer churn using supervised learning techniques. This project aims to identify customers who are likely to leave a service or subscription, enabling proactive retention strategies.

## 🚀 Project Overview

Customer churn is a significant issue for businesses, especially in subscription-based services. This project leverages data science and machine learning to:

- Analyze customer behavior
- Identify key features contributing to churn
- Build predictive models for early churn detection

## 📂 Project Structure

├── data/ # Raw and processed datasets
├── notebooks/ # Exploratory Data Analysis and modeling
├── models/ # Saved ML models
├── utils/ # Utility scripts
├── churn_prediction.py # Main pipeline script
├── requirements.txt # Python dependencies
└── README.md # Project documentation

## 🧠 Technologies Used

- **Python 3.8+**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **XGBoost / LightGBM**
- **Jupyter Notebook**
- **Streamlit** *(optional for deployment)*

## 📊 Dataset

Dataset used: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

**Features include:**
- Customer demographics
- Subscription details
- Payment methods
- Usage patterns

## 📈 Workflow

1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling  

2. **Exploratory Data Analysis (EDA)**  
   - Univariate and bivariate analysis  
   - Correlation matrix  
   - Churn distribution  

3. **Model Building**  
   - Logistic Regression  
   - Decision Trees  
   - Random Forest  
   - XGBoost  

4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - ROC-AUC curve  
   - Confusion matrix  

5. **Hyperparameter Tuning**  
   - GridSearchCV / RandomizedSearchCV  

6. **Model Deployment (Optional)**  
   - Streamlit app for real-time predictions  

## 🔍 Key Results

- Best model: **XGBoost** with ~87% accuracy on test data
- Key features influencing churn:
  - Contract type
  - Tenure
  - Monthly charges
  - Customer service calls

## 🖥️ How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
