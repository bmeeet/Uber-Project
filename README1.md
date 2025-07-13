# 🚖 Uber Data Analysis

This project performs an exploratory data analysis (EDA) on Uber ride data using Python. The goal is to uncover insights into ride trends, peak hours, most popular pickup locations, and more using visualizations and data manipulation techniques.

## 📂 Project Structure

```
uber-data-analysis/
├── uber data analysis.ipynb
├── README.md
└── requirements.txt
```

## 📊 Key Objectives

- Load and clean Uber ride data.
- Analyze ride patterns by:
  - Date and time
  - Day of the week
  - Base station
- Visualize insights using matplotlib and seaborn.

## 🛠️ Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🧪 Features & Analysis

- **Data Cleaning:**  
  - Converted date/time formats.
  - Handled missing or duplicate values.

- **Time-based Analysis:**  
  - Distribution by hour, day, and month.
  - Weekly and hourly trends.

- **Location-based Analysis:**  
  - Most popular pickup locations.
  - Ride frequency by base station.

- **Visualizations:**  
  - Bar charts
  - Heatmaps
  - Pie charts
  - Line graphs

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/uber-data-analysis.git
cd uber-data-analysis
```

2. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:

```bash
jupyter notebook "uber data analysis.ipynb"
```

## 📁 Dataset

The dataset used is Uber ride data from April to September 2014, originally sourced from [Kaggle](https://www.kaggle.com/datasets).

## 📌 Requirements

You can install required Python packages using:

```bash
pip install -r requirements.txt
```
