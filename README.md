Support Vector Machines
=====
This is the week 6 assignment of [Coursera Machine Learning](https://www.coursera.org/course/ml) class.

Summary
-------
First part of this program experiments with SVM, a large margin classifier algorithm, using three datasets. All of the three data sets consists of two classes. The goal is to find the boundary of classification. Starter code and datasets are shown below. 

> ex6.m - Octave script for the first half of the exercise
> ex6data1.mat - Example Dataset 1
> ex6data2.mat - Example Dataset 2
> ex6data3.mat - Example Dataset 3
> svmTrain.m - SVM training function
> svmPredict.m - SVM prediction function
> plotData.m - Plot 2D data
> visualizeBoundaryLinear.m - Plot linear boundary
> visualizeBoundary.m - Plot non-linear boundary
> linearKernel.m - Linear kernel for SVM

###### gaussianKernel.m 
This method returns the similarity between two input entry vectors using Gaussian kernel with bandwidth sigma

###### dataset3Params.m 
This method returns optimal C and sigma parameters to use for Dataset 3. The optimal learning parameter pair is found by iterating through all possible combinations of candidate values of C and sigma and minimizing the prediction error, which is given by svmPrediction function.

