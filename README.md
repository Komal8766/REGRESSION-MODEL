📌 Placement Package Prediction using Simple Linear Regression

This project is a machine learning application that predicts a student’s expected placement package (LPA) using their CGPA. It leverages Simple Linear Regression from Scikit-learn and provides an easy-to-use web interface built with Streamlit.

🚀 Features

* Predicts placement package based on CGPA.
* Uses Simple Linear Regression for modeling.
* Interactive web interface built with Streamlit.
* Trained model saved and loaded using Joblib.
* Clean and lightweight implementation suitable for beginners learning regression.

🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Matplotlib
* Seaborn
* Joblib

📊 Project Workflow

1. Load and explore the placement dataset.
2. Perform data preprocessing and visualization.
3. Split data into training and testing sets.
4. Train a Simple Linear Regression model.
5. Evaluate model performance.
6. Save the trained model using Joblib.
7. Deploy the model with a Streamlit web application for real-time predictions.

📁 Project Structure

├── app.py                     # Streamlit application
├── regression_model.joblib    # Saved trained model
├── placement.csv              # Dataset
├── simple_linear_regression.ipynb
├── requirements.txt
└── README.md

▶️ Installation

git clone https://github.com/your-username/placement-package-predictor.git
cd placement-package-predictor
pip install -r requirements.txt

▶️ Run the Application

streamlit run app.py

📈 Example

Input: CGPA = 8.5
Output: Predicted Placement Package = 7.8 LPA (example output; actual value depends on the trained model).

🎯 Learning Outcomes

* Applied supervised machine learning using Simple Linear Regression.
* Performed data analysis and visualization.
* Built and evaluated a predictive model.
* Deployed an ML model using Streamlit.
* Managed model persistence with Joblib.

👩‍💻 Author

Komal Murkute
Data Analyst | Python | SQL | Machine Learning | Power BI | Tableau

