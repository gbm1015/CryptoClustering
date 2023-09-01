# Crypto Clustering Challenge 

## Background

Using the knowledge of Python and unsupervised machine learning (clustering technique) in predicting whether cryptocurrencies are affected by 24-hour or 7-day price changes.

### Before opening the starterCode folder

1. I created a new repository in GitHub for this project called `CryptoClustering`. 
2. Inside the new repository I cloned the new repository to my computer.
3. Inside my local Git repository, I added the files from the StarterCode folder that was within the Module 19 Challenge zip file.  The folder included the following:
   - a file titled "Crypto_Clustering_starter_code", a Jupyter Notebook file that included starter code and comments.
   - a folder titled "Resources" that included the csv dataset titled "crypto_market_data.csv".
4. I renamed the Jupyter Notebook file "Crypto_Clustering_starter_code" to "Crypto_Clustering" before coding in Python and completing the cryptocurrency clustering analysis.

## Steps for Machine Learning Clustering Analysis

1. Imported the crypto_market_data.csv data and generated summary statistics (numerical and graphical).
   - Read the “crypto_market_data.csv” file into a DataFrame, and set the cryptocurrency name as the index.
   - Generated the summary statistics, and used HvPlot to visualize the data.
2. Prepared the data.
   - Used the `StandardScaler` module from scikit-learn to standardize the CSV file data.
   - Created a DataFrame that contained the scaled data.
   - Set the column `coin_id` from the original DataFrame as the index.
3. Found the Best Value for the number of clusters `k` using the Original Data, after standardizing the data.
4. Clustered the standardized Cryptocurrencies data using the K-means machine learning method, with the optimal number of clusters k=4.
5. Optimized the clustering by using Principal Component Analysis (PCA) for reducing the number of features from the original 7 to 3 features (PCA1, PCA2, and PCA3).
6. Found the Best Value for the number of clusters `k` Using the PCA data.
7. Using the PCA data, clustered the Cryptocurrencies data by the K-means machine learning method, with the optimal number of clusters k=4.
8. Compared and contrasted the clustering analysis visualizations and results between the original standardized data and the PCA data.
      

