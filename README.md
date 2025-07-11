Fertilizer Prediction using Machine Learning

This project uses machine learning models to predict the type of fertilizer based on agricultural inputs like district name, soil color, crop type, and nutrient values. It explores basic preprocessing, model building, evaluation, and making predictions.

Overview
The notebook walks through the following steps:

1. Data Loading
Loads a dataset called Crop_and_fertilizer_with_usage.csv containing information about crops, fertilizers, and related features.

2. Exploratory Analysis
Displays basic information, summary statistics, and unique values from key columns.

3. Data Preprocessing
Handles categorical columns like District_Name, Soil_color, Crop, and Link using Label Encoding.
Splits the data into features (X) and target (Fertilizer).

4. Model Training
Trains three different classifiers:

a. Logistic Regression
b. Decision Tree
c. K-Nearest Neighbors

5. Evaluation
Uses classification reports (precision, recall, F1-score) to compare model performance.

6. Prediction
Makes a prediction using the KNN model with a manually provided sample input.

How to Use?
Open the Jupyter Notebook modelprediction.ipynb.
Ensure the dataset Crop_and_fertilizer_with_usage.csv is in the correct path.
Run the cells step by step to preprocess data, train models, evaluate, and make predictions.

Modify the input sample to test predictions on your own values.

Notes
The model expects encoded input values, so input features must follow the same preprocessing steps.
You can modify the dataset or model parameters to improve accuracy or adapt to different crops or regions.

Run the requirements.txt after cloning by using
```pip install -r requirements.txt```

Or run the following line of code in ur environment cmd

```pip install pandas numpy scikit-learn matplotlib seaborn```



