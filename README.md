# Telecom-Customer-Churn-Prediction
This project is a Streamlit-based machine learning app for predicting telecom customer churn. It takes customer information as input, uses a trained model pipeline to predict whether the customer is likely to churn, and also provides a simple AI-generated explanation for the prediction.


---

## Features

- Predicts whether a telecom customer is likely to churn
- Uses customer details such as:
  - tenure
  - monthly charges
  - internet service
  - contract type
  - payment method
  - senior citizen status
- Displays churn probability
- Provides an explanation of the prediction
- Simple and interactive Streamlit user interface

---

## Project Structure

```bash
├── app.py                                   # Main Streamlit application
├── ui.py                                    # Handles user input form
├── model_pipeline.joblib                    # Saved trained ML pipeline
├── main.ipynb                               # Model training and experimentation notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv     # Dataset used for training
