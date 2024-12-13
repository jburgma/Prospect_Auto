<div align="center">
<img src="https://github.com/user-attachments/assets/71b41c62-5439-4ff1-b0cb-4ae18961f94c" width="200" height="200" alt="Image">
</div>

# Vehicles Classification - Prospect Auto shops
## Problem Description

A chain of car repair shops called “Prospect Auto” requested a model that would allow the differentiation of three vehicles based on their silhouette. Therefore, it was necessary to create a classification model that would allow the prediction of the vehicle class. The question that may arise is: what exactly is needed to tackle this project?



## Project Steps

- Import all of the libraries, upload the dataset and read it in.
- Conduct a good Exploratory Data Analysis, understanding the data both visually and numerically.
- Prepare the data for future modelling by normalizing and standardizing its columns. Also, divide the dataset into subsets (for training and testing purposes) at this stage!
- Check if dimensionality reduction makes a difference here. If it possible to reduce the number of dimensions from original 18 to a lower number while preserving the variance in the data, PCA is great for this purpose.
- The classification problem of “Prospect Auto” can be approached from two different perspectives: first, using a supervised classification approach or by using an unsupervised clustering method. Relevant metrics can be calculated to compare the approaches.

  
## Data Description
The data for this project contains numeric features extracted from the geometric silhouette of vehicles in different angles.

Features from the silhouette in the dataset are for the three vehicles. Here the are:
- a bus (which is a double decker bus)
- a van (which is a Cheverolet van)
- a car (either Saab 9000 or Opel Manta)

This particular combination of vehicles was chosen with the expectation that the bus, van and either one of the cars would be readily distinguishable, but it would be more difficult to distinguish between the cars.

The dataset is available for downloading here. Let’s briefly discuss what kind of columns this dataset has:
the ```class``` column contains vehicle models. As previously, there may be 3 values there: ```bus``` , ```van``` or ```car```.
the rest of the columns are numerical columns that describe the silhouette. Don’t try to understand the rationale behind these columns. Treat them as some numbers that can tell something about a silhouette of a particular vehicle.

Here are these columns:
- ```compactness```
- ```circularity```
- ```distance_circularity```
- ```radius_ratio```
- ```pr.axis_aspect_ratio```
- ```max.length_aspect_ratio```
- ```scatter_ratio```
- ```elongatedness```
- ```pr.axis_rectangularity```
- ```max.length_rectangularity```
- ```scaled_variance```
- ```scaled_variance.1```
- ```scaled_radius_of_gyration```
- ```scaled_radius_of_gyration.1```
- ```skewness_about```
- ```skewness_about.1```
- ```skewness_about.2```
- ```hollows_ratio```




