# 📈 TrendPulse – Hacker News Trend Analysis Pipeline

TrendPulse is a Python-based data analytics project that collects trending stories from the Hacker News API, cleans and processes the data, performs statistical analysis, and generates insightful visualizations. The project demonstrates an end-to-end data analysis workflow using Python, Pandas, NumPy, and Matplotlib.

---

## 🚀 Project Overview

The goal of TrendPulse is to automate the process of collecting trending Hacker News stories, preparing the data for analysis, extracting meaningful insights, and presenting the results through visual dashboards.

The project follows a complete data pipeline:

```
Hacker News API
       │
       ▼
Data Collection
       │
       ▼
Data Cleaning & Processing
       │
       ▼
Statistical Analysis
       │
       ▼
Feature Engineering
       │
       ▼
Data Visualization
```

---

## 📂 Project Structure

```
TrendPulse/
│
├── task_1_data_collection.py
├── task_2_processing.py
├── task_3_analysis.py
├── task_4_visualization.py
│
├── data/
│   ├── trends_YYYYMMDD.json
│   ├── trends_clean.csv
│   └── trends_analysed.csv
│
├── outputs/
│   ├── chart1_top_stories.png
│   ├── chart2_categories.png
│   ├── chart3_scatter.png
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

# ✨ Features

### 📥 Task 1 – Data Collection

- Fetches the Top 500 Hacker News stories using the Hacker News Firebase API.
- Categorizes stories using keyword matching into:
  - Technology
  - World News
  - Sports
  - Science
  - Entertainment
- Collects:
  - Post ID
  - Title
  - Category
  - Score
  - Number of Comments
  - Author
  - Collection Timestamp
- Stores collected data as JSON.

---

### 🧹 Task 2 – Data Cleaning & Processing

- Removes duplicate stories.
- Handles missing values.
- Filters low-quality posts using score threshold.
- Saves cleaned data as CSV.
- Displays category-wise story distribution.

---

### 📊 Task 3 – Statistical Analysis

- Computes descriptive statistics using NumPy.
- Calculates:
  - Mean Score
  - Median Score
  - Standard Deviation
  - Maximum Score
  - Minimum Score
- Finds:
  - Most active category
  - Most commented story
- Performs feature engineering:
  - Engagement Score
  - Popular Story Classification

---

### 📈 Task 4 – Visualization

Generates visualizations including:

- Top 10 Stories by Score
- Stories per Category
- Score vs Number of Comments Scatter Plot
- Combined TrendPulse Dashboard

All visualizations are automatically saved in the `outputs/` folder.

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Requests
- JSON
- OS
- Datetime
- Hacker News Firebase API

---

# 📊 Outputs

### Data Files

- `trends_YYYYMMDD.json`
- `trends_clean.csv`
- `trends_analysed.csv`

### Visualizations

- Top Stories Chart
- Category Distribution
- Score vs Comments Scatter Plot
- TrendPulse Dashboard

---

# 📷 Dashboard Preview

> Add screenshots of the generated charts here after running the project.

Example:

```
outputs/dashboard.png
outputs/chart1_top_stories.png
outputs/chart2_categories.png
outputs/chart3_scatter.png
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/TrendPulse.git
```

Move into the project directory

```bash
cd TrendPulse
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the pipeline

```bash
python task_1_data_collection.py
python task_2_processing.py
python task_3_analysis.py
python task_4_visualization.py
```

---

# 📚 Learning Outcomes

This project demonstrates:

- API Integration
- Data Collection
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Statistical Analysis
- Data Visualization
- File Handling
- Python Automation
- End-to-End Data Analytics Pipeline

---

# 🔮 Future Improvements

- Interactive dashboard using Streamlit
- NLP-based topic classification
- Sentiment analysis of news titles
- Machine Learning model for trend prediction
- Real-time data collection
- Scheduled automated pipeline

---

# 👨‍💻 Author

**Harsha Bhukesh**

🎓 Final-year B.Tech CSE Student

🤖 Aspiring Machine Learning Engineer

### Connect with me

- GitHub: https://github.com/YOUR_USERNAME
- LinkedIn: https://www.linkedin.com/in/elipeharshabhukesh

---

## ⭐ Support

If you found this project useful, please consider **starring ⭐ the repository**. It helps others discover the project and motivates further improvements.
