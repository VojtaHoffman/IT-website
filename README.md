# PreDigit
PreDigit is a web application that allows users to draw digits on a canvas and have them recognized by a machine learning model. The application uses TensorFlow.js to load and run the model, which was trained on the MNIST dataset of handwritten digits.

## Getting Started
To run the application, simply open the index.html file in a web browser. The application should load and display a canvas element for the user to draw on.

## Usage
To use the application, follow these steps:
1. Draw a digit on the canvas using your mouse or touch screen.
2. Click the "Recognize" button to have the model predict the digit.
3. The predicted digit and the model's confidence score for each digit will be displayed in a bar chart.

## Dependencies
The application requires the following dependencies:
* jQuery 3.3.1
* Chart.js 2.9.4
* TensorFlow.js 3.0.0
* Bootstrap 4.3.1
* These dependencies are included in the js and style directories of the project.

## Acknowledgments
This project was inspired by the TensorFlow.js MNIST demo and the following resources:
* [TensorFlow.js: Machine Learning for the Web and Beyond](https://www.tensorflow.org/js)
* [Getting Started with TensorFlow.js](https://www.tensorflow.org/js/tutorials)
* [Building a Handwritten Digits Recognizer in JavaScript with TensorFlow.js](https://codelabs.developers.google.com/codelabs/tfjs-training-classfication#0)
