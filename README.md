A machine learning web application that predicts housing prices in Bengaluru using location, size, number of bathrooms, and other key features. The model is trained on cleaned real estate data and utilizes Ridge Regression to provide accurate, real-time predictions.


House-Price-Predictor-Repo/
├── main.py                       # Main application script (Streamlit or CLI-based)
├── RidgeModel.pkl                # Trained Ridge Regression model
├── cleaned_bangaluru_data.csv    # Preprocessed dataset
├── requirements.txt              # Required Python packages
├── .idea/                        # Project config files (PyCharm)

Features
Predicts house prices based on area, location, BHK, and bath count

Cleaned and preprocessed dataset for accurate modeling

Ridge Regression model trained and saved using scikit-learn

Simple UI to accept user inputs (via Streamlit or CLI)

Real-time predictions with consistent performance

🧰 Tech Stack
Language: Python 3

Libraries: pandas, numpy, scikit-learn, streamlit

Model: Ridge Regression

Deployment: Local Streamlit App or future cloud hosting

📈 Dataset
Cleaned dataset of Bengaluru housing data

Key Features:

Total square feet

Number of bathrooms

Number of bedrooms (BHK)

Location (filtered and encoded)

🛠 How to Run
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Application

bash
Copy
Edit
streamlit run main.py
Enter Inputs

Provide house details (area, BHK, bath, location) to get predicted price.

📊 Model Info
Ridge Regression used to prevent overfitting

Model serialized as RidgeModel.pkl

Performance validated with R² Score and Cross Validation

📌 Future Enhancements
Add advanced models (e.g., XGBoost, Lasso)

Add geolocation and map-based UI

Host on cloud (Streamlit Cloud, Render)
