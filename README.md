# 🌧 Rainfall Prediction Using Machine Learning

## 📌 Project Overview

Rainfall prediction is an important task in weather forecasting and environmental analysis.
This project uses **Machine Learning (Linear Regression)** to predict rainfall levels based on various weather attributes.

The model is trained on the **Austin Weather Dataset** which includes parameters such as temperature, humidity, pressure, visibility, and wind speed.

---

## 🎯 Objectives

* Analyze historical weather data
* Clean and preprocess the dataset
* Train a **Linear Regression model**
* Predict precipitation levels
* Visualize relationships between weather attributes and rainfall

---

## 📂 Dataset

Dataset used in this project:

**austin_weather.csv**

The dataset includes the following attributes:

| Feature                   | Description          |
| ------------------------- | -------------------- |
| TempAvgF                  | Average Temperature  |
| DewPointAvgF              | Average Dew Point    |
| HumidityAvgPercent        | Average Humidity     |
| SeaLevelPressureAvgInches | Atmospheric Pressure |
| VisibilityAvgMiles        | Average Visibility   |
| WindAvgMPH                | Average Wind Speed   |
| PrecipitationSumInches    | Total Rainfall       |

---

## 🛠 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## ⚙️ Methodology

1. **Data Collection**

   * Load the Austin weather dataset.

2. **Data Preprocessing**

   * Replace missing values like `T` and `-`.
   * Convert values to numeric format.
   * Remove null values.

3. **Model Training**

   * Use **Linear Regression** from Scikit-Learn.
   * Train the model using weather attributes.

4. **Visualization**

   * Plot rainfall trends.
   * Analyze the relationship between rainfall and weather parameters.

---

## 📊 Visualizations

The project generates the following graphs:

* Rainfall trend over time
* Temperature vs Rainfall
* Humidity vs Rainfall
* Dew Point vs Rainfall
* Wind Speed vs Rainfall
* Pressure vs Rainfall
* Visibility vs Rainfall

---

## 📁 Project Structure

```
rainfall-prediction-project
│
├── rainfall_prediction.ipynb
├── austin_weather.csv
└── README.md
```

---

## 📈 Results

The Linear Regression model helps analyze how different weather conditions affect rainfall levels.
Visualizations help understand trends and dependencies between weather attributes and precipitation.

---

## 🚀 Future Improvements

* Use advanced models such as Random Forest or Gradient Boosting
* Improve prediction accuracy
* Add more weather datasets for better training

---

## 👨‍💻 Author

**Ganesh Bukka**

AI & Machine Learning Enthusiast

