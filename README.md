# Project_customer_segmentation
### Introduction:
The online retail industry is highly competitive, and companies need to stay ahead of their competitors by understanding their customers' behavior and preferences. Customer segmentation is a valuable strategy that helps companies identify the most valuable customers and target them with personalized marketing strategies. In this project, we aimed to identify major customer segments for a UK-based non-store online retail business that sells unique all-occasion gifts. The company's customer base includes both retail customers and wholesalers, making it essential to understand their preferences and behavior.

### Data Exploration and Cleaning:
Before segmenting the customers, we first explored and cleaned the data to ensure that it was ready for analysis. Data cleaning involved identifying and removing missing values, incorrect data types, and outliers. Exploratory data analysis helped us understand the relationships between the features and identify patterns and trends in the data. For instance, we found that customers from different countries had different buying patterns and preferences.

<img src="[https://i.imgur.com/ZWnhY9T.png](https://github.com/rajashriekatpure/Project_customer_segmentation-/blob/main/Combine.jpg)" width=50% height=50%>

### RFM Analysis:
After cleaning and exploring the data, we performed RFM analysis to segment the customers based on their behavior. RFM stands for Recency, Frequency, and Monetary, and it is a widely used technique for customer segmentation. Using RFM analysis, we identified the Platinum and Gold Customers who brought in more profit to the online retail store. These customers had high monetary value, made frequent purchases, and had a recent transaction with the company. We then focused on Silver and Bronze type customers, who were less valuable than the Platinum and Gold Customers. By organizing attractive offers for these customers, we aimed to increase their engagement with the company and boost their loyalty.
![alt text](https://github.com/rajashriekatpure/Project_customer_segmentation-/blob/main/RFM.jpg)
![alt text](https://github.com/rajashriekatpure/Project_customer_segmentation-/blob/main/Distribution.jpg)
### Unsupervised Machine Learning Algorithms:
Next, we implemented various unsupervised machine learning algorithms, such as KMeans Clustering, DBSCAN Algorithm, and Hierarchical Clustering (Agglomerative Clustering), to further segment the customers. These algorithms help identify patterns and clusters in the data without the need for predefined labels or categories. We used Python and its various libraries, such as Scikit-learn, to perform these clustering techniques. Each of these techniques had its pros and cons, and we tested all of them to see which one would be the best fit for our dataset.

### Optimal Number of Clusters:
One of the primary challenges in this project was to determine the optimal number of clusters that would provide meaningful insights. To find the optimal number of clusters, we used several techniques such as the Elbow method, Silhouette Score, Silhouette Plot, and Dendogram. These techniques helped us visualize the clusters with different numbers of clusters, and we chose the optimal number of clusters that would help us gain valuable insights into the customer segments.

### Customer Segments:
Using the KMeans Clustering algorithm, we identified two clusters in the dataset. Cluster 0 contained 2414 customers who had a high recency rate but very low frequency and monetary value. The retail business could focus on increasing engagement with these customers by offering them personalized deals and discounts. Cluster 1 had a low recency rate, but they were frequent buyers who spent a considerable amount of money on the website, making them the most valuable customer group. The company could offer loyalty rewards and personalized recommendations to these customers to retain their loyalty and maximize their lifetime value.
![alt text](https://github.com/rajashriekatpure/Project_customer_segmentation-/blob/main/k.jpg)
### Conclusion:
In conclusion, customer segmentation based on transaction data is essential for online retail businesses. By identifying the optimal number of clusters and analyzing customer data using RFM analysis and unsupervised machine learning algorithms, businesses can identify their most valuable customers and target them with personalized marketing strategies. However, more robust analysis that incorporates demographics or product features can lead to even more accurate customer segmentation. In this project, we identified two customer segments that could help the company make informed marketing decisions and maximize its profitability.
