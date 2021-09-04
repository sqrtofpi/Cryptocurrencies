# Cryptocurrencies
Module 18: Unsupervised Machine Learning and Cryptocurrencies

## Project Overview

The goal of this project is to perform an analysis that includes different types of cryptocurrencies being traded and create a classification system grouping them using clustering algorithms. We started with 1,252 rows of data in our original DataFrame and reduced the list of tradeable cryptocurrencies to 532 rows of data after cleaning. We determined 4 clusters would be appropriate from our K-means clustering algorithm (Elbow Curve method).

![Elbow Curve](https://github.com/sqrtofpi/Cryptocurrencies/blob/034b9fa1c4b855dfe5f1295fdf329b199faa9317/Images/Screen%20Shot%202021-09-04%20at%202.09.34%20PM.png)

The clusters were then plotted in a 3D scatterplot for visual representation.

![3D Scatterplot](https://github.com/sqrtofpi/Cryptocurrencies/blob/034b9fa1c4b855dfe5f1295fdf329b199faa9317/Images/Screen%20Shot%202021-09-04%20at%202.08.01%20PM.png)

Finally we then created a plot of TotalCoinsSupply vs. TotalCoinsMined to complete the analysis.

![Crypto Plot](https://github.com/sqrtofpi/Cryptocurrencies/blob/034b9fa1c4b855dfe5f1295fdf329b199faa9317/Images/Screen%20Shot%202021-09-04%20at%202.09.03%20PM.png)
