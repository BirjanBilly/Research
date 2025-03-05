# Research
This public repository contains some of my research in data science applications to satellite telemetry and Earth energy budget data. 
The work could be visualised in the link below: 
https://colab.research.google.com/drive/1jOAdsBlqgNiYZoO70kzUK4-kvwg2JFdZ?usp=sharing

In this project, I developed a comprehensive machine learning framework to analyse the telemetry data(NASA, 2025) related to energy. This demonstrates my proficiency in statistical modelling and deep learning implementation. The PREFIRE(NASA, 2025) dataset with 11 features(beta angle, orbit positions and quaternions) is used to predict the latitude variable. These far‐infrared measurements help quantify how energy is absorbed, emitted, and redistributed on Earth in the form of radiation.

I started by preprocessing the dataset and normalising the features for more efficient training.

Using Ridge Regression, I created a predictive model to estimate the latitude from satellite telemetry data, after optimising hyperparameters to strengthen the model accuracy. Additionally, I applied Logistic Regression for categorical latitude classification, achieving high accuracy by improving the feature selection process and applying standardised scaling methods.

Expanding upon traditional methods, I built and trained deep learning models using PyTorch, using fully connected multi-layer perceptrons with ReLU activations and dropout regularisation to improve generalization. I leveraged GPU acceleration to train models over multiple epochs, monitoring performance through the loss and accuracy plots. Additionally, I evaluated model effectiveness using R-squared scores, mean squared error, and classification accuracy, iteratively tuning the hyperparameters to improve the model performance.

By exploring various regression techniques and deep learning architectures, this project demonstrates my ability to apply advanced machine learning methods to real-world predictive modelling tasks, which could be used in geospatial analysis, physical research of the climate, and other data-driven decision-making.
