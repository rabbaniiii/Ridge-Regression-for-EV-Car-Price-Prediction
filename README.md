# Ridge Regression - EV Price Prediction

## 📌 About the Project

This project uses **Ridge Regression** to predict the price of electric vehicles (EVs).

The model uses different EV specifications such as **brand, model, range, power, and battery capacity** to predict the vehicle price.

## 🎯 Objective

The main objective of this project is to understand how **Ridge Regression** can be used for a simple machine learning prediction problem.

The project includes data preprocessing, feature encoding, feature scaling, model training, prediction, and evaluation.

## 📊 Dataset

The dataset contains **26 electric vehicle records** and 6 columns.

The columns are:

* **Brand** – EV manufacturer
* **Model** – EV model
* **Price** – Price of the vehicle
* **Range** – Driving range
* **Power** – Vehicle power
* **Battery** – Battery capacity

The **Price** column is used as the target variable.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## ⚙️ Machine Learning Process

The following steps are performed in the project:

1. Load the EV dataset.
2. Explore the dataset using Pandas.
3. Check the number of rows and columns.
4. Check for missing values.
5. Separate the features and target variable.
6. Identify categorical and numerical columns.
7. Convert categorical data using **OneHotEncoder**.
8. Scale numerical data using **StandardScaler**.
9. Split the dataset into training and testing data.
10. Build a **Ridge Regression** model.
11. Train the model.
12. Predict EV prices.
13. Evaluate the model using different metrics.

## 🤖 Model Used

### Ridge Regression

Ridge Regression is a type of linear regression that uses regularization.

In this project, different `alpha` values are considered for the Ridge model.

```text
0.01
0.1
1
10
100
```

## 📈 Model Evaluation

The model uses the following evaluation metrics:

* **MAE (Mean Absolute Error)**
* **RMSE (Root Mean Squared Error)**
* **R² Score**

These metrics help measure how well the model predicts EV prices.

## 📁 Project Files

```text
Ridge_Regression.ipynb
ev_car_India_dataset.csv
README.md
```

### Ridge_Regression.ipynb

Contains the complete Python code and machine learning workflow.

### ev_car_India_dataset.csv

Contains the electric vehicle dataset used for training and testing.

## 🚀 How to Run

1. Open the `Ridge_Regression.ipynb` file in **Google Colab**.
2. Upload the `ev_car_India_dataset.csv` dataset.
3. Run the notebook cells in order.
4. The model will train and generate prediction and evaluation results.

## 📚 Learning Outcome

Through this project, I learned how to:

* Work with a real-world dataset.
* Explore and prepare data using Pandas.
* Handle categorical and numerical features.
* Use `OneHotEncoder` and `StandardScaler`.
* Split data into training and testing sets.
* Build a Ridge Regression model.
* Make predictions using a machine learning model.
* Evaluate regression models using MAE, RMSE, and R².

## 👨‍💻 Author

**K Mushtaaqh Rabbani**

