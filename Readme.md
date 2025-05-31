# Weather Forecasting with RNN (PyTorch)

This project uses a Recurrent Neural Network (RNN) built with PyTorch to predict temperature based on historical weather data. It demonstrates a complete machine learning pipeline from preprocessing and modeling to evaluation and visualization.


## Features

- Multivariate weather data input (e.g., humidity, wind, pressure, etc.)
- Target: Predict future **temperature**
- Uses `nn.RNN` in PyTorch with multiple hidden layers
- Feature scaling using `StandardScaler`
- Model training, evaluation, and prediction


## Tech Stack

- Python
- PyTorch
- NumPy
- Pandas
- scikit-learn


## Model Architecture

- Input size: Depends on number of features (e.g., 17)
- RNN hidden layers: 2
- Activation function: `tanh`
- Fully connected (dense) layers after RNN output
- Loss function: MSELoss (regression)
- Optimizer: Adam


