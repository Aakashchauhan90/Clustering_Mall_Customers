# Clustering_Mall_Customers
Clustering-Project To find the clusters or groups existing in the data set which is unlabelled so that the mall client can target their loyal customers in better way with their liked products.  

## AIM: 
A mall has collected information about their client and given them spending score (1-100) on the basis of their spending, visit frequency, annual income, and age. The client has asked to categorize their customers into groups so that they can target them better. Also measure the accuracy achieved with applying K-Mean, Agglomarative Clustering and see which will perform better?  

## Data Set: 
The data set is called Mall_Customers.csv given by the client having 200 records, a very small data set which is to be used as POC project. The real data set we can't publish or talk about due to privacy concern. The data set has CustomerID, Genre, Age, Annual Income (k$), and Spending Score (1-100).  

## Approach: 
It is a unlabelled data set and Clearly we don’t know how many clusters could be? It becomes a clustering problem. We used K-Mean clustering algorithm to find the number of the clusters. We used Elbow method to find visually how many clusters could be?  

## Result: 
We are able to extract a total of 5 clusters from the data set.The clusters were namely Target, Standard, Careless, Sensible, and Careful. 

## Target: 
Annual income and spending score are higher. 

## Standard: 
The annual income and spending score both are in mid range. 

## Careless: 
Annual income are less but the spends more. 

## Careful: 
Annual income on higher side but they spends less. Sensible: Both annual income and spending score are on lower side means their income are less so they donot spends more.  The process based on the Elbow method and WCSS=Within cluster sum of square parameter to decide the number of clusters we can have.
