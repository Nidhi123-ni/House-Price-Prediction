# 🏠 House Price Prediction Using Deep Learning

## 📌 Overview

This project predicts house prices using a **Deep Neural Network (DNN)** built with TensorFlow and Keras. The model learns patterns from housing data and uses property-related features to estimate house prices.

The project demonstrates data preprocessing, feature scaling, categorical encoding, neural network training, model evaluation, and predictions on sample house data.

## 🎯 Objectives

- Build a Deep Learning model for house price prediction.
- Understand data preprocessing and feature engineering.
- Implement a neural network using TensorFlow/Keras.
- Evaluate model performance using Mean Absolute Error (MAE) and Mean Squared Error (MSE).
- Generate predictions for sample house inputs.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras

## 📊 Dataset

The project uses housing data containing features related to property size, facilities, and furnishing status.

Example features include:

- Area
- Number of bedrooms
- Number of bathrooms
- Number of stories
- Main road access
- Guest room availability
- Basement availability
- Air conditioning
- Parking spaces
- Preferred area
- Furnishing status

**Target variable:** House price

## ⚙️ Project Workflow

1. Load and explore the housing dataset.
2. Separate input features and the target variable.
3. Preprocess numerical and categorical features.
4. Apply feature scaling and one-hot encoding where required.
5. Build a Deep Neural Network using TensorFlow/Keras.
6. Train the model on the prepared data.
7. Evaluate predictions using MAE and MSE.
8. Provide sample house details and generate a predicted price.

## 🧠 Model Architecture

The Deep Neural Network uses the following architecture:

| Layer | Configuration |
|---|---|
| Input | Preprocessed housing features |
| Hidden Layer 1 | 64 neurons, ReLU activation |
| Hidden Layer 2 | 32 neurons, ReLU activation |
| Hidden Layer 3 | 16 neurons, ReLU activation |
| Output Layer | 1 neuron, linear activation |

**Optimizer:** Adam  
**Loss Function:** Mean Squared Error (MSE)

*Note: This architecture describes the model configured in the notebook. Update it if your actual implementation differs.*

## 📈 Model Evaluation

The model is evaluated using:

- **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted prices.
- **Mean Squared Error (MSE):** Measures the average squared prediction error, giving greater weight to larger errors.

Add your actual evaluation results here after running the notebook:

- MAE: `Your actual MAE value`
- MSE: `Your actual MSE value`

Lower values generally indicate smaller prediction errors when comparing models on the same dataset and target scale.

## 🔍 Sample Prediction

The trained model is used to predict the price of a sample house using its property features.

The notebook demonstrates how to prepare new input data, apply the same preprocessing used during training, and generate a price prediction.

Add a sample input and its predicted price here using the actual output from your notebook.


## 📚 Learning Outcomes

Through this project, I practiced:

- Data preprocessing and feature engineering.
- Numerical feature scaling and categorical encoding.
- Building and training a Deep Neural Network.
- Using TensorFlow/Keras for regression tasks.
- Evaluating model performance using MAE and MSE.
- Making predictions on new sample inputs.

## 👩‍💻 Author

**Nidhi Kumari**

GitHub: [Nidhi123-ni](https://github.com/Nidhi123-ni)

---

