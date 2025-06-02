# Hand Gesture Classification with Machine Learning

This project implements machine learning models for hand gesture classification. It includes preprocessing of gesture data, model training, and evaluation using techniques like Support Vector Machines (SVM),Logistic Regression, Random Forest, and XGboost .

The project also incorporates **hyperparameter tuning** using **Optuna** to optimize model performance and achieve the best results.

## Features:
- **Preprocessing** of the Hand Gesture Dataset: Data is cleaned and transformed for better performance in classification.
- **Model Training**: Utilizes SVM, Logistic Regression, Random Forest, and XGboost for classification tasks.
- **Hyperparameter Tuning**: Implements Optuna to optimize hyperparameters for each model.
- **Model Evaluation**: Evaluates models using key metrics such as:
  - **Accuracy**
  - **Precision**
  - **F1-score**

The goal of this project is to classify hand gesture images accurately and efficiently using machine learning techniques, and to showcase the impact of hyperparameter optimization on model performance.

## Why XGboost is the model choosen ?

Best Performing Model Based on the evaluation metrics, the Optimized XGBoost model outperformed the other models with the highest accuracy, precision, recall, and F1-score. The optimized XGBoost achieved:

Accuracy: 0.9733

Precision: 0.9736

Recall: 0.9733

F1-score: 0.9734

This makes XGBoost the best performing model for hand gesture classification in this project.

## Project Demo Video

You can view the demo video of the Hand Gesture Classification project below:

[![Watch the video](https://yourdomain.com/thumbnail.jpg)](https://drive.google.com/file/d/1z-bhjuNZE_OnqxmvvUxLM7anYrn1LoS2/view?usp=sharing)

## Get started :
1. Clone the Repository + also you need an input video (containing the Gestures you need to recognize)
2. Install the Required Dependencies
pip install numpy pandas scikit-learn xgboost opencv-python optuna matplotlib seaborn
3. Run
