# 📘 Machine Learning 

## 📌 Project Overview
This repository contains a complete learning path for **data science** and **machine learning** with **Python**, organized into **4 main sub-projects**.  
Each sub-project covers specific and progressive concepts.

---

## 📂 Sub-Project Structure

### 1. 📊 `pandas_tuto` - Pandas Fundamentals
**Goal**: Mastering the **pandas** library for data manipulation.  

**Concepts learned:**
- Data reading: `pd.read_csv()`, `pd.read_excel()`
- DataFrame creation: from dictionaries, list of tuples, list of dictionaries
- Data manipulation:
  - Handling missing values: `fillna()`, `dropna()`, `ffill()`
  - Type conversion with `pd.to_datetime()`
  - Data export with `to_csv()`
- Advanced parameters: `skiprows`, `header`, `names`, `nrows`, `na_values`

**Main files:**
- `pandas.ipynb`: Complete introduction to pandas  
- `Tutorial 3.ipynb`: Different methods for DataFrame creation  
- `Tutorial 4.ipynb`: Reading/writing Excel and CSV files  
- `Tutorial 5.ipynb`: Handling missing data  
- `weather_data.csv/xlsx`: Weather dataset for exercises  

**Dataset used:** Weather data (`day`, `temperature`, `windspeed`, `event`)

---

### 2. 📈 `linear_regression_one_value` - Simple Linear Regression
**Goal**: Understanding linear regression with a single variable.  

**Concepts learned:**
- Modeling: `LinearRegression()` from scikit-learn  
- Training: `model.fit(X, y)` with one feature  
- Prediction: `model.predict()` for new values  
- Visualization: Scatter plots with matplotlib  
- Model saving: Using **pickle** to persist models  
- Regression equation: `price = m * area + b`

**Main files:**
- `linear regression.ipynb`: Basic tutorial on simple linear regression  
- `exercice.ipynb`: Practical exercises  
- `canada_per_capita_income.csv`: Dataset on per capita income  
- `house_prediction_model.pkl`: Saved model  

**Dataset used:** House prices based on area (`area`, `price`)

---

### 3. 🏠 `linear_regression_multi-variable` - Multiple Linear Regression
**Goal**: Extending linear regression to multiple variables.  

**Concepts learned:**
- Multiple variables: Using several features (`area`, `bedrooms`, `age`)  
- Preprocessing:
  - Handling NaN values with median  
  - Converting text to numbers with **word2number**  
  - Using `isinstance()` to check data types  
- Advanced modeling: `rg.fit(df[['area','bedrooms','age']], df.price)`  
- Coefficients: Understanding `rg.coef_` and `rg.intercept_`  
- Predictions: Salary prediction based on experience, test score, and interview score  

**Main files:**
- `tuto_01.ipynb`: Multiple regression tutorial  
- `exercice.ipynb`: Salary prediction exercise  
- `homeprices.csv`: House price dataset with multiple features  
- `hiring.csv`: Dataset for salary prediction exercise  

**Datasets used:**
- `homeprices.csv`: (`area`, `bedrooms`, `age`, `price`)  
- `hiring.csv`: (`experience`, `test_score`, `interview_score`, `salary`)  

---

### 4. 🔥 `one_hot_encoder` - Encoding & Classification
**Goal**: Handling categorical variables and binary classification.  

**Concepts learned:**
- One-Hot Encoding: `pd.get_dummies()` for categorical variables  
- Concatenation: `pd.concat()` to merge DataFrames  
- Column removal: `drop()` for redundant variables  
- Logistic Regression: Binary classification with `LogisticRegression()`  
- Train/Test Split: `train_test_split()` for model evaluation  
- Metrics: `model.score()` and `predict_proba()` for performance evaluation  
- Predictions: Predicting car prices and insurance purchase likelihood  

**Main files:**
- `OHe_01.ipynb`: One-Hot Encoding tutorial  
- `exercice.ipynb`: Car price prediction exercise  
- `Logistic Regression (Binary Classification).ipynb`: Binary classification  
- `Training And Testing Available Data.ipynb`: Model validation  

**Datasets used:**
- `carprices.csv`: (`Car Model`, `Mileage`, `Sell Price`, `Age`) - 3 car brands  
- `insurance_data.csv`: (`age`, `bought_insurance`) - Insurance data  
- `homeprices.csv`: House prices by city  

---

## 🛠️ Technical Skills Acquired
### 🐍 Python & Libraries
- **Pandas**: Complete DataFrame manipulation  
- **NumPy**: Numerical computations  
- **Matplotlib**: Data visualization  
- **Scikit-learn**: Machine Learning (`LinearRegression`, `LogisticRegression`)  
- **Pickle**: Model persistence  

### 📊 Data Science
- Preprocessing: Missing values handling, type conversion  
- Feature Engineering: One-Hot Encoding, variable creation  
- Modeling: Simple & multiple linear regression, logistic classification  
- Evaluation: Train/test split, performance metrics  
- Visualization: Scatter plots, exploratory analysis  

### 🔧 Tools & Methods
- **Jupyter Notebooks**: Interactive development  
- **Project Management**: Modular structure & documentation  
- **Version Control**: Git for version tracking  
- **Virtual Environment**: Dependency isolation  

---

## 🚀 Learning Path Progression
1. **Fundamentals (`pandas_tuto`)** → Basic data manipulation  
2. **Simple Regression (`linear_regression_one_value`)** → Single-variable prediction  
3. **Multiple Regression (`linear_regression_multi-variable`)** → Multi-variable prediction  
4. **Classification (`one_hot_encoder`)** → Categorical data handling & classification  

---

## 💡 Use Cases
- Predicting house prices based on area, bedrooms, and age  
- Predicting salaries from experience, test score, and interview score  
- Predicting car prices based on brand, mileage, and age  
- Insurance purchase classification based on client age  

---

## ⚙️ Technologies & Dependencies
- **Python 3.12**  
- **Pandas 2.3.2**  
- **Scikit-learn**  
- **Matplotlib**  
- **NumPy**  
- **OpenPyXL** (Excel support)  
- **word2number** (text → number conversion)  
