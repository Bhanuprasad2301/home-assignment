This Source code demonstrates **linear regression** implemented in two ways:

* **Closed-Form Solution (Normal Equation)** – Calculates model parameters analytically using

  $$
  \theta = (X^TX)^{-1}X^Ty
  $$
* **Gradient Descent Optimization** – Iteratively updates parameters to minimize Mean Squared Error (MSE).

## Features

* **Synthetic Data Generation**: Creates data based on $y = 3 + 4x + \text{noise}$
* **Closed-Form Solution**: Computes optimal intercept and slope directly
* **Gradient Descent**: Custom implementation with configurable learning rate & iterations
* **Visualization**:

  * Scatter plot of generated data
  * Regression lines from both methods for comparison
  * Loss curve showing MSE reduction over time

## Results

* Shows that both methods converge to nearly the same parameters
* Gradient descent demonstrates how optimization works step-by-step

## Requirements

* Python 3.x
* `numpy`
* `matplotlib`

Install dependencies with:

```bash
pip install numpy matplotlib
```

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook "Machine learning assignment.ipynb"


* A plot comparing both regression lines
* A loss curve for gradient descent
* Printed intercept and slope values from both methods
