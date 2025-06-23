#  Data Cleaning & Preprocessing – Titanic Dataset

Link for google colab : https://colab.research.google.com/drive/1rnfrIVh-skQbQ7XpmfxuvKIYz-QYubft?usp=sharing

## 📌 Objective
To clean and preprocess raw data using Python tools such as **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. This step is crucial for preparing data before feeding it into a machine learning model.

---

## 📊 Dataset Used
**Titanic - Machine Learning from Disaster**  
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Description: Predict survival on the Titanic and analyze what sorts of people were likely to survive.

---

## 🔧 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📝 Steps Performed

### 1. Data Exploration
- Loaded dataset using `pandas`
- Viewed data structure using `.info()`, `.describe()`, and `.head()`

### 2. Handling Missing Values
- Filled missing **Age** values with median
- Filled missing **Embarked** values with mode
- Dropped **Cabin** column due to high missing values

### 3. Encoding Categorical Features
- Converted `Sex` column using **Label Encoding**
- Converted `Embarked` column using **One-Hot Encoding**

### 4. Feature Scaling
- Standardized numerical features `Age` and `Fare` using `StandardScaler`

### 5. Outlier Detection and Removal
- Visualized outliers using **boxplots**
- Removed outliers in `Fare` column using **IQR method**

---


