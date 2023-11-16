# CryptoClustering

Contributor: Alex Calametti


Overview: 

The goal of this project was to analyze if cryptocurrencies are affected by 7-day or 24-hour price changes using Python and unsupervised learning. 

Programs and files: 

- Python, Sklearn, pandas
- Crypto_Clustering_starter_code.ipynb
- crypto_market_data_csv

Steps:

- Prepared the data by using StandardScaler() module to normalize data and created DataFrame
  
![Screen Shot 2023-11-16 at 4 25 58 PM](https://github.com/acalametti/CryptoClustering/assets/136642574/33a161c2-9d50-4e0f-8dfe-b6e51deb14f8)

- Found the best K value using the scaled DataFrame by creating an elbow curve
  
![Screen Shot 2023-11-16 at 4 27 44 PM](https://github.com/acalametti/CryptoClustering/assets/136642574/894a1566-4115-4445-9ba2-95ec591ed062)

- Clustered the cryptocurrency with the K-means found from the elbow curve and plotted the data›
  
  ![Screen Shot 2023-11-16 at 4 29 16 PM](https://github.com/acalametti/CryptoClustering/assets/136642574/b1564dec-899f-4a50-8272-3f92dec0f7ed)

- Used principle component analysis to optimize the clusters and reduced the features to three different principles and created a new DataFrame
- Found the explained variance of the three principle components
- Found the best k value based on the PCA data by creating a new elbow curve

  ![Screen Shot 2023-11-16 at 4 32 35 PM](https://github.com/acalametti/CryptoClustering/assets/136642574/1824906a-27af-477a-9bb1-d96008860e1b)

-   Lastly, crytpocurrencies were clusteres using the K-means from the PCA data and a new plot was created
  
![Screen Shot 2023-11-16 at 4 33 54 PM](https://github.com/acalametti/CryptoClustering/assets/136642574/eca56225-29fa-4fde-9409-89a9dd985c20)
