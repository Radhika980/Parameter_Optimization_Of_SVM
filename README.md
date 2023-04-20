# Parameter_Optimization_Of_SVM
Assignment for UCS654

Support Vector Machines (SVMs) are powerful and versatile machine learning algorithms used for both classification and regression tasks. The main idea behind SVMs is to find the hyperplane that maximizes the margin between the different classes in the dataset.

When it comes to parameter optimization, SVMs have several parameters that can be fine-tuned to achieve better performance. Some of the important parameters include:

Kernel: SVMs use different types of kernels, such as linear, polynomial, radial basis function (RBF), and sigmoid, to transform the input data into a higher-dimensional space. Choosing the right kernel function can greatly impact the performance of the SVM.

Regularization parameter (C): This parameter controls the trade-off between maximizing the margin and minimizing the classification error. A large value of C will lead to a narrow margin and potentially overfitting, while a small value of C will lead to a wider margin and potentially underfitting.

Gamma parameter: This parameter is used in the RBF kernel and controls the shape of the decision boundary. A small value of gamma will lead to a more flexible decision boundary, while a large value of gamma will lead to a more rigid decision boundary.

Optimizing these parameters can be challenging and time-consuming, but it is crucial for achieving the best performance of the SVM. One common approach to optimize the parameters is to use a grid search, where a range of values for each parameter is specified, and the SVM is trained and evaluated for each combination of parameter values. Cross-validation is often used to prevent overfitting and ensure that the selected parameter values generalize well to new data.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset

This dataset is used for images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. A total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains. It is a multi-variate classification Dataset.

| Number of Instances:  | 13611 |
|-----------------------|--------|
| Number of Attributes: |  17 |



## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.77 | linear | 1.38 | 4.10 |
| 2 | 0.44 | linear | 1.24 | 5.82 |
| 3 | 0.48 | poly | 0.77 | 2.16 |
| 4 | 0.56 | linear | 1.27 | 1.27 |
| 5 | 0.38 | linear | 4.91 | 6.73 |
| 6 | 0.64 | poly | 1.05 | 6.93 |
| 7 | 0.40 | poly | 9.70 | 1.55 |
| 8 | 0.65 | linear | 6.10 | 4.47 |
| 9 | 0.37 | poly | 9.59 | 3.83 |
| 10 | 0.48 | poly | 2.02 | 4.64 |

## Convergence Graph
![graph]

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 1 has the best accuracy of 0.77 having kernel = linear, Nu = 1.38 and Epsilon = 4.10.


## Submission by :
**Name** : Radhika Aggarwal
<br>
**Roll No** : 102003313
