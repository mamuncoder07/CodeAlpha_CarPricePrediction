# 🚗 Car Price Prediction Using Machine Learning

This project was completed as part of the **CodeAlpha Data Science Internship**.

The objective of this project is to build a Machine Learning model that can accurately predict the selling price of a used car based on various features such as present price, fuel type, transmission type, driven kilometers, ownership history, and car age.

---

## 📌 Project Objective

To develop a predictive model that estimates the selling price of a car using historical vehicle data and Machine Learning techniques.

---

## 📊 Dataset Information

The dataset contains information about 301 cars and includes the following features:

- Car Name
- Year
- Present Price
- Driven Kilometers
- Fuel Type
- Selling Type
- Transmission
- Owner
- Selling Price (Target Variable)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses and visualizations were performed:

### Fuel Type Distribution
- Petrol vehicles dominate the dataset.
- Diesel vehicles are the second most common.
- Only a few CNG vehicles are present.

### Transmission Analysis
- Most cars use Manual transmission.
- Automatic transmission vehicles are comparatively fewer.

### Correlation Heatmap
- Analyzed relationships between different features.
- Identified important variables affecting car prices.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

1. Checked for missing values.
2. Removed unnecessary columns.
3. Created a new feature called **Car Age**.
4. Converted categorical data into numerical format using One-Hot Encoding.
5. Separated features and target variables.

---

## 🤖 Machine Learning Model

### Random Forest Regressor

The dataset was split into:

- 80% Training Data
- 20% Testing Data

A Random Forest Regressor model was trained to predict car selling prices.

---

## 📊 Model Performance

### R² Score

```text
0.9594
```

### Performance

The model achieved an R² Score of approximately **95.94%**, indicating excellent prediction accuracy on unseen data.

---

## 📷 Visualizations

- Fuel Type Distribution
- Transmission Distribution
- Correlation Heatmap
- Actual vs Predicted Price Graph

---

## 📁 Repository Structure

```text
CodeAlpha_CarPricePrediction
│
├── car data.csv
├── Car_Price_Prediction.ipynb
├── fuel_type_hd.png
├── transmission_hd.png
├── correlation_heatmap_hd.png
├── actual_vs_predicted_hd.png
└── README.md
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Data Cleaning and Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Regression Models
- Random Forest Algorithm
- Model Evaluation using R² Score

---

## 🚀 Conclusion

This project demonstrates how Machine Learning can be used to predict used car prices based on multiple vehicle-related features. The Random Forest Regressor performed exceptionally well and achieved an R² Score of **95.94%**, making it a reliable model for price prediction tasks.

---

## 👨‍💻 Author

**Mamun Reja**

B.Tech (Artificial Intelligence & Machine Learning)

CodeAlpha Data Science Intern
