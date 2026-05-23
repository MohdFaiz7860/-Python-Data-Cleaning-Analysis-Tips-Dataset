# 🍽️ Python Data Cleaning & Analysis — Tips Dataset

A Python project that performs end-to-end data cleaning and exploratory analysis on the **Tips dataset** using Pandas, NumPy, and Matplotlib.

---

## 📌 Overview

This notebook loads a restaurant tips dataset, cleans and preprocesses the data, and uncovers revenue insights by day and time through grouped aggregations and visualizations.

---

## 📊 What This Project Does

### 🔧 Data Cleaning
- Loads dataset from CSV using Pandas
- Checks dataset shape and column structure
- Identifies and removes duplicate records
- Converts numeric columns (`total_bill`, `tip`, `size`) to proper data types
- Fills missing values with column **median** to handle nulls without skewing data

### 📈 Analysis & Insights
| Analysis | Description |
|---|---|
| Highest bill by day | Top bills sorted by day |
| Highest bill by time | Top bills sorted by time (Lunch/Dinner) |
| Total revenue by day | Grouped sum of total bill per day |
| Total revenue by time | Grouped sum of total bill by meal time |
| Average bill by day | Mean bill amount per day |
| Average bill by time | Mean bill amount per meal time |

### 📉 Visualizations
- **Bar chart** — Total bill by day
- **Bar chart** — Total bill by time (Lunch vs Dinner)
- **Pie chart** — Revenue share by day

---

## 🗂️ Dataset

**File:** `tips.csv`  
**Source:** Classic restaurant tips dataset (available on [Kaggle](https://www.kaggle.com/datasets/jsphyg/tipping) or Seaborn's built-in datasets)

| Column | Description |
|---|---|
| `total_bill` | Total bill amount |
| `tip` | Tip amount |
| `size` | Party size |
| `day` | Day of the week |
| `time` | Meal time (Lunch / Dinner) |
| `sex` | Customer gender |
| `smoker` | Smoker or non-smoker |

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — data loading, cleaning, groupby analysis
- **NumPy** — numeric type handling
- **Matplotlib** — bar charts and pie chart
- **Google Colab** — development environment

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib
```

### 3. Add the dataset
Place `tips.csv` in your working directory (or Google Drive if using Colab) and update the file path:
```python
file = "tips.csv"  # update path as needed
```

### 4. Run the notebook
Open `Python_Data_Cleaning.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab and run all cells.

---

## 📁 Project Structure

```
├── Python_Data_Cleaning.ipynb   # Main analysis notebook
├── tips.csv                     # Dataset (add manually)
└── README.md
```

---

## 📄 License

This project is for educational purposes. Dataset is publicly available.
