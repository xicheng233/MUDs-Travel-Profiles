This folder render into linear regression model to classify MUD, clustering model to cluster the travel pattern, optimization model to determine charging station deployment.

1. To match the NHTS household-level travel data with the MUDs share information, we fit a statistical model that predicts the share of MUDs as a function of variables included in both datasets.

2. This repository classifies the travel patterns of MUD residents, leveraging trip data of the latest National Household Travel Survey and American Housing Survey. A hierarchical agglomerative clustering method is used. Three clusters are created taking into consideration factors, such as dwell time, daily vehicle miles traveled, income, and US census division. 

3. We propose a charging decision model to determine charging station deployment in MUDs and charging time, under an assumption that MUD resident drive electric vehicles. Numerical experiments are conducted to gain insights into MUD charging needs as well as energy uses in the national level in U.S. 
