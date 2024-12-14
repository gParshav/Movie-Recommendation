# Graph-Based Movie Recommendation System

## Overview
The movie recommendation problem can be effectively addressed using graph-based algorithms, particularly **Graph Convolutional Networks (GCNs)** and **Graph Attention Networks (GATs)**. These approaches leverage the inherent relationships between users and movies to generate precise and personalized recommendations.

In this system, users and movies are represented as nodes in a **bipartite graph**, with edges signifying user interactions (e.g., clicks or ratings). By modeling these interactions, GCN and GAT algorithms capture complex user-movie relationships and make recommendations based on both direct and higher-order connections.

---

## Key Features
- **Higher-Order Relationships**  
  GCNs and GATs analyze not just direct user-movie interactions but also their broader network of relationships, uncovering intricate patterns.

- **Contextual Variability**  
  The models adapt to users' diverse interests and behaviors by learning from their network connections and interactions.

- **Class Imbalance Management**  
  Graph-based algorithms handle the imbalance caused by the sparse reviews in movie datasets, ensuring robust recommendations.

---

## Methodology
To enhance recommendation accuracy, the system employs two prediction methods:

### 1. Click Prediction using LightGCN
- **LightGCN** is a lightweight Graph Convolutional Network designed to model user-movie interactions efficiently.
- It captures latent patterns in the data, enabling the system to predict which movies users are likely to click on.

### 2. Rating Prediction using IGMC and GraphRec
- **Inductive Graph-Based Matrix Completion (IGMC)** and **GraphRec** models are built on Graph Attention Networks (GATs).
- These models incorporate explicit user-movie interaction data to provide personalized rating predictions.

---

## Advantages
- Models **higher-order neighborhoods** for better pattern recognition.  
- Captures the **variability** in user preferences.  
- Effectively manages **sparse datasets** and **class imbalance** issues.  

---

## Conclusion
By integrating cutting-edge graph-based algorithms like **GCNs**, **GATs**, and **LightGCN**, this system delivers accurate and high-quality movie recommendations. It considers not only user preferences but also the relational and contextual nuances in the data.

---

### References
1. GCNs and GATs for graph-based recommendation systems.  
2. [LightGCN Paper](https://arxiv.org/abs/2002.02126)  
3. IGMC and GraphRec for rating prediction models.  
