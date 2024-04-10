

<div align="center">
  
</div>

![image](https://github.com/Yashg5311/NightGuardian/assets/91370994/7432dea7-4366-4e0d-b220-903981b87292)



## Introduction
The issue of safety is of crucial importance in Delhi with the ever so escalating crime rates. Putting the same crime related data to good use, we have come up with an app that suggests alternative routes between any two places in Delhi, giving information about not only the time duaration and distance of travel, but also a certain 'Danger Index' of each route. We evaluate this 'Danger Index' by applying Unsupersvised Machine Learning on crime data/records of the past. We hope to extend this app's utility by including more detailed and transparent data which is not currently available.

## Technical Complexity
We have applied Unsupervised Machine Learning Algorithm to find danger index of multiple routes between two places.
We have used a Clustering algorithm : K-Means , to rate criminal activities in 166 places on the map of Delhi on a scale of 0 to 4. K-means clustering is unsupervised machine learning, which is used when you have unlabeled data (i.e., data without defined categories or groups). The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups based on the features that are provided. Data points are clustered based on feature similarity. The results of the K-means clustering algorithm are: 1.The centroids of the K clusters, which can be used to label new data 2.Labels for the training data (each data point is assigned to a single cluster)

## APIs - Google Maps Javascript API
We used Google map and google places apis to display all possible routes between any two location along with danger index of that route. An autocomplete feature of the search bars lets the user select starting and destination locations along with the mode of travel i.e. walking , driving or transit.This leads to displaying routes with markers indicating danger level of a place that falls on that route.The data below the map shows relevant information like time durations , distance and danger index of all possible routes between two places entered. This would enable user to make smart decisions while choosing any route.





