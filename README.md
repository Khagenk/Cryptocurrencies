# Cryptocurrencies
Accountability Accounting, is interested in offering a new cryptocurrency investment portfolio to its clients; however, the company needs assistance in determining which cryptocurrencies they should offer. Senior management has requested a report that include what cryptocurrencies are on the trading market and if they could be grouped to create a classification system for this new investment.
The data from Accountability Accounting needed to be cleaned in order to fit the machine learning models, and since there isn't a known output for what this investment bank is looking for, unsupervised machine learning was employed. In order to group the cryptocurrencies, a clustering algorithm was utilized and the data was visualized so the finding could be shared with the board.


# Resources
- crypto_data.csv
- hvPlot Documentation
- scikit-learn PCA Documentation
- scikit-learn KMeans Documentation
- scikit-learn MinMaxScaler Documentation
- scikit-learn StandardScaler Documentation

# Dependencies
-Jupyter Notebook
- Python v3.x
  - Pandas
  - hvPlot
  - Path
  - Plotly
  - SciKit-Learn

# Results
Once crypto_data.csv was cleaned and preprocessed, there were 532 tradable cryptcurrencies.


An elbow curve was produced in order to find the best value for K. This would be used to determine the number of clusters that should be used in the K-Means clustering algorithm. According to the elbow curve, k=4

![Screen Shot 2022-04-03 at 10 02 18 PM](https://user-images.githubusercontent.com/94031446/161462098-56f8cafe-7bb7-45ff-b369-09bf326fee33.png)

The unsupervised machine learning algorithm Principal Componenet Analysis (PCA) was used to reduce the dimensions of the cryptocurrency components to three principal components. The following 3D scatter chart shows the cryptocurrency dataset in four clusters.

![Screen Shot 2022-04-03 at 10 04 46 PM](https://user-images.githubusercontent.com/94031446/161462278-4046fcc1-7763-4642-ac8c-6a001ab94bc7.png)


The 2D scatter chart shows the each cryptocurrency from the dataset as it related to total coins mined and total coin supply.

![Screen Shot 2022-04-03 at 10 05 07 PM](https://user-images.githubusercontent.com/94031446/161462302-e3028cfc-feef-4a34-bfd3-be1d0805b476.png)

