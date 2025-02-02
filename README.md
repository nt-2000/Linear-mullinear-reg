# **Linear Regression Analysis with Python (Iris & Insurance Dataset)**

## **Project Description**
This project applies **Linear Regression** and **Multiple Linear Regression** techniques using Python to analyze two datasets:
1. **Iris Dataset:** A simple linear regression model is built using petal length as the independent variable and petal width as the dependent variable.
2. **Insurance Dataset:** A multiple linear regression model is applied to predict medical charges based on various features such as age, BMI, and smoking status.

The project leverages **Seaborn, Matplotlib, Scikit-Learn, NumPy, and Pandas** for data analysis, visualization, and modeling.

---

## **Contents**
- `iris_regression.py` - Implementation of **simple linear regression** using the Iris dataset
- `insurance_regression.py` - Implementation of **multiple linear regression** using the Insurance dataset
- `README.md` - Project documentation
- **Generated Plots:**
  - `corr-fig.png` - Scatter plot showing correlation between petal length and petal width
  - `scatter-train.png` - Scatter plot of training data with fitted regression line
  - `scatter-test.png` - Scatter plot of test data with predictions
  - `multiple-train.png` - Scatter plot of predicted vs actual values for training data
  - `multiple-test.png` - Scatter plot of predicted vs actual values for test data

---

## **Installation and Setup**
### **Prerequisites**
Ensure you have Python 3 installed along with the required libraries. You can install the dependencies using:

```bash
pip install -r requirements.txt
```

### **Dataset Requirements**
- The **Iris dataset** is loaded directly from the Seaborn library.
- The **Insurance dataset** must be downloaded and placed in the appropriate directory. Ensure the dataset is available in this project folder itself.

## **Usage**
### **Running Simple Linear Regression (Iris Dataset)**
```bash
python iris_regression.py
```
- Loads the Iris dataset
- Selects `petal_length` as the independent variable and `petal_width` as the dependent variable
- Splits data into training and testing sets
- Fits a **Linear Regression model**
- Generates scatter plots and a fitted regression line

### **Running Multiple Linear Regression (Insurance Dataset)**
```bash
python insurance_regression.py
```
- Loads the **Insurance dataset**
- Encodes categorical variables (`sex`, `smoker`, `region`)
- Splits data into training and testing sets
- Fits a **Multiple Linear Regression model**
- Evaluates model accuracy using **R² Score**
- Generates scatter plots comparing actual and predicted values

---

## **Project Methodology**
### **1. Simple Linear Regression (Iris Dataset)**
- **Data Preparation:** Extracts `petal_length` and `petal_width`
- **Correlation Analysis:** Uses scatter plots and Pearson correlation
- **Model Training:** Fits a **Linear Regression model** using `train_test_split`
- **Predictions & Visualization:** Generates a regression line and compares predictions

### **2. Multiple Linear Regression (Insurance Dataset)**
- **Data Preparation:** Encodes categorical variables and handles missing values
- **Feature Selection:** Uses age, BMI, children, smoker status, etc.
- **Model Training:** Fits a **Multiple Linear Regression model** using `train_test_split`
- **Model Evaluation:** Uses **R² Score** to check accuracy

---

## **Results & Observations**
- **Iris Dataset:** A strong correlation exists between `petal_length` and `petal_width`, making it suitable for simple linear regression.
- **Insurance Dataset:** The model shows a strong relationship between `charges` and `smoker` status, BMI, and age, highlighting key factors influencing medical costs.

---

## **License**
This project is licensed under the **MIT License**.

---

## **Contributing**
Feel free to contribute by submitting issues or pull requests. If you find this project helpful, consider giving it a ⭐ on GitHub!

---

## **Contact**
For any queries, reach out via GitHub Issues.

Happy coding! 🚀

