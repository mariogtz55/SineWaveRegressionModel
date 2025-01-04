# Sine Wave Regression Model

## Purpose

This code demonstrates how to build and train a simple neural network to predict the sine of a given input. It covers the following steps:

1. **Data Generation:** Generates sample data points representing a sine wave with added noise.
2. **Data Splitting:** Divides the data into training, validation, and testing sets.
3. **Model Building:** Creates a sequential neural network model using Keras.
4. **Model Training:** Trains the model using the training data and validates it using the validation set.
5. **Model Evaluation:** Evaluates the model's performance using the testing set.
6. **Model Conversion:** Converts the trained model to TensorFlow Lite format for mobile and embedded deployment.
7. **Model Optimization:** Quantizes the TensorFlow Lite model to reduce its size and improve performance.
8. **Model Comparison:** Compares the predictions of the original, TensorFlow Lite, and quantized TensorFlow Lite models.

## What was done

- A sine wave dataset was generated and split into training, validation, and testing sets.
- Two sequential neural network models were built and trained using Keras, with the second model having an additional hidden layer.
- The models were evaluated using metrics like mean squared error (MSE) and mean absolute error (MAE).
- The best performing model was converted to TensorFlow Lite format, both with and without quantization.
- The size difference between the original and quantized TensorFlow Lite models was compared.
- The predictions of all three models were visualized against the actual values.

This example showcases a basic machine learning workflow for regression tasks, including data preprocessing, model training, evaluation, and deployment optimization.
