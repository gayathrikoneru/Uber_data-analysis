# Uber_data-analysis
The real time data regarding the information of rides taken up by the popular ride-hailing company, Uber, from April to September 2014, are available online.
This data is analysed using relevant Machine Learning algorithms to give some useful insights and visualize the hidden patterns in the data.

## Visualization
Visualization of the available data is performed using "visualization.ipynb" to bring out the hidden patterns.

## Frequent Itemsets Mining
Frequent patterns related to the rides and their locations are mined using "Frequent Pattern Growth" algorithm, association rules are generated and interesting rules are mined out.
FIM is performed in the files "dataset_for_mining.ipynb" and "fim_using_pyspark.ipynb".
This process of FIM is implemented using pyspark.

## Clustering
The data of rides is analyzed by clustering the locations of the rides according the Base region they belong to. The ML algorithms used are DBSCAN and KMeans clustering.
These are available in the files "densityClustering.ipynb" and "KMeansClustering_using_pyspark.ipynb".
The latter algorithm is implemented using pyspark.

## Classification
Given the values of Latitude and Longitude of a location, the Base to which it belongs to, is predicted by training an ML model using K-Nearest Neighbours algorithm.
