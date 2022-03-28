# Cryptocurrencies

## Project Summary

This project was conducted in Jupyter Notebook with Python mlenv. This project included 4 parts.  The first part was preparing the data.  Null values were found and dropped.  All values were converted to floats and certain columns were dropped. To create two dataframes.

In the second part of the project, the data dimensions were reduced by PCA.  A new dataframe pcs_df was created with 3 compononents the data was reduced into by PCA.  The third part included clustering the cryptocurrencies using K-Means.  This included plotting an elbow curve to determine the best value of k.


<img width="767" alt="image" src="https://user-images.githubusercontent.com/85581208/156397958-8e99eccd-3e2c-4ce4-9b5b-ad7fb8f94afa.png">


Looking at the plot above it appears k should be 4.  The K-Means was run with 4 clusters as shown below.


<img width="699" alt="image" src="https://user-images.githubusercontent.com/85581208/156398152-5a8a2d18-493c-45c7-8e55-2a5e1a5e7a8f.png">


Then two dataframes were concatenated to set up for the fourth part of the project.


<img width="825" alt="image" src="https://user-images.githubusercontent.com/85581208/156398436-b9dba4bc-f8cb-461b-8c32-037248d2b7a4.png">


Part 4 included plotting a 3-D scatterplot, hvplot table, scaling the data, and a 2-D scatter plot.  Images below.

<img width="750" alt="image" src="https://user-images.githubusercontent.com/85581208/156398825-00e41c8b-9979-4205-930a-23fbc96428b1.png">


<img width="847" alt="image" src="https://user-images.githubusercontent.com/85581208/156398900-7fa4c89e-5a11-4580-9e3a-b387f36bd74c.png">


<img width="808" alt="image" src="https://user-images.githubusercontent.com/85581208/156398993-15f1753b-d8e2-4ab4-938f-78fc35649712.png">


<img width="840" alt="image" src="https://user-images.githubusercontent.com/85581208/156399039-cc486201-4f88-442f-ac0a-7ffb672df142.png">

Overall the scatterplot was concentrated in the corner with TotalCoinsMined(X) less than 0.2 and TotalCoinsSupply(Y) less than 0.4.  There are two notable outliers.  Otherwise data seems to be consistent.


