# Cryptocurrencies
## Overview
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:

* preprocessing the database,
* reducing the data dimension using Principal Component Analysis,
* clustering cryptocurrencies using K-Means,
* visualizing classification results with 2D and 3D scatter plots.

## Resources
**Data Source:** crypto_data.csv,
**Software:** Python, Jupyter Notebook

## Results
Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.


### Clustering Cryptocurrencies using K-Means - Elbow Curve
We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

![elbow_curve](https://user-images.githubusercontent.com/96354508/166585613-433fa598-47c4-4733-b063-59ae77d1d8ff.png)

The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

### Visualizing Cryptocurrencies Results

![viz_3d_scatter](https://user-images.githubusercontent.com/96354508/166585703-02408fe7-02a8-4eb5-8e5d-23038f2409ab.png)
