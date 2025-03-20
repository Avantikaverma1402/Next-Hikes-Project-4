# 📱 **Mobile Price Prediction & Feature Importance Analysis**  

## 🚀 **Project Overview**  
In today’s fast-paced smartphone industry, understanding what drives mobile phone prices is crucial for both consumers and manufacturers. This project builds a **machine learning model** to predict mobile prices based on key hardware specifications while analyzing **feature importance** using SHAP values and correlation metrics.  

By leveraging **Exploratory Data Analysis (EDA), feature engineering, and machine learning algorithms**, this project provides data-driven insights into the most **significant factors influencing mobile pricing.**  

---

## 📂 **Dataset Information**  
The dataset consists of mobile phone specifications, including:  

🔹 **Hardware Specifications:** Model, Processor, RAM, Memory, Battery, AI Lens  
🔹 **Camera Features:** Rear Camera MP, Front Camera MP  
🔹 **Pricing Factors:** Price per RAM, Price per Memory  
🔹 **Design Features:** Mobile Height, Color  

### **🔍 Key Insights from Data Exploration**  
✔ **RAM & Memory are the biggest contributors to price fluctuations** 📈  
✔ **Camera quality (MP) also plays a major role in pricing** 📸  
✔ **Battery capacity has minimal impact on price** 🔋  
✔ **AI Lens does not significantly influence pricing decisions**  

---

## 🛠️ **Project Workflow**  

### **1️⃣ Exploratory Data Analysis (EDA)**
- Data Cleaning: Handling missing values, duplicates, and inconsistencies  
- Visualizing correlations between features and price  
- Detecting and handling outliers  

### **2️⃣ Feature Engineering & Selection**  
- **Correlation Analysis**: Identifying features with the highest impact on price  
- **SHAP Value Analysis**: Using SHAP to explain model predictions  
- **Encoding Categorical Variables**: Converting categorical data into numerical values  

### **3️⃣ Model Development & Training**  
Trained multiple **Supervised Learning Models**:  
✅ **Linear Regression**  
✅ **Decision Tree Regressor**  
✅ **Random Forest Regressor**  
✅ **Lasso Regression**  
✅ **Support Vector Regressor (SVR)**  
✅ **K-Nearest Neighbors (KNN)**  
✅ **Gradient Boosting Regressor**  

### **4️⃣ Model Evaluation & Selection**  
Models are compared using the following performance metrics:  
📊 **Mean Absolute Error (MAE)**  
📉 **Root Mean Squared Error (RMSE)**  
🎯 **R² Score (Coefficient of Determination)**  

📌 **Best Model Selection:** The model with the lowest **RMSE & MAE** and the highest **R² Score** is chosen.  

### **5️⃣ Feature Importance Analysis (SHAP)**
- **Global Feature Importance**: Identifying the most significant factors influencing mobile phone prices  
- **Local Explanation**: Visualizing how each feature affects an individual prediction  

### **6️⃣ Deployment (Optional)**
The trained model can be deployed in a **web-based UI**, allowing users to input mobile specifications and get an **instant price prediction**.  

---

## 🔑 **Key Findings & Results**
✔ **RAM & Storage are the biggest price drivers** 📊  
✔ **Processor power also plays a crucial role** ⚡  
✔ **Battery size does NOT significantly impact pricing** 🔋  
✔ **AI-based camera enhancements don’t directly influence price** 🤖  

📌 **The Best Performing Model:**  
🏆 **Random Forest Regressor** – Achieved the best RMSE and R² score, making it the most reliable model for price prediction.  

---

## 📁 **Project Files**  
📂 **`Processed_Flipdata.csv`** → Preprocessed dataset used for training  
📂 **`Project 4-Final EDA.ipynb`** → Complete Jupyter Notebook with analysis and model training  
📂 **`README.md`** → Project documentation  

---

## 🛠 **Technologies & Libraries Used**
🔹 **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
🔹 **Machine Learning:** Scikit-learn (Linear Regression, Decision Trees, Random Forest, Gradient Boosting)  
🔹 **SHAP for Explainability** 📊  

---

## 🎯 **Conclusion & Future Scope**
✅ **This model enables better mobile price estimations** for manufacturers and buyers.  
✅ **Feature importance insights** help manufacturers focus on high-impact components.  

---
