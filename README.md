# Customer Churn Prediction App

##  Overview
A machine learning-based web application that predicts customer churn using demographic and behavioral data. The model is trained using a Jupyter Notebook and deployed through a Streamlit interface.

##  Features
- Predicts whether a customer will churn
- Interactive Streamlit UI
- Real-time predictions
- Machine learning model trained using notebook

##  Tech Stack
Python, Scikit-learn, Streamlit, NumPy, Pandas

##  How to Run
### Step 1: Install dependencies
pip install -r requirements.txt  

### Step 2: Train the model
Run the Jupyter Notebook to generate the trained model file.
Then open and run:
customer_churn.ipynb
(This will create the .pkl model file required for the app)

### Step 3: Run the application
streamlit run churn_app.py

### Note
The .pkl model file is not included in this repository.
You must run the notebook first to generate the model before starting the app.
