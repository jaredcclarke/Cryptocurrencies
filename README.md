# Cryptocurrencies
## Overview
### Purpose
The purpose of this exercise was to use unsupervised machine learning with cryptocurrencies that are on the trading market in order to group them together in order for Accountability Accounting to offer clients an investment cryptocurrency portfolio.
## Resources/Tools
* Jupyter Notebook 6.0.3
* Python 3.7.9
* Anaconda 4.9.2
* `crypto_data.csv` from CryptoCompare
* scikit-learn library
* hvplot
* Plotly express

## Results
* Prepocessed by filtering cryptocurrency that was actively traded, null values and removed columns that would not help the analysis. Scaled the data.
* Becuase there are so many variables, PCA was used to reduced the dimensional data to 3 principal components.
* Created an elbow curve to find the best number of n_clusters or K. 
* Used k for the KMeans model to get predictions. Elbow curve showed that 4 clusters would be best.
* Visualized with 3D plots


