# CodSoft-Task2
# Movie Rating Prediction

# Aim
The aim of this project is to build a model that predicts movie ratings based on given features.

# Libraries
The following important libraries were used for this project:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.preprocessing.LabelEncoder
- sklearn.preprocessing.MinMaxScaler
- sklearn.model_selection.train_test_split
- sklearn.linear_model.LogisticRegression

# Data Exploration and Preprocessing
- Database was loaded from a csv file
- The missing values in each DataFrame were dropped using dropna(inplace=True).
- The shape and descriptive statistics for each DataFrame were displayed using df.shape and df.describe().
- Data visualization was performed using count plots and histograms to gain insights.

# Model Training
- The feature matrix X and target vector y were created using relevant columns from the dataset MovieRating.
- The data was split into training and testing sets using train_test_split.
- The input data was scaled using MinMaxScaler to normalize the values between 0 and 1.

# Prediction
- A logistic regression model was initialized and trained on the training data using LogisticRegression.
- The model was used to predict movie ratings for the test set using model.predict(X_test).
