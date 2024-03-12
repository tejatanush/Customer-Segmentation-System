# Customer-Segmentation-System
This model is capable of categorizing customers into distinct groups based on common characteristics, enabling personalized marketing strategies and improving customer satisfaction and retention.  
### Features  
Import required libraries  
Import dataset  
Data Preprocessing  
Find and fill missing values  
Encoding data  
Feature Scaling  
Dimensionality Reduction  
Build a model  
K-Mean Clustering  
Finding Optimal number of clusters    
Build a K-Mean clustering model  
Visualizing Clusters  
Observing percentage of customers in each cluster  
Evaluate K-Means cluster model  
Silhouette score   
Davies bouldin score   
Hierarchical Clustering  
Finding Optimal number of clusters  
Build a Hierarchical clustering model  
Visualizing Clusters  
Observing percentage of customers in each cluster  
Evaluate Hierarchical cluster model  
Silhouette score  
Davies bouldin score  
Finalize the model  
Cluster Analysis  
Profiling   
### Applications  
**Personalized Marketing:** Tailoring marketing campaigns and promotions to specific customer segments based on their preferences and behavior.  
**Product Development:** Informing product design and feature enhancements by understanding the needs and desires of different customer groups.  
**Customer Retention Strategies:** Crafting targeted retention programs and loyalty rewards to increase customer loyalty within specific segments.  
**Pricing Optimization:** Adjusting pricing strategies for different segments to maximize revenue while meeting the price sensitivity and expectations of each group.  
### Compiler Type:  
I used a compiler CPU provided in google colab while running this project.  
## Results  
### This project contain two models. Among them K-Means clustering model have a davies bouldin score of 1.14 and silhouette score of 0.283.....Hierarchical clustering model have a davies bouldin score of 1.613 and silhouette score of 0.229. So K-Means model performed well with 4 clusters.  
## These are the 4 clusters through K-Means  
## CLUSTER-0: IMPULSIVE SPENDERS  
This cluster is having the customers with moderate age,moderate income and high spending score. It mean this cluster contains the customers who are in youth age and having moderate annual income but spending lot's of money.  
## CLUSTER-1: WEALTHY ELDERS  
This cluster is having high age, high annual income and high spending score. It mean this cluster contain customers who are very old aged and having high annual income and also  spending more money daily.  
## CLUSTER-2: AFFLUENT MODERATES  
This cluster is having moderate age, high annual income and moderate spending score.It mean this cluster contain customers who are middle aged, having high annual income and spending moderate money as per their needs in a planned way.  
## CLUSTER-3:  STABLE RETIREES  
This cluster is having high age, moderate annual income and moderate spending score. It mean this cluster contain customers who are old aged, having moderate income and moderate spending as per their needs.  
## References  
Customer_Segmentation_System.csv->  (https://www.kaggle.com/datasets/govindkrishnadas/segment)  
## Requirements  
Pandas  
Numpy  
Matplotlib  
sci-kit learn  
scipy  
## Programmes  
Python  
## Owner  
[Teja Tanush](https://github.com/tejatanush) 
