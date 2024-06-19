# K-Means Clustering Analysis of Thai Live Sellers' Posting Types

**Overview**

In this project, I utilized K-Means clustering to analyze and categorize Thai live sellers based on their posting types and engagement metrics. This README provides an overview of the project, including key concepts of K-Means clustering and insights derived from the analysis.

**Key Concepts:**

1. **K-Means Clustering**
K-Means clustering is a popular unsupervised machine learning algorithm used to partition data points into K distinct clusters. It operates by iteratively assigning data points to clusters based on the proximity to the cluster's centroid (mean).

2. **Elbow Method**
The Elbow Method is a technique used to determine the optimal number of clusters (K). It plots the sum of squared distances from each point to its assigned cluster center (inertia) against the number of clusters. The "elbow" point where the inertia starts to decrease more slowly indicates the optimal K value.

3. **Label Encoding**
Label Encoding is a preprocessing step where categorical variables are converted into numerical labels. This transformation allows algorithms like K-Means to process categorical data effectively.

4. **Feature Scaling**
Feature Scaling standardizes the range of independent variables in the data. It ensures that each feature contributes equally to the clustering process, preventing variables with larger ranges from dominating the algorithm.

# Project Details

**Dataset**
Source: [Provide details about where the dataset was sourced from]

* Features: The dataset includes metrics such as:
  1. status_id           
  2. status_type         
  3. status_published    
  4. num_reactions       
  5. num_comments        
  6. num_shares          
  7. num_likes           
  8. num_loves           
  9. num_wows            
  10. num_hahas           
  11. num_sads            
  12. num_angrys  
  13. Methodology
  
**Data Preprocessing:**
* Applied Label Encoding to convert categorical features.
* Used Feature Scaling to normalize numerical features.

**Applying K-Means Clustering:**
* Employed the Elbow Method to determine the optimal number of clusters.
* Implemented K-Means clustering to segment sellers into distinct groups based on their posting behaviors.

**Evaluation:**
* Assessed cluster quality using metrics such as silhouette score and intra-cluster distances.
* Analyzed and interpreted the characteristics of each cluster.

**Insights:**
* Identified distinct clusters of Thai live sellers based on their posting strategies and engagement patterns.
* Provided actionable insights for optimizing content strategies and enhancing customer engagement.

**Conclusion:**
This project demonstrates the application of K-Means clustering to gain insights from data and make informed decisions. The use of clustering techniques helps in understanding complex data patterns and segmenting data into meaningful groups.

