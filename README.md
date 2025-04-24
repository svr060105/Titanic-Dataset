# Titanic Dataset - Data Cleaning & Preprocessing

## 📌 Objective
This project demonstrates how to clean and prepare the **Titanic Dataset** for machine learning. It involves:
- handling missing values
- encoding categorical features
- scaling numerical values
- removing outliers.

---

## 🔧 Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn

---

## 📊 Steps Performed

### 1. Data Import & Exploration
- Loaded the dataset using `pandas`.
- Explored structure using `.head()`, `.info()`, `.describe()`.
- Identified missing values with `.isnull().sum()`.

### 2. Handling Missing Values
- Dropped the `Cabin` column (too many missing values).
- Imputed `Age` with the **mean**.
- Imputed `Embarked` with the **mode**.

### 3. Encoding Categorical Variables
- Conversion `Sex` into binary values (`male` → 0, `female` → 1).
- Applied **one-hot encoding** on `Embarked`.

### 4. Feature Scaling
- Standardized `Age` and `Fare` using `StandardScaler`.

### 5. Outlier Detection & Removal
- Visualized outliers using **boxplots**.
- Removed outliers in `Age` and `Fare` using the **IQR method**.

---

## 💾 Output
Cleaned dataset saved as Titanic-Datasset-cleaned.csv

---

