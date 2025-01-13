Diabetes Prediction Using ANN
This repository contains the code and documentation for building an Artificial Neural Network (ANN) to predict diabetes progression based on clinical and diagnostic data. The project leverages Python libraries such as TensorFlow, scikit-learn, pandas, matplotlib, and seaborn to preprocess data, analyze features, train a model, and evaluate its performance.

Key Features
1. Loading and Preprocessing
Load the Diabetes dataset from sklearn.datasets and check for missing values and handle them if present. further, the features were normalised using StandardScaler to improve model performance.
2. Exploratory Data Analysis (EDA)
Performed EDA to understand the dataset and the target variable and Visualised feature distributions and relationships using plots (e.g., histograms, scatter plots, and heatmaps).
3. Building the ANN Model
Created a Sequential ANN with at least one hidden layer and used appropriate activation functions (e.g., ReLU for hidden layers).
4. Training the ANN Model
Splitted the dataset into training and testing sets and trained the ANN using an appropriate optimizer (e.g., Adam) and loss function (e.g., Mean Squared Error for regression).
5. Evaluating the Model
Evaluated the model's performance on the test data and reported performance metrics such as Mean Squared Error (MSE) and R² Score.
6. Improving the Model
Experimented with different model architectures, activation functions, and hyperparameters and finally, compared performance metrics before and after optimization.
