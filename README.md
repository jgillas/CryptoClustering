# CryptoClustering

The first chart in this challenge is of all the data. This includes all the data for each of the coin ids in the dataset. The chart is below: 

  <img width="849" alt="Screenshot 2023-07-20 at 4 54 10 PM" src="https://github.com/jgillas/CryptoClustering/assets/125215083/c0fcc021-e476-4233-ad0a-963d16d517bc">

I then scaled the data and made the coin ids the index of the dataset. 
Then I created an elbow graph for the scaled data. The graph is below: 

  <img width="834" alt="Screenshot 2023-07-20 at 4 59 00 PM" src="https://github.com/jgillas/CryptoClustering/assets/125215083/17c2b4f1-885b-421b-a281-beb256c053cb">

The best value for K is 4. So there will be 4 clusters.
I then created a Predicted Clusters for the data and I graphed the clusters. The graph is below: 

  <img width="837" alt="Screenshot 2023-07-20 at 5 04 23 PM" src="https://github.com/jgillas/CryptoClustering/assets/125215083/30057a16-b8d2-4a24-ac5a-28768a331969">

I then created a PCA model with 3 clusters. I used the fit_transform to reduce to three principal components. 
I then created an elbow graph for the PCA model. The graph is below: 

  <img width="826" alt="Screenshot 2023-07-20 at 5 08 21 PM" src="https://github.com/jgillas/CryptoClustering/assets/125215083/f80e4d75-460f-4afa-8cb9-ccfed6dfad3e">

The best value for K is still 4, there is not difference between this k value and the k value found while using the original data. 
This means that there will be 4 clusters for this cluster graph as well. I made a column for predicted clusters for this data too. 
The cluster graph for the PCA model is below: 

  <img width="831" alt="Screenshot 2023-07-20 at 5 11 45 PM" src="https://github.com/jgillas/CryptoClustering/assets/125215083/b8e22ed8-b332-4adb-8c15-c477ccc70429">

Then I created elbow graphs for the two sets of data right next to each other. This allows for us to see them side by side. The graphs are below: 

  <img width="802" alt="Screenshot 2023-07-20 at 5 14 52 PM" src="https://github.com/jgillas/CryptoClustering/assets/125215083/8d8be8fd-44ab-40d8-8a80-fab67b620396">
<img width="706" alt="Screenshot 2023-07-20 at 5 15 56 PM" src="https://github.com/jgillas/CryptoClustering/assets/125215083/57c68b6b-4cb0-49f1-b9e1-018313ad0e21">

I then created a cluster graph combining the two sets of data together. The graph is below: 

  <img width="716" alt="Screenshot 2023-07-20 at 5 17 24 PM" src="https://github.com/jgillas/CryptoClustering/assets/125215083/bb2c971f-4c67-410b-86e2-8f44cafeb140">

This is the conclusion of the challenge. 
