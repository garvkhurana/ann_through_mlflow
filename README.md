# ann_through_mlflow

Artificial Neural Network (ANN) with Hyperparameter Tuning

Overview

This project implements an Artificial Neural Network (ANN) for predictive modeling and optimizes its hyperparameters using Hyperopt. The workflow includes data preprocessing, model training, hyperparameter tuning, and tracking experiments with MLflow.

Features

Built an ANN model using TensorFlow and Keras

Applied Hyperopt for hyperparameter optimization

Used MLflow for experiment tracking and model logging

Preprocessed data using pandas and NumPy

Evaluated performance using Mean Squared Error (MSE)

Libraries Used

pandas – Data manipulation and preprocessing

NumPy – Numerical operations

TensorFlow & Keras – Building and training the ANN model

Hyperopt – Bayesian optimization for hyperparameter tuning

sklearn.metrics – Model evaluation (MSE)

sklearn.model_selection – Train-test splitting

MLflow – Tracking experiments and logging models

Workflow

Data Preprocessing – Loaded and prepared the dataset using pandas and NumPy.

Model Creation – Defined an ANN architecture using TensorFlow/Keras.

Hyperparameter Tuning – Used Hyperopt to find the best ANN parameters.

Evaluation – Assessed model performance using mean_squared_error.

Experiment Tracking – Logged results, parameters, and models with MLflow.

Results

Found the optimal ANN hyperparameters using Bayesian optimization.

Improved model performance with fine-tuned hyperparameters.

Logged and stored the trained models for reproducibility.

Conclusion

This project showcases how ANNs can be efficiently optimized using Hyperopt and tracked with MLflow, ensuring better model performance and reproducibility.

Happy Experimenting with ANN & MLflow! 🚀

