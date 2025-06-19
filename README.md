Medical Insurance Price Prediction
This project aims to predict medical insurance charges based on individual characteristics using machine learning models. It is designed to provide accurate estimates of healthcare insurance costs for individuals based on features such as age, gender, BMI, smoking status, and region.

📊 Problem Statement
Health insurance companies often determine policy premiums based on various customer attributes. Predicting insurance charges using machine learning can help:

Individuals estimate their premiums.

Insurers price policies fairly and competitively.

Automate and optimize pricing strategies.

📁 Dataset
The dataset used in this project contains the following features:

Feature	Description
age	Age of the individual (integer)
sex	Gender: male/female
bmi	Body Mass Index
children	Number of children covered by health insurance
smoker	Smoking status: yes/no
region	Residential area in the US
charges	Medical insurance premium (target)

Data source: Kaggle - Medical Cost Personal Dataset

⚙️ Technologies Used
Python 3.x

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook / Streamlit (optional for dashboard/app)

XGBoost / LightGBM (for improved performance)

📈 Model Workflow
Data Preprocessing

Handle categorical variables using OneHotEncoding/LabelEncoding

Feature scaling (StandardScaler or MinMaxScaler)

Train-test split

Model Building

Linear Regression (baseline)

Random Forest Regressor

Gradient Boosting Regressor / XGBoost / LightGBM

Hyperparameter tuning using GridSearchCV or RandomizedSearchCV

Model Evaluation

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

Deployment (Optional)

Streamlit dashboard for user-friendly interaction

🧪 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/gapskris/medical_insurance_prediction.git
cd insurance-price-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook Insurance_Prediction.ipynb
(Optional) Launch Streamlit app:

bash
Copy
Edit
streamlit run app.py
