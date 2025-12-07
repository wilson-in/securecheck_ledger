
# 🚓 SecureCheck: A Python-SQL Digital Ledger for Police Post

SecureCheck is a Data Science mini project that analyzes traffic stop data using Python, PostgreSQL, and Streamlit. 
It delivers SQL-powered insights through a clean and interactive dashboard. Ideal for those learning SQL integration with Python.

---

## 🔧 Tools Used

![Python](https://img.shields.io/badge/Python-Pandas%20%7C%20SQLAlchemy-gray?logo=python&logoColor=white&labelColor=3776AB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-gray?logo=postgresql&logoColor=white&labelColor=4169E1)
![Google%20Colab](https://img.shields.io/badge/Google%20Colab-Data%20Cleaning%20In%20Notebook-gray?logo=google-colab&logoColor=white&labelColor=f9ab00)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard%20UI-gray?logo=streamlit&logoColor=white&labelColor=FF4B4B)
![VS%20Code](https://img.shields.io/badge/VS%20Code-IDE-gray?logo=visual-studio-code&logoColor=white&labelColor=0078d7)

---

## 📁 Project Structure

```
Project_1-Secure_Check/
├── 📁 app/
│   └── main_app.py                # Streamlit app with SQL queries
├── 📁 data/
│   └── cleaned_traffic_stop.csv   # Cleaned dataset
├── 📁 notebooks/
│   └── Mini_project_1(Secure_Check).ipynb   # Data cleaning in Colab
├── .gitignore
├── requirements.txt               # Python dependencies
└── README.txt                     # Project documentation
```

---

## 🚀 How to Run

1. Clone the repo  
   `git clone https://github.com/wilson-in/securecheck_ledger.git`

2. Navigate to the app folder  
   `cd Project_1-Secure_Check/app`

3. Install required packages  
   `pip install -r ../requirements.txt`

4. Update your PostgreSQL connection string in `main_app.py`

5. Run the Streamlit app  
   `streamlit run main_app.py`

---

## 📊 Features

- Store and query traffic stop data using PostgreSQL
- 20+ SQL queries (simple to advanced)
- Interactive dashboard with dropdown filters
- Clean UI built with Streamlit

---


## 📚 Sample SQL Insights

- Top 10 drug-related vehicles
- Most searched violations
- Arrest rate by age group
- Night-time vs day-time stops
- Year-wise arrest breakdown (using window functions)
- Driver demographics by country

---

