# Parameter_Optimization_Of_SVM

Support Vector Machines (SVMs) are powerful and versatile machine learning algorithms used for both classification and regression tasks. The main idea behind SVMs is to find the hyperplane that maximizes the margin between the different classes in the dataset.

When it comes to parameter optimization, SVMs have several parameters that can be fine-tuned to achieve better performance. Some of the important parameters include:

Kernel: SVMs use different types of kernels, such as linear, polynomial, radial basis function (RBF), and sigmoid, to transform the input data into a higher-dimensional space. Choosing the right kernel function can greatly impact the performance of the SVM.

Regularization parameter (C): This parameter controls the trade-off between maximizing the margin and minimizing the classification error. A large value of C will lead to a narrow margin and potentially overfitting, while a small value of C will lead to a wider margin and potentially underfitting.

Gamma parameter: This parameter is used in the RBF kernel and controls the shape of the decision boundary. A small value of gamma will lead to a more flexible decision boundary, while a large value of gamma will lead to a more rigid decision boundary.

Optimizing these parameters can be challenging and time-consuming, but it is crucial for achieving the best performance of the SVM. One common approach to optimize the parameters is to use a grid search, where a range of values for each parameter is specified, and the SVM is trained and evaluated for each combination of parameter values. Cross-validation is often used to prevent overfitting and ensure that the selected parameter values generalize well to new data.

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph

## Submission by :
**Name** : Radhika Aggarwal
<br>
**Roll No** : 102003313
