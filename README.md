# House Price Predictor

A machine learning-based application that predicts housing prices in Bengaluru based on property details like location, square footage, number of bathrooms, and BHK. Built using Python and trained with Ridge Regression on a cleaned real estate dataset.

---

## Project Structure
House-Price-Predictor-Repo/
│
├── main.py # Main application script (Streamlit UI)
├── RidgeModel.pkl # Trained Ridge Regression model
├── cleaned_bangaluru_data.csv # Cleaned dataset for training
├── requirements.txt # Python dependencies
└── .idea/ # Project config files (IDE-related)


---

## Features

- Predicts house prices using key features (BHK, bath, sqft, location)
- Cleaned and preprocessed dataset for better accuracy
- Trained Ridge Regression model with good generalization
- User-friendly interface using Streamlit
- Real-time predictions with quick response time

---

## Tech Stack

- **Language**: Python 3.x  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `streamlit`  
- **Model**: Ridge Regression  
- **Deployment**: Local (can be deployed to Streamlit Cloud/Render)

---

## Dataset

- Cleaned Bengaluru housing dataset
- Key columns used:
  - `total_sqft`
  - `bath`
  - `bhk`
  - `location` (filtered and encoded)





