# Parameter Optimization of Support Vector Machines

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset Description


### Attribute Information:


### Source
 UCI Machine Learning Repository:https://archive.ics.uci.edu/ml/machine-learning-databases/00628/
 
### Result
| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.93 | Poly | 6.93 | 2.77 |
| 2 | 0.56 | Rbf | 9.49 | 9.14 |
| 3 | 0.92 | Poly | 2.45 | 3.58 |
| 4 | 0.93 | Linear | 2.83 | 2.95 |
| 5 | 0.73 | Sigmoid | 8.68 | 3.75 |
| 6 | 0.58 | Rbf | 5.56 | 6.85 |
| 7 | 0.93 | Poly | 8.94 | 1.30 |
| 8 | 0.93 | Poly | 1.90 | 7.19 |
| 9 | 0.93 | Poly | 7.39 | 9.51 |
| 10 | 0.93 | Poly | 8.62 | 9.82 |


# Convergence Graph 
![image](https://user-images.githubusercontent.com/72933441/233191949-c603bc36-3bd8-4ff7-913e-0ec3ba41e7d0.png)


## Written By:
Name: Parth Vohra

Roll No: 102016044

Batch: 3CS10
