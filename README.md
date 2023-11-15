# Visualizing Machine Learning: From Linear Regression to Non-Linear SVMs

This repository showcases a series of Python scripts and GIF visualizations designed to demonstrate fundamental machine learning concepts. The focus is on visual clarity and practical understanding, with each script corresponding to a key ML problem. Here's what you can expect:

1. Linear Regression Visualization: Demonstrates the basics of linear regression using a cloud of data points. This script iteratively fits a linear model to the data, updating the model with each new point and visualizing the changing regression line.
2. Binary Classification with Linear SVM: Explores binary classification by using a linear Support Vector Machine (SVM) to find the optimal line that separates two sets of data points.
3. Limitation of Linear Models - The XOR Problem: Highlights the limitations of linear classifiers by attempting (and failing) to solve the XOR problem with a linear SVM, thereby showcasing the need for non-linear models in certain scenarios.
4. Solving XOR with Non-linear SVM: Resolves the XOR challenge using an SVM with a Radial Basis Function (RBF) kernel, illustrating how non-linear models can successfully tackle problems where linear models fall short.

Each step is complemented by a dynamic GIF that visualizes the process, making the learning experience more engaging and insightful. You are encouraged to dive into the code, tweak parameters, and observe firsthand how different models behave under various conditions.

## Step 1: Linear Regression Visualization

### Overview:
Step 1 in this repository focuses on the foundational concept of linear regression. It presents an interactive Python script that incrementally fits a linear model to a set of uniformly distributed data points.

### How It Works:

    The script generates a cloud of data points spread uniformly along a line with some added random noise.
    A linear regression model is then iteratively applied to this data. With each iteration, the model includes one additional data point from the set.
    After incorporating each new point, the regression line updates, reflecting the model's changing understanding of the data.

### Visualization:
The key highlight is the dynamic GIF that visualizes this process. As you watch the GIF, you'll see the linear regression line adjusting with each new data point, providing a clear visual representation of how linear regression models adapt and find the best-fit line through data. The GIF effectively demonstrates the convergence of the model as more data is considered.

### Exploration Encouraged:
Users are encouraged to play with the data generation parameters to see how different distributions of data points affect the regression line. Alter the noise level or the spread of the data points to observe how robustly the linear regression model adapts to these changes.

![linear_regression](https://github.com/DataScienceFH/ML_Visualizing_Problems/assets/129044997/99ecce12-2d5e-468b-b487-593057ee3c31)

This step serves as an excellent starting point for understanding machine learning's approach to finding patterns and trends in data.
