📊 Telecom Churn Prediction Dashboard

An end-to-end Machine Learning project that predicts customer churn and presents the results through an interactive Streamlit dashboard with a Power BI–style dark UI.

This project demonstrates how ML models can be integrated into real-world business dashboards to support customer retention decisions.

🚀 Features

End-to-end ML pipeline (data → model → dashboard)

Customer churn prediction (Churn / Stay)

Probability-based risk estimation

Interactive Streamlit dashboard

Custom dark theme with CSS (Power BI–inspired UI)

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

Joblib

Streamlit

Custom CSS

📂 Project Structure
telecom-churn-dashboard/
│
├── data/
│   └── telco_churn.csv
├── model/
│   └── churn_model.pkl
├── train_model.py
├── app.py
├── style.css
├── requirements.txt
└── README.md

⚙️ How It Works

Customer data is preprocessed and encoded

A Logistic Regression model is trained

The trained model is saved using joblib

Streamlit loads the model and predicts churn in real time

Results are shown in a clean, business-friendly dashboard

▶️ Run Locally
1️⃣ Install dependencies
pip install -r requirements.txt

2️⃣ Train the model
python train_model.py

3️⃣ Run the dashboard
python -m streamlit run app.py


Open in browser:

http://localhost:8501

🧪 Sample Inputs

Gender: Female

Age: 34

Days Subscribed: 2

Weekly Minutes Watched: 200

Videos Watched: 14

Customer Support Calls: 2

📈 Output

Churn Prediction: Yes / No

Risk Probability: Percentage-based churn risk

💡 Use Case

This dashboard can help:

Identify high-risk customers

Support retention strategies

Demonstrate ML deployment skills for internships and entry-level roles

🔮 Future Improvements

Train model using all dashboard input features

Add feature importance visualization

Deploy on Streamlit Cloud

Add historical churn analytics

👤 Author

Guru Patel
Data Science & Analytics Intern

