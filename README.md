# 🗳 ML_PackagingMonitor Project

## 📘 **Overview**  
This project demonstrates a **Voting Ensemble** machine learning pipeline for predicting a binary target on an imbalanced dataset.  
The dataset contains a mix of **numeric and categorical features**, requiring preprocessing, one-hot encoding, and scaling. The main goal is to **predict disruption events (0/1)** accurately.

## 🧠 **Project Highlights**  
- **Type:** Classification (Binary)  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn  
- **Dataset:** `disruption_dataset.csv` — mix of numeric & categorical features  

## ⚙️ **Workflow**  
1. **Data Cleaning & Preprocessing** – handle missing values, encode categorical features.  
2. **EDA (Exploratory Data Analysis)** – visualize distributions, density plots, boxplots, and heatmaps.  
3. **Train/Test Split** – separate features (X) and target (y) for evaluation.  
4. **Spot-Check Models** – baseline performance with LR, LDA, SVM, and KNN.  
5. **Voting Ensemble** – combine LR, LDA, SVM, and Random Forest with **hard/soft voting**.  
6. **SMOTENC Oversampling** – balance classes to improve minority class prediction.  
7. **Threshold Tuning** – adjust decision threshold for better class recall.  
8. **Model Evaluation** – Accuracy, Confusion Matrix, Classification Report.

## 🚧 **Challenges**  
- Imbalanced dataset led to poor recall for minority class.  
- Categorical + numeric mix required careful encoding and handling in SMOTENC.  
- Hyperparameter tuning of ensemble weights needed to optimize predictions.

## 📊 **Results**  
✅ **Best Model:** Voting Ensemble (LR + LDA + SVM + Random Forest)  
🎯 **CV Accuracy:** ~73.8%  
📉 **Test Accuracy:** ~72.9%  
⚖️ Minor class prediction still low due to extreme imbalance; SMOTENC improved balance but careful thresholding is necessary.

## 💡 **Skills Used**  
🐍 Python  
🤖 Machine Learning  
📊 Data Science  
📈 Ensemble Learning & Model Optimization  
📉 Handling Imbalanced Data  

## 📁 **Files Included**  
- `packaging_disruption.ipynb` → Main notebook with preprocessing, training, and evaluation  
- `packaging_center_records.csv` → Dataset (numeric + categorical)  

## 📬 **Contact**  
📧 amirhossin6825@gmail.com  
💬 Telegram: @AmirHossin6825 
