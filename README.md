# unsupervised-learning-challenge

This assignment asked us to use unsupervised machine learning in order to create a classification system for cryptocurrencies. The raw data comes from the crypto_data.csv obtained from CryptoCompare.

In order to run the model, first you must prepare the data. We are asked to only use the cryptocurrencies that are currently in use, and drop the rest from the dataset, get rid of any rows with null values, limit the dataframe to rows where the total data mined is greater than 0, drop all columns with non-numerical data that isn't catagorical(names of the different cryptocurrencies), and use pandas to create dummy variables for the non-numerical, catagorical data.

Once the data was prepared, you scale it. You then perform dimensionality reduction with PCA, preserving 90% of explained varience. Taking that reduced data, run it through a t-SNE and create a scatter plot. 

Analyze the clusters shown using k-Means and an elbow plot, where k has a value of 1 to 10.

All observations are included in the jupyter notebook file.

There were no really big stumbling blocks with this assignment. The preparation was simple and straight-forward, running the models were pretty much cut and paste from the class examples.
