## Hospital Clustering and recommendation based user input

  The model built defines the cluster a user is located and also sends to the user the nearest Hospital to his exact location.

#### Exploratory Data Analysis was conducted to clearly understand the data itself.
  * Checked for Missing Data
  * Analyze columns with high missing data to handle before dropping
#### Data Cleaning and Non Algorithmic Clustering
  * Dropped columns deemed not useful from the above process
  * Filled Missing values using other columns
  * Frequency Encoding for Highly categorical data
  * Wrote Python Function to do some clustering by just passing in some necessary data
#### KMeans Clustering Algorithm Implementation using class and Function
  * Use the Location columns for clustering for ease of understanding
  * Plot the points and see if it matches the map of country
  * Class Implementation of Algorithm
  * Using Elbow Method find the best number of clusters
  * Predict cluster of a Location
  * Try different number of clusters and Visualize the clusters with annotation
  * Silhouette Score to also find suitable number of clusters
#### KDTree (Scipy and KNN Implementation)
Got to find out about KDTree and I absolutely love the function. this function really handles the main goal of this project. find the nearest points from a user input. Cool part about it is the ability to input amount of  points interested in.
  * Fit on dataset
  * Test with one close point
  * Export estimator
  * Test with ten close points
  * Create DataFrame for the results
  From the main dataset return the following
  *  'facility_name'
  *  'facility_type'
  *  'community'
  *  'X_gps_longitude'
  *  'X_gps_latitude'
#### Functional Implementationos KMeans clustering Algorithm
  * Function
  * Elbow Method
  * Visualization

I had much fun doing this project
