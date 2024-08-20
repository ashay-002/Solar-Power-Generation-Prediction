# Solar-Power-Generation-Prediction


# Project Overview

This project aims to predict the amount of solar power generated using various machine learning models. By leveraging a dataset containing solar power generation data, we explore different preprocessing techniques and model architectures to enhance the accuracy of our predictions.

# Dataset

The dataset used in this project consists of solar power generation data, including various features that may influence the amount of power generated, such as weather conditions, time of day, and geographical location.

# Preprocessing Steps

The preprocessing steps are crucial for preparing the data before feeding it into the models. The following steps were applied across all models:

Data Cleaning: Handling missing values and outliers to ensure data quality.

Feature Engineering: Creating new features and selecting relevant ones to improve model performance.

Normalization/Standardization: Scaling features to a uniform range.

Boxcox Transformation: Applied to deal with skewness in the data.

Train-Validation Split: Dividing the dataset into training and validation sets for model evaluation.

# Model Architecture and Training

DLinear Model

Architecture: A DLinear model optimized for time series forecasting.

Training: The model was trained on the same preprocessed data, focusing on optimizing the time series aspects.

TCM Model

Architecture: The Temporal Convolutional Model (TCM) architecture was employed for this project.

Training: This model was trained similarly, with adjustments specific to temporal data.

Hybrid Model

Architecture: A hybrid approach combining both the TCM and DLinear Models.

Training: The model was trained on the preprocessed data and validated using the validation set.

# Results

Each model was evaluated based on its performance on the validation set. Metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) were used to assess the accuracy of predictions.

# Conclusion

The project successfully demonstrates the effectiveness of different machine learning models in predicting solar power generation. The choice of model can significantly impact the prediction accuracy, depending on the specific characteristics of the data.
