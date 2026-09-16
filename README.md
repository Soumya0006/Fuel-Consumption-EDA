# 🚗 Fuel Consumption — Exploratory Data Analysis

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on a Fuel Consumption dataset using Python.

The analysis focuses on understanding vehicle characteristics, fuel consumption patterns, and their relationship with **CO₂ emissions** through data cleaning, statistical analysis, correlation analysis, and visualization.

---

## 🎯 Objectives

* Understand the structure of the dataset
* Perform data quality checks
* Analyze numerical and categorical variables
* Explore fuel types and vehicle classes
* Analyze engine size and cylinder distribution
* Study fuel consumption patterns
* Analyze factors related to CO₂ emissions
* Identify correlations between variables
* Detect potential outliers
* Generate meaningful analytical insights

---

## 📊 Dataset

The dataset contains **1,067 vehicle records and 13 columns**.

### Features

| Column                     | Description                     |
| -------------------------- | ------------------------------- |
| `MODELYEAR`                | Vehicle model year              |
| `MAKE`                     | Vehicle manufacturer            |
| `MODEL`                    | Vehicle model                   |
| `VEHICLECLASS`             | Vehicle class                   |
| `ENGINESIZE`               | Engine size                     |
| `CYLINDERS`                | Number of cylinders             |
| `TRANSMISSION`             | Transmission type               |
| `FUELTYPE`                 | Fuel type                       |
| `FUELCONSUMPTION_CITY`     | City fuel consumption           |
| `FUELCONSUMPTION_HWY`      | Highway fuel consumption        |
| `FUELCONSUMPTION_COMB`     | Combined fuel consumption       |
| `FUELCONSUMPTION_COMB_MPG` | Combined fuel efficiency in MPG |
| `CO2EMISSIONS`             | CO₂ emissions                   |

---

## 🛠️ Tools & Technologies

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 📈 Seaborn
* 📓 Jupyter Notebook

---

## 🔍 EDA Process

### 1. Data Understanding

* Dataset shape
* First and last records
* Column names
* Data types
* Dataset information
* Statistical summary

### 2. Data Quality Analysis

* Missing-value analysis
* Duplicate-row detection
* Data-type verification
* Unique-value analysis

### 3. Categorical Analysis

* Fuel type distribution
* Vehicle class distribution
* Vehicle manufacturer analysis
* Transmission analysis

### 4. Numerical Analysis

* Engine size distribution
* Cylinder distribution
* Fuel consumption distribution
* Combined MPG analysis
* CO₂ emissions distribution

### 5. Relationship Analysis

The following relationships were analyzed:

* City Fuel Consumption vs Highway Fuel Consumption
* Engine Size vs CO₂ Emissions
* Cylinders vs CO₂ Emissions
* Fuel Consumption vs CO₂ Emissions
* Combined MPG vs CO₂ Emissions

### 6. Correlation Analysis

A correlation matrix and heatmap were created to identify relationships between numerical variables.

### 7. Outlier Detection

The **Interquartile Range (IQR)** method was used to identify potential outliers in CO₂ emissions.

---

## 📈 Visualizations

The project includes:

* Fuel Type Distribution
* Vehicle Class Distribution
* Top 10 Vehicle Manufacturers
* Engine Size Distribution
* Cylinder Distribution
* CO₂ Emissions Distribution
* CO₂ Emissions Boxplot
* Combined Fuel Consumption Distribution
* City vs Highway Fuel Consumption
* Engine Size vs CO₂ Emissions
* Cylinders vs CO₂ Emissions
* Fuel Consumption vs CO₂ Emissions
* MPG vs CO₂ Emissions
* Correlation Heatmap
* Pairplot

---

## 💡 Key Insights

* The dataset contains **1,067 vehicles** and **13 variables**.
* No missing values were found.
* No duplicate rows were identified.
* The dataset contains **39 manufacturers, 663 models, 16 vehicle classes, 4 fuel types, and 22 transmission types**.
* City and highway fuel consumption are strongly related.
* Larger engine sizes generally show higher CO₂ emissions.
* Vehicles with more cylinders generally tend to have higher CO₂ emissions.
* Higher combined fuel consumption is generally associated with higher CO₂ emissions.
* Higher MPG generally corresponds to lower CO₂ emissions.
* Engine size, cylinders, and fuel consumption can be useful variables for CO₂ emissions prediction.

---

## 📊 CO₂ Emissions Summary

| Metric             |  Value |
| ------------------ | -----: |
| Mean               | 256.23 |
| Median             |    251 |
| Minimum            |    108 |
| Maximum            |    488 |
| Standard Deviation |  63.34 |

The IQR method identified **6 potential CO₂ emission outliers**.

---

## 🚘 Vehicle Analysis

### Highest CO₂ Emissions

The highest CO₂ emission recorded in the dataset was **488**, associated with the **Ford E350 Wagon** with a 6.8L engine and 10 cylinders.

### Highest Fuel Efficiency

The highest combined fuel efficiency recorded was **60 MPG**, associated with the **Toyota Prius c** with a 1.5L engine.

---

## 📁 Project Structure

```text
Fuel-Consumption-EDA/
│
├── Fuel Consumption — Exploratory Data Analysis.ipynb
├── FuelConsumption.csv
├── Fuel Consumption EDA.pdf
└── README.md
```

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Fuel-Consumption-EDA.git
```

### Open the project

```bash
cd Fuel-Consumption-EDA
```

### Install dependencies

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
Fuel Consumption — Exploratory Data Analysis.ipynb
```

---

## 🔮 Future Improvements

* Feature engineering
* Statistical modeling
* Linear Regression
* Machine Learning-based CO₂ prediction
* Model evaluation using MAE, MSE and R²
* Interactive Power BI dashboard
* Tableau visualization
* CO₂ emissions prediction application

---

## 👨‍💻 Author

### Soumyaranjan Das

**Aspiring Data Analyst**

**Skills:** Python • SQL • MySQL • Power BI • Tableau • Excel • Data Visualization

📍 Bhubaneswar, Odisha, India

---

## ⭐ Support

If you found this project useful, feel free to **⭐ Star this repository**.

Thank you for visiting! 🚗📊
