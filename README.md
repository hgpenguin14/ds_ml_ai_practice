# Data Science, Machine Learning & AI Practice

A collection of selected data science, machine learning, and AI projects from my graduate coursework and independent study.

The projects in this repository have been reviewed and reorganized to focus on the main analytical methods, implementation, and results.

## Projects

### CIFAR-10 Image Classification with FNN and CNN

Image classification using the CIFAR-10 dataset, comparing a feedforward neural network (FNN) baseline with a convolutional neural network (CNN).

**Topics:**

- Image preprocessing and one-hot encoding
- Feedforward neural network (FNN)
- Convolutional neural network (CNN)
- Training and validation performance analysis
- Overfitting diagnosis using learning curves
- Early stopping and model comparison

**Tools:** Python, NumPy, Matplotlib, TensorFlow, Keras

[View project](./CIFAR-10-NN/)

### Fashion-MNIST Representation Learning and Classification

Representation learning and image classification using the Fashion-MNIST dataset, comparing SOM, RBM, and VAE for dimensionality reduction and latent feature extraction.

**Topics:**

- Image preprocessing and feature normalization
- Self-Organizing Map (SOM) representation learning
- Restricted Boltzmann Machine (RBM) feature extraction
- Variational Autoencoder (VAE) with reparameterization
- Image reconstruction from latent representations
- Random Forest and AdaBoost classification
- Classification performance and computational efficiency comparison
- VAE stability analysis with repeated training experiments

**Tools:** Python, NumPy, Pandas, Matplotlib, TensorFlow, Keras, scikit-learn, MiniSom

[View project](Fashion-MNIST/Fashion-MNIST-VAE.ipynb)

### California Housing Price Prediction with XGBoost

Regression modeling on the California Housing dataset, comparing a linear regression baseline with XGBoost and analyzing the effects of key boosting hyperparameters.

**Topics:**

- Regression modeling and train/test evaluation
- Linear regression baseline
- XGBoost regression
- MAE and MSE model comparison
- Ensemble size analysis
- Learning rate analysis and hyperparameter tuning

**Tools:** Python, Pandas, Matplotlib, scikit-learn, XGBoost

[View project](./XGBoost/)

### California Housing Price Prediction

Exploratory data analysis and linear regression using the California Housing dataset.

**Topics:**

- Data exploration with Pandas
- Correlation analysis and visualization
- Linear regression
- Feature selection and multicollinearity
- Model evaluation using MAE, RMSE, and R²
- Comparison of single-feature, baseline, and reduced models

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

[View project](./california_housing_analysis/)
