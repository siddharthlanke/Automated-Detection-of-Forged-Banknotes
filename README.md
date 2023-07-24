# Automated-Detection-of-Forged-Banknotes
The "Automated Detection of Forged Banknotes" project was completed as part of the online course "Foundations of Data Science: K-Means Clustering in Python" on Coursera. 

## Objective
The primary objective of the project was to detect counterfeit banknotes using the K-Means clustering algorithm. 
The project leveraged various Python libraries, including Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn, to handle data manipulation, visualization, and machine learning tasks.

## Dataset
The project utilized a dataset comprising samples of banknotes, each represented by a set of numerical features extracted from images. The dataset contained attributes such as variance, skewness, kurtosis, and entropy, which captured different characteristics of the banknotes. 

The dataset used in this project can be accessed through the following OpenML link:
https://www.openml.org/d/1462

## Methods and Approach
The project adopted a K-Means clustering approach, a popular unsupervised learning algorithm, to categorize the banknote samples into distinct clusters based on their feature similarities. The data was preprocessed to ensure standardized scaling, enabling fair comparisons of features during clustering. Multiple iterations of the K-Means algorithm were executed to account for different random initializations, enhancing the stability of the clustering results. 
