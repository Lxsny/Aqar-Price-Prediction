# 🏠 Aqar-Price-Prediction

A machine learning project that analyzes real estate data from the Saudi Aqar market to estimate property prices based on key features such as size, rooms, which district, etc...

## 🛠️ Technologies

- **Language:** Python 
- **Libraries:** Pandas, NumPy, Scikit-Learn
- **Visualization:** Matplotlib
- **Environment:** Jupyter Notebook / Google Colab

## ⚙️ Approach

- **Data Cleaning:** Processed the dataset by handling missing values and ensuring consistency across all features.
- **Outlier Handling:** Used the Interquartile Range (IQR) technique to filter abnormal property prices and improve model stability.
- **Feature Engineering:** Reduced noise by grouping less frequent districts into a single category to avoid overfitting.
- **Encoding:** Applied One-Hot Encoding (with drop_first=True) to convert categorical variables into numerical form while preventing redundancy.
- **Modeling:** Built a Linear Regression model to learn the relationship between property attributes and price, allowing for interpretable predictions.

## 📊 Results

The model demonstrated strong performance in predicting property prices:
- **Training R² Score:** 0.81+
- **Testing R² Score:** 0.82+
- **Model Insight:** Error distribution analysis showed balanced residuals, indicating the model generalizes well and captures realistic pricing patterns.

## 👥 Team Penta's Members
- **Abdullah bin Maneea [ Leader ]**
- **Abdullah AlOud**
- **Faris Abuthnain**
- **Mohammad Alaqid**
- **Malik Alhabashi**
