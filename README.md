# LHL-DS-Project6-UnsupervisedLearningML

## I. Dataset
    https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set/data


## II. Notebook Content
### 1. Data Cleaning and EDA
    1.1 Data Loading
    1.2 Data Auditing
    1.3 Grouping Datasets by Channel and Region
    1.4 Preliminary EDA
    1.5 Data Cleaning
    1.6 Data Transformation and Scaling
### 2. K-Means
    2.1 Finding the Optimal K-Value
    2.2 K-Means Clustering
    2.3 Assignning the Labels to the dataset
    2.4 K-Means Model Metrics
### 3. Hierarchiral
    3.1 Finding the optimal number of dendograms
    3.2 Agglometarive Clustering
    3.3 Assigning the labels to the dataset
    3.4 Agglomerative Clustering Metrics
### 4. PCA + Kmeans
    4.1 Reducing the dimension of the dataset to 2 features
    4.2 Performing Agglomerative Clustering
    4.3 Performing K-Means Clustering
    4.4 Comparing the metrics of Agglomerative and K-Means model
    4.5 Assigning the labels from K-Means clustering to the Dataset
    4.6 EDA of the new clustered dataset
### 5. Conclusion

## III. Approach
    1. Use histograms to determine the distribution shape of the data.
    2. Use z-score to determine the outliers
    3. Try different data transformation and composition (with or without the outliers) to determine which model will result into a higher metrics.
    4. For k-means, use elbow method and gap statistics to determine which model will result in a higher metrics.
    5. For agglomerative clustering use dendograms to find the optimal number of clusters for agglomerative clustering with the higher metrics.
    6. For PCA reduce the dimension of the dataset to two features and test both agglomerative and k-means to determine which model will result in a higher metrics using the minmax scaled dataset because minmax dataset is the most optimal dataset to use for both k-means and agglomerative clustering.
    7. For the result of PCA and K-means, use the range of values of the original dataset grouped by region and channel but divided into different clusters based on the cluster determined using PCA + K-means model.
