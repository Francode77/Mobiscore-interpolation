# Interpolation using KNN and IDW
This is the code that accompanies the article posted on medium. 

[Link to the article](https://medium.com/@francode77/interpolation-using-knn-and-idw-fe546d5fb9ae)

# Context

I will explain a method to create a density map from a limited number of coordinates, by estimating missing values using interpolation.

In this approach we first make a grid and then assign interpolated weights to each coordinate.

# Method

For the interpolation, three methods are explored:

1. Creating a KNN algorithm using BallTree
2. Using sklearn KNeighborsRegressor
3. Nearest neighbours with griddata from scipy

Then we briefly summarize more advanced interpolation methods such as linear and cubic interpolation, and krigin.

# Results

This map is obtained using KNN and IDW.

![image](https://github.com/Francode77/Mobiscore-interpolation/blob/main/assets/output.png)

# Contributor

Written by [Frank Trioen](https://www.linkedin.com/in/frank-trioen-21b71135/) on April 3th, 2023.

