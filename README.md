# Gaussian process

This notebook demonstrates the use of Gaussian Process Regression (GPR) for modeling and predicting a synthetic dataset. The steps include:

1. **Synthetic Data Generation**:
    - A true generative function `f(x) = x * sin(x)` is defined and plotted.
    - A few data points are sampled from this function to serve as training data.

2. **Gaussian Process Regression (Noise-Free)**:
    - A Gaussian Process model with an RBF kernel is trained on the noise-free training data.
    - The model's predictions, along with a 95% confidence interval, are plotted against the true function.

3. **Gaussian Process Regression (With Noise)**:
    - Noise is added to the training data to simulate real-world scenarios.
    - The Gaussian Process model is retrained, incorporating the noise variance using the `alpha` parameter.
    - Predictions and confidence intervals are plotted for the noisy dataset.

The notebook provides a clear visualization of how Gaussian Processes can model data with and without noise, showcasing their flexibility and predictive power.

Signal to predict

![image](https://github.com/user-attachments/assets/319b6841-9f3f-401d-b581-3acb96028263)


Gaussian process regression without and with noise

![image](https://github.com/user-attachments/assets/31123d13-5060-4c44-8d1d-3835b83630fd)

![image](https://github.com/user-attachments/assets/c56fd693-cf76-4c84-98e7-acf03219337a)


