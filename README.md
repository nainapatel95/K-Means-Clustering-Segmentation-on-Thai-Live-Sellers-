# K-Means Clustering Analysis of Thai Live Sellers' Posting Types

**Overview**

In this project, I utilized K-Means clustering to analyze and categorize Thai live sellers based on their posting types and engagement metrics. 

# Introduction to K-Means Clustering
K-Means clustering is a widely-used unsupervised machine learning algorithm that identifies inherent groups within unlabeled datasets. Unlike supervised learning, which requires predefined categories, K-Means relies solely on input features to uncover patterns and structures in data.

# K-Means Clustering Intuition
The algorithm operates by iteratively assigning data points to clusters represented by centroids, which are points at the centre of each cluster. Its objective is to minimize variance within each cluster, grouping data points based on their similarity in feature space.

**Key Concepts**

**Centroid:**
Each cluster is characterized by a centroid, which represents its centre. Data points are assigned to clusters based on proximity to these centroids.

**Elbow Method:**
This technique assists in determining the optimal number of clusters (K) by plotting the sum of squared distances from each point to its cluster centre (inertia) against K. The "elbow" point signifies the optimal K where inertia begins to plateau.

**Label Encoding:**
A preprocessing step where categorical variables are converted into numerical labels. This allows algorithms like K-Means to process categorical data effectively.

**Feature Scaling:**
Standardizing the range of independent variables ensures each feature contributes equally to clustering. It prevents variables with larger ranges from dominating the algorithm.

K-Means clustering is highly effective for discovering structure in data and is applied across diverse domains for tasks such as segmentation and pattern recognition.

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

