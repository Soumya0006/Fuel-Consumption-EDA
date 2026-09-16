# 🚗 Fuel Consumption — Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Fuel Consumption dataset using Python.

The main objective is to understand vehicle characteristics, fuel consumption, fuel efficiency, and their relationship with **CO₂ emissions** through data analysis and visualization.

## 🎯 Objectives

- Understand the structure of the dataset
- Perform data quality checks
- Analyze numerical and categorical variables
- Explore fuel types and vehicle classes
- Analyze engine size and cylinder distribution
- Study fuel consumption patterns
- Analyze relationships between vehicle characteristics and CO₂ emissions
- Perform correlation analysis
- Detect potential outliers
- Identify fuel-efficient and high-emission vehicles
- Generate meaningful analytical insights

## 📊 Dataset

The dataset contains:

- **1,067 vehicle records**
- **13 columns**
- Numerical and categorical variables
- No missing values
- No duplicate records

### Dataset Features

| Column | Description |
|---|---|
| `MODELYEAR` | Vehicle model year |
| `MAKE` | Vehicle manufacturer |
| `MODEL` | Vehicle model |
| `VEHICLECLASS` | Vehicle class |
| `ENGINESIZE` | Engine size |
| `CYLINDERS` | Number of cylinders |
| `TRANSMISSION` | Transmission type |
| `FUELTYPE` | Fuel type |
| `FUELCONSUMPTION_CITY` | City fuel consumption |
| `FUELCONSUMPTION_HWY` | Highway fuel consumption |
| `FUELCONSUMPTION_COMB` | Combined fuel consumption |
| `FUELCONSUMPTION_COMB_MPG` | Combined fuel efficiency in MPG |
| `CO2EMISSIONS` | CO₂ emissions |

## 🛠️ Technologies Used

- 🐍 Python
- 🔢 NumPy
- 🐼 Pandas
- 📊 Matplotlib
- 📈 Seaborn
- 📓 Jupyter Notebook

## 🔍 EDA Performed

### Data Understanding

- Dataset shape
- First and last records
- Column names
- Data types
- Dataset information
- Statistical summary

### Data Quality Analysis

- Missing value analysis
- Duplicate row detection
- Data type verification
- Unique value analysis

### Categorical Analysis

- Fuel type distribution
- Vehicle class distribution
- Vehicle manufacturer analysis
- Transmission analysis

### Numerical Analysis

- Engine size distribution
- Cylinder distribution
- Fuel consumption distribution
- Combined MPG analysis
- CO₂ emissions distribution

### Relationship Analysis

- City Fuel Consumption vs Highway Fuel Consumption
- Engine Size vs CO₂ Emissions
- Cylinders vs CO₂ Emissions
- Fuel Consumption vs CO₂ Emissions
- Combined MPG vs CO₂ Emissions

### Correlation Analysis

A correlation matrix and heatmap were created to understand relationships between numerical variables.

### Outlier Detection

The **Interquartile Range (IQR)** method was used to identify potential outliers in CO₂ emissions.

## 📈 Visualizations

The project includes:

- Fuel Type Distribution
- Vehicle Class Distribution
- Top 10 Vehicle Manufacturers
- Engine Size Distribution
- Cylinder Distribution
- CO₂ Emissions Distribution
- CO₂ Emissions Boxplot
- Combined Fuel Consumption Distribution
- City vs Highway Fuel Consumption
- Engine Size vs CO₂ Emissions
- Cylinders vs CO₂ Emissions
- Fuel Consumption vs CO₂ Emissions
- MPG vs CO₂ Emissions
- Correlation Heatmap
- Pairplot by Fuel Type

## 💡 Key Insights

- The dataset contains **1,067 vehicles** and **13 variables**.
- No missing values were found.
- No duplicate rows were identified.
- The dataset contains **39 manufacturers, 663 vehicle models, 16 vehicle classes, 4 fuel types, and 22 transmission types**.
- Higher fuel consumption is generally associated with higher CO₂ emissions.
- Larger engine sizes generally tend to produce higher CO₂ emissions.
- Vehicles with more cylinders generally tend to have higher CO₂ emissions.
- Higher MPG generally corresponds to lower CO₂ emissions.
- Engine size, cylinders, and fuel consumption can be useful variables for predicting CO₂ emissions.

## 📁 Project Files

- `Fuel_Consumption_EDA.ipynb` — Complete EDA notebook
- `FuelConsumption.csv` — Dataset
- `README.md` — Project documentation

## ▶️ How to Run

### 1. Clone the Repository

git clone https://github.com/Soumya0006/Fuel-Consumption-EDA.git

### 2. Navigate to the Project

cd Fuel-Consumption-EDA

### 3. Install Required Libraries

pip install numpy pandas matplotlib seaborn jupyter

### 4. Open the Notebook

Open `Fuel_Consumption_EDA.ipynb` in **Jupyter Notebook, JupyterLab, or VS Code**.

Make sure `FuelConsumption.csv` is in the **same folder** as the notebook.

## 🔮 Future Improvements

- Feature Engineering
- Machine Learning
- Linear Regression
- CO₂ Emissions Prediction
- Model Evaluation using MAE, MSE and R²
- Power BI Dashboard
- Tableau Dashboard

## 👨‍💻 Author

**Soumyaranjan Das**

🎯 **Aspiring Data Analyst**

**Skills:** Python | SQL | MySQL | Power BI | Tableau | Excel | Data Visualization

📍 Bhubaneswar, Odisha, India

---

⭐ If you find this project useful, consider giving this repository a star.
