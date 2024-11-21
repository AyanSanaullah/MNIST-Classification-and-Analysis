# MNIST-Classification-and-Analysis
This project focuses on exploring and classifying the MNIST dataset using Python and key libraries such as NumPy, Matplotlib, and Keras.

MNIST Classification and Analysis
This project demonstrates a binary classification approach using the MNIST dataset. The code filters and classifies digits 0 and 8 based on their center pixel averages. It includes data visualization, feature engineering, and a simple threshold-based classifier.

Features
Data Visualization: Displays example MNIST images and their labels.
Binary Classification: Focuses on distinguishing between digits 0 and 8.
Feature Engineering: Computes the center pixel average of images as a distinguishing feature.
Threshold-Based Classification: Implements a straightforward method for classifying digits based on the computed feature.
Results
Metric	Accuracy
Training	~25.2%
Validation	~26.2%
Testing	~26.8%
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/CAP4613_Assignment4.git
Navigate to the project directory:
bash
Copy code
cd CAP4613_Assignment4
Install required dependencies:
bash
Copy code
pip install numpy matplotlib tensorflow keras
Usage
Open the Jupyter Notebook CAP4613_Assignment4.ipynb.
Run the cells step by step to:
Visualize and explore the MNIST dataset.
Process data for binary classification.
Compute the feature (center pixel average).
Evaluate classification performance.
Project Structure
CAP4613_Assignment4.ipynb: The main notebook containing all code and analysis.
LICENSE: The project license (MIT License).
Future Work
Improve accuracy using advanced machine learning or deep learning methods.
Explore additional features and transformations for better distinction between digits 0 and 8.
Compare the current approach with neural network-based classifiers.
License
This project is licensed under the Apache License 2.0.
