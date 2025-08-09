Customer Satisfaction Intelligence Dashboard
📌 Overview
This project analyzes customer support interactions to predict satisfaction outcomes and provide actionable insights for service improvement. It combines machine learning, data visualization, and business intelligence tools to empower support teams.

🧠 Problem Statement
Customer satisfaction is a key metric for service quality. This dashboard helps:

Predict whether a customer is satisfied or dissatisfied after a support ticket

Identify patterns in ticket types, resolution times, and customer demographics

Visualize trends to guide operational decisions

✅ Features
📊 Power BI Dashboard: Interactive visuals for ticket analysis, satisfaction trends, and agent performance

🧹 Data Preprocessing: Cleaned and transformed support ticket data

🧠 ML Models: Trained classifiers (e.g., XGBoost, Random Forest) with over 70% accuracy

🔍 Predictive Insights: Satisfaction prediction based on ticket metadata and customer remarks

📁 CSV Upload: Easily test with your own dataset

💬 AI-Generated Responses (optional): Personalized replies based on prediction

🚀 Tech Stack
Component	Tools Used
Data Cleaning	Pandas, NumPy
Modeling	Scikit-learn, XGBoost
Visualization	Power BI, Matplotlib
Deployment	Streamlit (optional)
Automation	SMTP for email alerts (optional)
📂 Repository Structure
├── data/
│   └── customer_support_data.csv
├── notebooks/
│   └── model_training.ipynb
├── app/
│   └── streamlit_app.py
├── models/
│   └── xgb_model.joblib
├── dashboard/
│   └── powerbi_report.pbix
├── README.md
📈 Results
Model Accuracy: 73.71%

Correct Predictions: 1,873 out of 2,500 tickets

Key Insight: High-priority tickets resolved within 24 hours had a 90% satisfaction rate

📬 Contact
For questions or collaboration, feel free to reach out via LinkedIn.
