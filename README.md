# 🦠 COVID-19 Data Analysis using NumPy, Pandas & Visualization

## 📌 Project Overview

This project performs **end-to-end COVID-19 data analysis** using:

* **NumPy** → numerical operations
* **Pandas** → data cleaning & analysis
* **Matplotlib & Seaborn** → data visualization

It follows a real-world data workflow:

> **Load → Clean → Analyze → Visualize**

---

## 🧱 Project Structure

```
covid_analysis/
│
├── data/
│   └── country_wise_latest.csv
│
├── outputs/
│   └── (saved plots / results)
│
├── src/
│   ├── numpy_ops.py
│   ├── pandas_loader.py
│   ├── data_cleaner.py
│   ├── eda_analyzer.py
│   ├── visualizer.py
│
├── main.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Features Implemented

### 🔹 Task 1 – NumPy Operations

* Created 1D & 2D arrays
* Performed:

  * Mean, Sum, Min, Max
* Vectorized operations
* Broadcasting
* Slicing & indexing
* Reshaping & splitting arrays

---

### 🔹 Task 2 – Data Loading (Pandas)

* Loaded CSV dataset
* Displayed:

  * First & last rows
  * Data types
  * Null values
  * Duplicate values

---

### 🔹 Task 3 – Data Cleaning

* Removed duplicate rows
* Handled missing values
* Replaced invalid values (`inf`, `NaN`)
* Prepared clean dataset for analysis

---

### 🔹 Task 4 – Exploratory Data Analysis (EDA)

* Total confirmed, deaths, recovered
* WHO region-wise analysis
* Top 10 affected countries
* Highest active cases
* Used:

  * `groupby()`
  * sorting
  * filtering
  * aggregation

---

### 🔹 Task 5 – Visualization

Generated the following charts:

* 📈 Line graph → Confirmed cases
* 📊 Bar chart → Deaths by WHO region
* 📉 Histogram → Active cases distribution
* 🥧 Pie chart → Recovered cases by region
* 🔵 Scatter plot → Confirmed vs Deaths
* 🔥 Heatmap → Correlation matrix

Plots can be viewed directly or saved in the **outputs/** folder.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-repo-link>
cd covid_analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the project

```bash
python main.py
```

---

## 📊 Output

* Cleaned dataset
* Statistical summaries
* Region-wise analysis
* Visualizations
* Insights from COVID data

---

## 🧠 Key Learnings

* Applied **NumPy for efficient numerical computation**
* Used **Pandas for real-world data analysis**
* Built a **modular OOP-based project structure**
* Created **meaningful visualizations for insights**
* Understood **data cleaning & preprocessing workflows**

---

## 🔮 Future Improvements

* Save all plots automatically in `outputs/`
* Add interactive dashboards (Plotly / Streamlit)
* Perform time-series analysis
* Add logging instead of print statements

---

## 👨‍💻 Author

**Love Vyas**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
