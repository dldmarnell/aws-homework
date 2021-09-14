# Clustering Crypto

The crypto_clustering notebook generates a report of what cryptocurrencies are available on the trading market and how they can be grouped using classification.  First the code uses an API to pull data on all cryptocurrencies from cryptocompare.com.  After the data is prepped, the code reduces data dimensions using PCA and then predicts cryptocurrency clusters using the K-Means algorithm.  The results are then visualized in plots and tables for presentation.

---

## Technologies

Language: Python3, Pandas 

Imports: pandas, requests, json, matplotlib.pyplot, hvplot.pandas, plotly, plotly.express, Path from pathlib, StandardScaler and MinMaxScaler from sklearn.preprocessing, PCA from sklearn.decomposition, and KMeans from sklearn.cluster

External Resources: cryptocompare.com

Developed with JupyterLab

---

## Installation

JupyterLab - [Install JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)

---

## Examples

Final cleaned cryptocurrency dataframe with PCA clusters and classes:

![clustered_df](Resources/Images/clustered_df.png)


Cryptocurrency PCA data and clusters plotted on a 3D scatter graph:

![scatter_plot3d](Resources/Images/scatter_plot3d.png)

---

## Contributors

Drew Disbrow Marnell: dldmarnell@gmail.com

---

## License

MIT License
Copyright (c) 2021 Drew Disbrow Marnell