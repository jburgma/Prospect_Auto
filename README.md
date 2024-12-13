# Prospect Auto
Problem Description
A chain of car repair shops called “Prospect Auto” asked you for a model that would differentiate all 3 vehicles based on the silhouette. So, eventually, you need to create a classification model that would predict a vehicle class. The question that may arise: what exactly is needed to approach this project? 

![image](https://github.com/user-attachments/assets/71b41c62-5439-4ff1-b0cb-4ae18961f94c)

## Steps in the Project 





You already know how to generally approach data-driven project. Our project isn’t an exception. So, to come up to the final model, these steps will be crucial in your flow:
- Import all of the libraries you need, upload the dataset and read it in.
- Conduct a good Exploratory Data Analysis, understanding the data both visually and numerically.
- Prepare your data for future modelling by normalizing and standardizing its columns. Also, don’t forget to divide the dataset into subsets (for training and testing purposes) at this stage!
- Check if dimensionality reduction makes a difference here. If it possible to reduce the number of dimensions from original 18 to a lower number while preserving the variance in the data, don’t hesitate to do it. PCA is great algo for this purpose!
- Try solving classification problem “Prospect Auto” asked you to address from two different perspectives: first, using a supervised classification approach or via unsupervised-based clustering way. Compare the approaches by calculating relevant metrics.

Data Description
The data that you’ll work with in this project contains features extracted from the silhouette of vehicles in different angles. In other words, all of the features that you are going to work with are geometric features extracted from the silhouette. They all are numeric in nature.

Features from the silhouette in the dataset are for the three vehicles. Here the are:
a bus (which is a double decker bus)
a van (which is a Cheverolet van)
a car (either Saab 9000 or Opel Manta)
This particular combination of vehicles was chosen with the expectation that the bus, van and either one of the cars would be readily distinguishable, but it would be more difficult to distinguish between the cars.
The dataset is available for downloading here. Let’s briefly discuss what kind of columns this dataset has:
the class column contains vehicle models. As we discussed previously, there may be 3 values there: bus , van or car.
the rest of the columns are numerical columns that describe the silhouette. Don’t worry if you don’t fully understand the rationale behind these columns. Treat them as some numbers that can tell you something about a silhouette of a particular vehicle. Here are these columns:
^compactness
circularity
distance_circularity
radius_ratio
pr.axis_aspect_ratio
max.length_aspect_ratio
scatter_ratio
elongatedness
pr.axis_rectangularity
max.length_rectangularity
scaled_variance
scaled_variance.1
scaled_radius_of_gyration
scaled_radius_of_gyration.1
skewness_about
skewness_about.1
skewness_about.2
hollows_ratio
