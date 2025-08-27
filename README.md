# House Price Prediction Project 🏠💰

This project is a complete end-to-end machine learning workflow to predict house prices based on various features of the property. It demonstrates practical data science skills including data cleaning, feature engineering, and predictive modeling.

---

## 📋 Project Workflow

This project follows a structured data science pipeline:

1.  **Data Cleaning**: Handled potential outliers (e.g., properties with an unusually high number of bedrooms) to ensure the data is robust and clean.
2.  **Exploratory Data Analysis (EDA)**: Investigated the dataset to understand the relationships between different features and the target variable (price).
3.  **Feature Engineering**: Creatively engineered new, more insightful features from the existing data. Key new features include:
    * `sqft_per_bedroom`: To capture the spaciousness of rooms.
    * `effective_age`: Calculated based on the later of the build year or renovation year to better represent the property's modern condition.
4.  **Data Preprocessing**: Prepared the data for modeling by splitting it into training and testing sets and applying feature scaling (`StandardScaler`) to normalize the data.
5.  **Modeling**: Trained a **Linear Regression** model using Scikit-learn to predict house prices.
6.  **Evaluation**: Assessed the model's performance using key regression metrics like Mean Squared Error (MSE) and R-squared ($R^2$).

---

## 🛠️ Tech Stack

* **Python**: The core programming language used.
* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Scikit-learn**: For splitting data, preprocessing, and building the Linear Regression model.
* **Matplotlib / Seaborn**: For data visualization during EDA.
