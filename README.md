# Data-Cleaning-and-Preprocessing

This project is part of an AI & ML internship assignment. The objective is to learn how to clean and prepare raw data for machine learning by applying preprocessing techniques to the Titanic dataset.

## 📁 Dataset
- Dataset used: [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File: `Titanic-Dataset.csv`

## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn (for scaling)

## ✅ Steps Performed

1. **Data Loading**  
   Loaded the dataset and checked data types and missing values.

2. **Missing Value Treatment**  
   - Filled missing `Age` with median.
   - Filled missing `Fare` with mean.
   - Dropped rows with missing `Embarked`.

3. **Categorical Encoding**  
   - Converted `Sex` to numerical (`0` for male, `1` for female).
   - Applied one-hot encoding to `Embarked`.

4. **Feature Scaling**  
   - Standardized numerical features (`Age` and `Fare`) using `StandardScaler`.

5. **Outlier Detection and Removal**  
   - Visualized `Age` and `Fare` using boxplots.
   - Removed outliers using IQR (Interquartile Range) method.

## 📊 Final Output
Cleaned and preprocessed data ready for use in machine learning models.

## 📎 How to Run
1. Install requirements (if needed):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
