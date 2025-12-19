# Unsupervised Learning Analysis – From Concepts to Olivetti Faces dataset apllied

This project documents a step-by-step exploration of **unsupervised learning techniques**, starting from fundamental clustering concepts and algorithms, and culminating in their practical application on the **Olivetti Faces dataset**. The notebook reflects a learning-driven workflow where algorithms are first understood on general data and then applied to real-world image data.

---

## Project Files

- Unsupervised.ipynb – Notebook containing all experiments and analysis

---

## 1. Objective

The objectives of this notebook are:
- To understand core unsupervised learning algorithms
- To study how clustering behaves without labeled data
- To analyze the impact of scaling and dimensionality
- To apply learned techniques to facial image data

---

## 2. Understanding Unsupervised Learning

Initial exploration focuses on:
- The concept of learning without target labels
- Grouping data based on similarity and distance
- Differences between supervised and unsupervised approaches
- Use cases of clustering and dimensionality reduction

---

## 3. Data Preparation and Scaling

Before applying algorithms:
- Datasets are loaded and inspected
- Feature scaling is applied where distance-based methods are used
- The importance of normalization for clustering is observed

Scaling is shown to significantly influence cluster formation.

---

## 4. K-Means Clustering Exploration

K-Means clustering is explored in detail:
- Applying K-Means with different values of K
- Understanding centroids and cluster assignments
- Observing how inertia changes with cluster count

### Elbow Method
- Inertia vs number of clusters is plotted
- Optimal K is selected based on elbow point

This section builds intuition about cluster compactness.

---

## 5. Cluster Evaluation and Interpretation

Clusters are analyzed using:
- Visual inspection
- Intra-cluster similarity
- Inter-cluster separation

Limitations of K-Means such as sensitivity to initialization and scaling are observed.

---

## 6. Transition to Real-World Data

After understanding clustering behavior on general data, the same concepts are applied to real-world image data to test scalability and robustness.

---

## 7. Olivetti Faces Dataset

The Olivetti Faces dataset contains:
- 400 grayscale facial images
- 40 individuals
- 10 images per individual
- Image resolution of 64 × 64 pixels

Each image is flattened into a high-dimensional feature vector.

---

## 8. Dimensionality Reduction with PCA

Due to the high dimensionality of image data:
- PCA is applied to reduce feature space
- Eigenfaces are generated and visualized
- Principal components capture dominant facial features

PCA improves both efficiency and clustering quality.

---

## 9. Clustering Faces Using K-Means

K-Means is applied to:
- Original pixel feature space
- PCA-reduced feature space

Cluster assignments are analyzed by:
- Visualizing face images per cluster
- Observing similarity in lighting, pose, and facial structure

---

## 10. Observations from Olivetti Dataset

- PCA significantly improves clustering performance
- Faces cluster more by visual similarity than identity
- Lighting and orientation strongly influence clustering
- Unsupervised learning captures patterns without labels

---

## 11. Conclusion

This notebook demonstrates a progressive learning approach to unsupervised learning. By first exploring clustering algorithms and their behavior, and then applying those insights to the Olivetti Faces dataset, the project highlights how unsupervised methods can uncover meaningful structure in complex, high-dimensional data.

---

