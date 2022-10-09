# Cryptocurrencies


### Using Unsupervised Machine Learning to Explore Cryptocurrency Investment Opportunities

![Bannerhead Image](https://github.com/rloufoster/Cryptocurrencies/blob/main/Resources/Images/BannerImage.jpeg?raw=true)



## Overview:

The purpose of this analysis was to use data from CryptoCompare to provide a report and visualizations of currently traded cryptocurrencies that can be grouped together to create a new classification system. The report will be used to guide the Accountability Accounting firm in the decision of whether or not to offer a new investment portfolio to its customers that would include cryptocurrency investment opportunities. 

The data provided to us is not ideal for machine learning models, so it is necessary to preprocess it to fit the algorithms requirements. Since there is no known output for what we are looking for, we decided to use unsupervised learning. We decided to use a clustering algorithm to group the cryptocurrencies. We will then use data visualizations to share our findings with the firm's board of directors.

 * The following concepts and skills were utilized:

   * **Data Processing** (Selection, Transformation, Scaling) - the process of preparing data for input into the Machine Learning                  Algorithms.   
   * **Elbow Curve** - method to determine the best number of clusters to feed into the algorithm
   * **Principal Component Analysis (PCA)** - statistical technique to speed up machine learning algorithms when the number of features is          high
   * **Clustering Algorithms (KMeans)** - the process of grouping similar objects/data points into clusters.
   * **Visualization (hvPlot, Plotly)** - graphic libraries that allows us to create 2D and 3D graphs
  
 * Deliverables Requested were as follows:
 
   * Deliverable 1: Preprocessing the Data for PCA
   * Deliverable 2: Reducing Data Dimensions Using PCA
   * Deliverable 3: Clustering Cryptocurrencies Using K-means
   * Deliverable 4: Visualizing Cryptocurrencies Results 
   
### Resources

   * crypto_data.csv from CryptoCompare
   * Python 3.7.6
   * crypto_clustering_starter_code
   * Jupyter Notebook 6.4.12
   * Libraries: Scikit-learn, Plotly, hvPlot, Pandas
   
   
## Results:

The original dataset contained 1,252 entries, however only 1,144 cryptocurrencies were currently trading. The data was further munged to remove null values and only leave cryptocurrencies that had a total number of mined coins greater than 0. The final results identified 532 tradable cryptocurrencies.


![CryptoTable](https://github.com/rloufoster/Cryptocurrencies/blob/main/Resources/Images/CryptoTable.png?raw=true)

The Elbow Curve method showed the slope at 4.  This is the number of clusters that was used for the KMeans algorithm.

![CryptoElbow](https://github.com/rloufoster/Cryptocurrencies/blob/main/Resources/Images/ElbowCurve.png?raw=true)

The clusters are visualized in the 3D scatter plot.

![3DGraph](https://github.com/rloufoster/Cryptocurrencies/blob/main/Resources/Images/3DGraph.png?raw=true)




 
