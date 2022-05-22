# Mod10_Challenge

# Creating a Jupyter notebook that clusters cryptocurrencies. 

This is a Jupyter lab program that will create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods using CSV file. Then it will plot the results to visually show the performance across time.

## Technologies

The project is in Jupyter Note with the following libraries:

* [Pandas] 

* [Path] 

* [Hvplot] 

* [sklearn.Cluster kMeans] 

* [sklearn.Decomposition PCA] 

* [sklearn.Preprocessing StandardScaler] 

## Installation Guide

Install required libraries above for program to function correctly.

## Usage

The program analyses the csv cryptocurrencies and creates new DataFrame before running K-Means algorithm using StandardScaler utilizing fit_transform function. Finds the best value for k using the elbow method algorithm range from 1-11, then creating a plot line chart with the different inertia values compound to find the optimal k value. Also performs a principal component analysis (PCA) and reduce the features to three principal components to cluster. It will visually analyze the cluster analysis results by contrasting the outcome with and without using the optimization techniques.

## Contributors

Brought by Jaime Villafuerte 
Jaime_Villafuerte20@yahoo.com

## License

Rice Bootcamp
