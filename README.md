# BA820-Credit-Card-Project
## Project Final Deliverable - Summary

### The problem to solve:
In today's world, the right marketing is becoming increasingly important. It is not only about working out the right marketing campaign, but also presenting it to the right target group. The target groups of a company must be determined through analysis and categorization. The difficulty is not to work out too many small customer segments, but on the other hand to still have larger homogeneous groups. One way to cluster customers into different groups is unsupervised machine learning. Our goal is to identify different customer groups for the selected credit card data set, which can then be used by the company for targeted marketing campaigns in the future.

### The data set:
We chose the Credit Card dataset from Kaggle, which contains transactions about 9000 active credit card holders over 6 months. The dataset contains 8950 rows and 18 columns, and the columns contain information about the associated ID, balance and various transaction information. There are 17 variables that are numerical, and one object variable in the data set.
The reason we chose this dataset is because a big challenge for marketers is to understand whom to sell to. When you know the buyer’s personality, you can adjust your positioning and products to increase their satisfaction and earnings. When you already have a customer pool and have enough data, it is very useful to segment them. Therefore, this dataset can help us extract customer segments based on customer behavior patterns provided in the data to focus the company’s marketing strategy on specific segments. For details about EDA and Data Cleaning see deliverable 2.

### Proposed analysis methodology:
We plan to use the learning obtained from the class such as PCA, Standard Scare, Kmeans clustering, Elbow method, Hierarchical clustering and Silhouette analysis to conduct the analysis.

Data cleaning includes removing missing values and using dummy variables where possible. Also, we will look into the distributions and correlations of each variable. Data standardization and PCA might apply for the dataset depending on the distance of each variable.
EDA to determine structures and get to know the data itself.
Analyze and interpret data to understand trends in customer segments. Here we will determine the strength of our model(s) by looking at the following metrics:
Hierarchical clustering. Hclust is an algorithm for grouping similar objects into clusters. It treats each observation as a separate cluster. Then, it repeats the following steps: (1) identify the two closest clusters, (2) merge the two most similar clusters. Repeat this process until all clusters are merged together.
Kmeans clustering. It can help us divide n observations into k clusters, where each observation belongs to the cluster with the nearest mean.
Elbow method. In cluster analysis, the elbow method is a heuristic method to determine the number of clusters in the data set. Therefore, we will use Elbow methods to decide the number of k in order to do further clustering analysis.
Silhouette analysis. Silhouette analysis can be used to study the separation distance between the obtained clusters. It can be used to evaluate Kmeans clustering and Hclust. By analyzing the silhouette score and plot, we will be able to choose the best clustering model for our dataset.
