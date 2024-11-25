# ✈️ Flight Price Prediction: Data Cleaning & Feature Engineering

This repository contains the **data cleaning** 🧹 and **feature engineering** ⚙️ steps for the **Flight Price Prediction** project.  
The goal of this project was to preprocess and prepare the data for machine learning models to predict flight prices.  
While this project focuses on transforming the raw data into a clean and feature-rich dataset, it does *not* include model building or price prediction.

---

## 🌟 Project Overview

The dataset used in this project contains flight information such as:
- 📍 **Flight Source**
- 📍 **Flight Destination**
- 🛑 **Total Stops**
- 💰 **Flight Price**
- 📝 Other relevant flight details (e.g., date, airline, etc.)

The project includes the following key steps:
- 🧹 **Data Cleaning**: Handling missing values, correcting data types, and removing duplicates.
- ⚙️ **Feature Engineering**: Creating new features, encoding categorical variables, and scaling numerical features.

The resulting preprocessed data is ready for machine learning models to predict flight prices! 🚀

---

## 📋 Steps Performed

### 1️⃣ Data Loading
✔️ The dataset was loaded from a CSV file and examined for inconsistencies, such as missing values and incorrect data types.

### 2️⃣ Data Cleaning
🧹 Steps included:
- 🔍 Identifying and handling missing values.
- 🔢 Converting categorical and numerical columns to appropriate data types.
- ❌ Removing duplicate entries.

### 3️⃣ Feature Engineering
⚙️ New features were created to enhance the dataset, including:
- 🗓️ Extracting date, month, and day of the week from flight date columns.
- 🛑 Encoding **Total Stops** as numerical categories.
- 📊 Using **OneHotEncoding** and **OrdinalEncoding** for categorical variables.
- 📈 Scaling numerical features for consistency.

---

## 📂 Dataset

The dataset used in this project can be found in the `data/` directory.  
It contains:
- The raw flight data before cleaning.
- The final preprocessed dataset ready for machine learning tasks.

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository and create a pull request if you have suggestions or improvements. 😊

---

## 📧 Contact

If you have any questions or feedback, feel free to reach out. 📬

---

## 🎉 Thank You!

Thank you for visiting this repository! 🚀  
I hope this project inspires you to dive deeper into the exciting world of data cleaning and feature engineering.  
Happy coding! 💻✨
