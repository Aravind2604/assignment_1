
📊 Placement Eligibility Dashboard

An interactive Python + SQL + Streamlit web application designed to simplify the campus placement process.
This project integrates a Streamlit frontend with a MySQL backend, while SQL queries are executed via Jupyter Notebook for easy data handling.

Built to assist HR professionals and placement teams in filtering, visualizing, and exporting student placement data, making the shortlisting process efficient and data-driven.

🚀 Key Features

• 🎯 Smart Multi-Dropdown Filters → Filter students by Department, Gender, Batch, Scores
• 📈 Visual Analytics → Plotly-powered charts for technical & soft skills performance
• 📥 Export Functionality → Download filtered student data as timestamped CSV files
• 🔍 MySQL Integration → Real-time query execution and data retrieval
• ⚡ User-Friendly UI → Streamlit-based clean and interactive dashboard

🛠️ Tech Stack

• Frontend → Streamlit (Python)
• Backend → MySQL
• Query Handling → Jupyter Notebook
• IDE → Visual Studio Code
• Visualization → Plotly
• Data Manipulation → Pandas

📂 Folder Structure

placement-eligibility-dashboard/
│
├── placement_app.py             # Main Streamlit application      
├── notebooks/
│   └── placement_app.ipynb      # Jupyter Notebook for DB setup & data insertion
└── README.md                    # Project Documentation

💻 Setup Instructions

1️⃣ Clone the Repository
git clone https://github.com/aravind2604/assignment_1.git
cd Placement_Eligibility_Dashboard-main

2️⃣ Set up MySQL Database
Create a MySQL database named placement_app
Run placement_app.ipynb to create required tables and insert sample data

3️⃣ Install Dependencies
pip install streamlit mysql-connector-python pandas plotly

4️⃣ Run the App
streamlit run placement_app.py

🙋‍♀️ About the Creator

Created by Aravind S., an Electrical Engineering fresher passionate about practical applications of technology.
This project reflects a strong interest in data visualization, database management, and full-stack Python development.

