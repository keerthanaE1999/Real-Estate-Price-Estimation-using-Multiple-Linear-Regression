# Real-Estate-Price-Estimation-using-Multiple-Linear-Regression
This project uses *Multiple Linear Regression* to estimate housing prices based on various property attributes. It demonstrates how linear regression techniques can be applied to real-world datasets to support smarter, data-driven decisions in the real estate industry.

---

## 📌 Objective

To develop a regression model that accurately predicts house prices using key features like area, number of rooms, floor, and location details.

---

## 📊 Dataset Overview

*Source*: [Kaggle – Real Estate Dataset by uviiiii](https://www.kaggle.com/datasets/uviiiii/real-estate)

The dataset contains details of real estate listings including:

- transaction date – When the transaction took place  
- house age – Age of the house (in years)  
- distance to the nearest MRT station – Distance in meters  
- number of convenience stores – Nearby stores  
- latitude and longitude – Geographic location  
- price of unit area – Target variable (price per square meter)

---

## ⚙ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib & Seaborn (for visualization)  
- Scikit-learn (for model building)

---

## 🔍 Workflow

1. *Data Loading*
   - Import CSV and load it into a Pandas DataFrame.

2. *Exploratory Data Analysis (EDA)*
   - Visualize correlations and distributions.
   - Detect and handle outliers.

3. *Feature Engineering*
   - Select and preprocess important features.

4. *Model Building*
   - Train a *Multiple Linear Regression* model using scikit-learn.

5. *Model Evaluation*
   - Use metrics like *R² Score, **MAE, **MSE, and **RMSE*.

6. *Visualization*
   - Plot predicted vs actual values for insights.

---

## 📈 Results

- *R² Score*: 0.54 (can vary depending on preprocessing)
- *RMSE*: 8.6
- The model was able to capture the trend of price variation based on location and amenities.
---

## 📁 Files in This Repository

- real_estate_price_prediction.ipynb – Complete notebook with code and output  
- real_estate.csv – Dataset (or load it via notebook from Kaggle)  
- requirements.txt – Required Python libraries

---

## ✅ Installation & Setup

1. Clone this repository:

```bash
git clone https://github.com/yourusername/real-estate-price-estimation.git
cd real-estate-price-estimation
