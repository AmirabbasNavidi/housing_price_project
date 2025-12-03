A machine learning project for predicting housing prices in California.

📌 Project Description

This project uses the California Housing dataset to predict house prices based on features such as population, average income, geographic location, total rooms, bedrooms, and more.
The goal is to build a clean, well-structured ML pipeline and compare multiple models.

📊 Project Steps

✔ Load and explore the dataset
✔ Data cleaning (handling missing values, fixing outliers)
✔ Feature engineering
✔ Train/Test splitting
✔ Data scaling and preprocessing
✔ Training different machine learning models, including:

Linear Regression

Decision Tree

Random Forest

✔ Model selection using GridSearchCV and Cross-Validation
✔ Model evaluation using RMSE and MSE

🧠 Best Model

RandomForestRegressor with RMSE ≈ 47,000

🗂 Feature Engineering

Some engineered features used in this project include:

Rooms per household

Rooms per person

Population density

Income-to-price ratio

Bedrooms per room

🗺 Data Visualization

A geographic scatter plot was used to visualize housing distribution across California.
Color represents median house value, and point size represents population.

🧪 Technologies Used

Python

NumPy

Pandas

Scikit-Learn

Matplotlib

Seaborn

Jupyter Notebook

📁 Project Files

housing.csv → dataset

housing-project.ipynb → main notebook

👤 Author

Amirabbas Navidi
A learning project focused on Machine Learning and Data Analysis 🌱
