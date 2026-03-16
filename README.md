# House-Price-Predictor-ML-Model
This project implements a basic machine learning model to predict housing prices using the California Housing dataset. The goal of the project is to demonstrate a complete machine learning workflow, including data exploration, preprocessing, model training, and evaluation.

The project uses structured housing data derived from the 1990 U.S. Census. It includes features such as median income, house age, total rooms, population, and geographical information. These features are used to train a regression model that predicts the median house value of a district.

Dataset Files
california_housing_data.csv*
This dataset contains housing information collected during the 1990 U.S. Census. It is used in this project to train and test the housing price prediction model.


### Features in the Dataset

- **Median Income** – Median income of households in the district.
- **Housing Median Age** – Median age of houses in the district.
- **Total Rooms** – Total number of rooms across all houses in the district.
- **Total Bedrooms** – Total number of bedrooms across all houses in the district.
- **Population** – Total population living in the district.
- **Households** – Total number of households in the district.
- **Latitude** – Geographical latitude coordinate of the district.
- **Longitude** – Geographical longitude coordinate of the district.
- **Median House Value (Target Variable)** – Median value of houses in the district, which the model aims to predict.


anscombe.json
Contains Anscombe’s Quartet, a classic dataset used in statistics to demonstrate the importance of data visualization when interpreting statistical data.

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## Machine Learning Workflow

1. **Data Loading** – Import the housing dataset and inspect its structure.
2. **Exploratory Data Analysis (EDA)** – Analyze feature distributions and relationships between variables.
3. **Data Preprocessing** – Handle missing values and prepare features for model training.
4. **Feature Selection** – Identify the most relevant variables influencing housing prices.
5. **Model Training** – Train a regression-based machine learning model using the training dataset.
6. **Model Evaluation** – Evaluate model performance using appropriate evaluation metrics.
7. **Prediction** – Use the trained model to predict housing prices based on input features.

