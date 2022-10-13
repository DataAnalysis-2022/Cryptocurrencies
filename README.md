# Cryptocurrencies



## Purpose of the project:

We will use unsupervised machine learning to group cryptocurrencies of current trading market to show the leadership of 

Accountability Accounting company a possible cryptocurrency investment portfolio.

The process includes the data cleaning and transformation, reducing dimensions by PCA (principal component analysis), K-means clustering and final data visualization.



### Results:

- #### Deliverable 1: Preprocessing the Data

​		The data is shown below:

![image-20221012202144930](Resources/image-20221012202144930.png)



​		We only choose the data with active trading, non-null value, and workable algorithms.  The data is cleaned and shown below:

![image-20221012202611501](Resources/image-20221012202611501.png)



After scaling and encoding, the data is shown as:

![image-20221012202759577](Resources/image-20221012202759577.png)



- ### Deliverable 2: Reducing Data Dimensions Using PCA

​		Data after the 3-component PCA dimension reduction:

![image-20221012202915894](Resources/image-20221012202915894.png)



- ### Deliverable 3: Clustering Cryptocurrencies Using K-means

​		Elbow curve of K-means inertia:

![image-20221012203223523](Resources/image-20221012203223523.png)

​		Data after K-means clustering:

![image-20221012203320811](Resources/image-20221012203320811.png)



- #### Deliverable 4: Visualizing Cryptocurrencies Results

​	

​		3D Visualization of 3-components of PCA:

![image-20221012203430972](Resources/image-20221012203430972.png)

​		Classification results table:

![image-20221012203604110](Resources/image-20221012203604110.png)



​		Total number of tradable cryptocurrencies:

![image-20221012203746538](Resources/image-20221012203746538.png)



​		Scaled TotalCoinSupply and TotalCoinsMined with CoinName and Class:

​		![image-20221012203845020](Resources/image-20221012203845020.png)



​		Scatter plot of above data:

![image-20221012203956798](Resources/image-20221012203956798.png)

