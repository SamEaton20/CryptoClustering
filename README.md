# CryptoClustering
Load in the CSV file - crypto_market_data.csv
# Prepare the Data
 - Use StandardScaler to normalize data from CSV
 - Create DataFrame with scaled data
# Fine the Best Value for k with Original Scaled DataFrame
 - Create list of k-values
 - Create a loop with inertia
   - Create KMeans model
   - Fit the model to scaled data
 - Create a dictionary with data to plot Elbow Curve
 - Chart Elbow curve
 - ![Screenshot 2024-11-14 211608](https://github.com/user-attachments/assets/7b25e8d6-2ade-44f3-8a65-9166391c8062)

# Cluster Cryptocurrencies with K-means with Original Scaled DataFrame
 - Initialize the K-means model using the best value
 - Fit the K-means model
 - Predict the clusters
 - Create scatter plot
 - ![Screenshot 2024-11-14 211715](https://github.com/user-attachments/assets/50872639-e2f7-4d17-bff9-3e867c8ab05a)

# Optimize Clusters with Principal Component Analysis
 - Create PCA model instance
 - Use model to reduce original scaled DataFrame down to three principal components
 - Get the explained variance to determine how much info can be attributed to principal components.
 - Create DataFrame with PCA data
# Find the Best Value for k using the Scaled PCA DataFrame
 - Create list of k-values
 - Create a loop with inertia
 - Create KMeans model
 - Fit the model to scaled data
 - Create a dictionary with data to plot Elbow Curve
 - Chart Elbow curve
 - ![Screenshot 2024-11-14 212156](https://github.com/user-attachments/assets/8fd25b45-1ea2-4afa-8a53-48cd5f30db54)
# Cluster Cryptocurrencies with K-means using the Scaled PCA DataFrame
 - Initialize the K-means model using the best value
 - Fit the K-means model
 - Predict the clusters
 - Create scatter plot
 - ![Screenshot 2024-11-14 212304](https://github.com/user-attachments/assets/7455a99c-5836-4ce9-83e3-b13177c0f4d8)
