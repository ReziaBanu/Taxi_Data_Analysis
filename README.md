# 🚕 Taxi Dataset Analysis Using Python

## 📌 Project Overview

Taxi services generate large amounts of trip data every day. Analyzing this data helps understand travel patterns, fare distribution, customer payment preferences, and operational trends.

The objective of this project is to clean, analyze, and visualize the Taxi dataset using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## 🎯 Project Objectives

- Load and explore the Taxi dataset.
- Identify and handle missing values.
- Perform data cleaning and preprocessing.
- Analyze taxi fares, trip distances, and payment methods.
- Create meaningful visualizations to understand data patterns.
- Extract useful insights from the dataset.

## 🛠️ Technologies and Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Google Colab | Development environment |

## 📂 Dataset Description

**Dataset Name:** Taxis Dataset

**Dataset Source:** Seaborn Built-in Dataset

The dataset is loaded using:

```python
import seaborn as sns

df = sns.load_dataset("taxis")
```

### Important Dataset Columns

| Column Name | Description |
|---|---|
| pickup | Pickup date and time |
| dropoff | Dropoff date and time |
| passengers | Number of passengers |
| distance | Trip distance |
| fare | Taxi fare |
| tip | Tip amount |
| tolls | Toll charges |
| total | Total trip amount |
| payment | Payment method |
| pickup_zone | Pickup location zone |
| pickup_borough | Pickup borough |
| dropoff_zone | Dropoff location zone |
| dropoff_borough | Dropoff borough |
| color | Taxi color |

## 🧹 Data Cleaning and Preprocessing

The following data cleaning techniques were performed:

1. Checked for missing values in all columns.
2. Identified columns containing missing data.
3. Converted pickup and dropoff columns into datetime format.
4. Removed rows with missing critical values such as pickup timestamp and fare.
5. Imputed missing numerical values using median.
6. Imputed missing categorical values using mode.
7. Verified the dataset after handling missing values.

## 📊 Data Visualizations

A total of 10 visualizations were created.

### 1. Matplotlib / Pandas Visualizations

| Visualization | Analysis |
|---|---|
| Line Chart | Fare trends over time |
| Bar Chart | Total fare by pickup borough |
| Pie Chart | Distribution of trips by payment method |
| Histogram | Distribution of taxi trip distances |
| Box Plot | Tip distribution by pickup borough |

### 2. Seaborn Visualizations

| Visualization | Analysis |
|---|---|
| Count Plot | Number of trips by pickup borough |
| Scatter Plot | Relationship between distance and fare |
| Heatmap | Correlation between numerical variables |
| Pair Plot | Pairwise relationships between distance, fare, tip, and total by pickup zone |
| Violin Plot | Fare distribution by payment method |

## 🔍 Key Insights

The visualizations help identify:

- Which pickup borough generates the highest total fare.
- Which borough has the highest number of taxi trips.
- The most frequently used payment method.
- The relationship between trip distance and fare.
- The distribution of tips across different boroughs.
- Correlations between distance, fare, tip, tolls, and total.
- Differences in fare distribution across payment methods.

## 📁 Project Structure

```text
Taxi_Dataset_Analysis/
│
├── Taxi_Data_Analysis.ipynb
│
├── README.md
│
└── Taxi_Analysis_Summary.docx
```

## ▶️ How to Run the Project

1. Clone or download this GitHub repository.
2. Open Google Colab or Jupyter Notebook.
3. Open `Taxi_Data_Analysis.ipynb`.
4. Import the required Python libraries.
5. Run the notebook cells sequentially.
6. View the data cleaning results and visualizations.

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

## 📌 Conclusion

This project demonstrates the application of Python for real-world data analysis. By performing data cleaning, handling missing values, and creating different visualizations, useful insights can be obtained from taxi trip data.

The analysis helps understand fare patterns, trip distances, borough-wise trip activity, and customer payment preferences.

## 👩‍💻 Project Category

**Domain:** Data Analytics

**Skills Demonstrated:** Python Programming, Data Cleaning, Data Preprocessing, Exploratory Data Analysis (EDA), Data Visualization, Statistical Analysis.
