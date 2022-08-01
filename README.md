# Linear regression with syntheic data

## Intro

Learning objectives:
* Run Colabs.
* Tune the following hyperparameters:
  * learning rate
  * number of epochs
  * batch size
* Interpret different kinds of loss curves.

## Usage

### Running code cells
You must run code cells in order. In other words, you may only run a code cell once all the code cells preceding it have already been run.

To run a code cell:

1. Place the cursor anywhere inside the [ ] area at the top left of a code cell. The area inside the [ ] will display an arrow.
2. Click the arrow.
Alternatively, you may invoke Runtime->Run all. Note, though, that some of the code cells will fail because not all the coding is complete.

### Why did you see an error?
If a code cell returns an error when you run it, consider two common problems:

1. You didn't run all of the code cells preceding the current code cell.
2. If the code cell is labeled as a Task, then you haven't written the necessary code.

### Use the right version of TensorFlow
The following hidden code cell ensures that the Colab will run on TensorFlow 2.X, which is the most recent version of TensorFlow:
```python 
%tensorflow_version 2.x
```

## Definition

### 1. Build and train a model function
```build_model(my_learning_rate)```, which trains the model from the examples (feature and label) you pass.

```train_model(model, feature, label, epochs)```, which trains the model from the examples (feature and label) you pass.

### 2. Plotting function
We're using a popular Python library called Matplotlib to create the following two plots:
```plot_the_model(trained_weight, trained_bias, feature, label)```, a plot of the feature values vs. the label values, and a line showing the output of the trained model.

```plot_the_loss_curve(epochs, rmse)```,a loss curve.

## Document
[Copyright 2020 Google LLC](https://colab.research.google.com/github/google/eng-edu/blob/main/ml/cc/exercises/linear_regression_with_synthetic_data.ipynb?utm_source=mlcc&utm_campaign=colab-external&utm_medium=referral&utm_content=linear_regression_synthetic_tf2-colab&hl=en#scrollTo=wDlWLbfkJtvu)
