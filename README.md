# Toronto Clustering

## Introduction/Business Problem
Cluster Toronto neighborhoods by venue similarity.

## Data
List of venues retrieved through the Foursquare API, geolocation data from the geopy package.

## Methodology 
K-means clustering and hierarchical clustering applied to geolocation data and neighborhoods data retrieved by the Foursquare API.

## Results
The two cluster models when set with the same number of clusters give similar results and in particular they outline : 
- a clearly identified city center where Coffee Shops are abundantly present
- a second predominant cluster of neighborhoods which have a stronger presence of ethnic restaurants.

