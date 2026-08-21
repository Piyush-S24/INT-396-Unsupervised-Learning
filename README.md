# INT396 — Unsupervised Learning

> **Important Note:** If you experience access issues, preview errors, or are
> unable to view any PDF or script directly on GitHub, please download the file
> to your local machine to access it properly.

---

## Units and Topics

### Unit I — Foundations of Unsupervised Learning
- Problem formulation for unsupervised learning
- Real-life use cases: Market segmentation, Customer behavior analysis
- Anomaly & fraud detection
- Pattern discovery in biological and social data
- Distance & similarity metrics: Euclidean, Manhattan, Cosine similarity
- when and why distance choice matters

### Unit II — Partition-Based Clustering
- Clustering fundamentals and assumptions, Hard vs. Soft clustering
- k-Means algorithm: Objective function, Initialization strategies (Random, k-Means++)
- Convergence and limitations, k-Medoids (PAM) vs. k-Means
- Data standardization and scaling impact
- MiniBatch k-Means for large-scale datasets
- Cluster Validation: Inertia (WCSS), Silhouette Coefficient
- Davies–Bouldin Index, Elbow method pitfalls

### Unit III — Hierarchical & Density-Based Clustering
- Hierarchical clustering: Agglomerative vs. Divisive
- Linkage methods (single, complete, average, Ward)
- Dendrogram interpretation
- Density-based clustering: DBSCAN fundamentals
- e-neighborhood, MinPts
- Noise and border points
- Comparison: k-Means vs. Hierarchical vs. DBSCAN

### Unit IV — Dimensionality Reduction and Representation Learning
- Need for Dimensionality Reduction
- Linear Dimensionality Reduction Techniques (PCA – Geometric Intuition)
- Manifold Learning Overview
- Non-Linear Dimensionality Reduction Concepts - t-SNE
- UMAP – Conceptual
- Autoencoder Intuition

### Unit V — Association Rule Mining & Anomaly Detection
**Association Rule Mining**
- Support, Confidence, Lift, Conviction
- Apriori Algorithm
- FP-Growth algorithm
- Market Basket Analysis

**Anomaly Detection**
- Anomaly vs. novelty detection
- Isolation Forest
- Local Outlier Factor (LOF)
- Applications in Cybersecurity and Fraud Detection

### Unit VI — Evaluation and Applications of Unsupervised Learning
- Internal and External Clustering Validation Metrics
- Silhouette Score and Cohesion–Separation Intuition
- Stability-Based Evaluation
- Interpretability Challenges in Unsupervised Learning
- Real-World Case Studies
- Ethical Considerations in Pattern Discovery

---

## List of Practicals

**Practical 1** — Analyze customer behavior patterns by performing exploratory data analysis and evaluating Euclidean, Manhattan, and Cosine similarity measures on an unlabeled customer dataset.
*Analyze unlabeled datasets using exploratory data analysis and compute appropriate similarity and distance measures to identify meaningful patterns and relationships among data instances.*

**Practical 2** — Develop a customer segmentation solution by implementing and comparing k-Means and k-Medoids clustering techniques on the Mall Customers dataset.
*Develop the capability to discover meaningful customer segments and translate clustering results into actionable business insights.*

**Practical 3** — Design a scalable clustering model by implementing k-Means from scratch and validating its performance using the Scikit-learn framework.
*Build competency in designing clustering solutions through algorithmic implementation and validating their effectiveness using industry-standard machine learning frameworks.*

**Practical 4** — Investigate the influence of data preprocessing by examining the effect of feature scaling and standardization on clustering quality and model convergence.
*Gain proficiency in improving the quality and reliability of unsupervised learning models through appropriate data preprocessing and feature transformation techniques.*

**Practical 5** — Determine the optimal clustering configuration by applying Elbow Method, Silhouette Score, and Davies–Bouldin Index on a real-world marketing dataset.
*Develop the ability to evaluate multiple clustering solutions and justify the selection of the most suitable model using objective validation measures.*

**Practical 6** — Analyze hierarchical relationships in unlabelled data by constructing dendrograms and comparing multiple linkage strategies using Hierarchical Clustering.
*Acquire the ability to interpret hierarchical relationships within complex datasets and derive meaningful insights from cluster structures.*

**Practical 7** — Develop a density-based clustering solution by applying DBSCAN and evaluating the impact of e (epsilon) and MinPts parameters on cluster formation and noise detection.
*Develop competency in identifying naturally occurring clusters and distinguishing anomalous observations within real-world datasets.*

**Practical 8** — Evaluate clustering techniques for diverse data distributions by benchmarking k-Means, Hierarchical Clustering, and DBSCAN using clustering validation metrics.
*Gain the ability to critically evaluate and recommend appropriate clustering techniques based on dataset characteristics, performance, and application requirements.*

**Practical 9** — Develop an efficient feature representation model by applying Principal Component Analysis (PCA) to reduce dimensionality while preserving maximum variance.
*Develop proficiency in representing high-dimensional data in compact feature spaces to improve computational efficiency and analytical effectiveness.*

**Practical 10** — Compare dimensionality reduction techniques by visualizing high-dimensional datasets using PCA, t-SNE, and UMAP for exploratory data analysis.
*Acquire the ability to explore, visualize, and interpret complex datasets using advanced dimensionality reduction techniques for effective knowledge discovery.*

**Practical 11** — Extract actionable business insights by implementing Apriori and FP-Growth algorithms for Market Basket Analysis and interpreting association rules.
*Develop competency in extracting valuable knowledge from transactional data to support business intelligence, recommendation systems, and strategic decision-making.*

**Practical 12** — Develop an anomaly detection framework by comparing Isolation Forest and Local Outlier Factor (LOF) for identifying unusual observations in cybersecurity or financial datasets.
*Gain the ability to identify unusual behavioural patterns and detect anomalies for improving the reliability and security of intelligent systems.*

**Practical 13** — Assess the quality of unsupervised learning models using clustering validation metrics, visualization techniques, and stability analysis to support model selection.
*Develop the capability to assess the robustness, reliability, and effectiveness of unsupervised learning models using appropriate validation and visualization techniques.*

**Practical 14** — Develop an end-to-end unsupervised learning solution by integrating data preprocessing, clustering, dimensionality reduction, anomaly detection, visualization, evaluation, and presentation of insights for a real-world application in healthcare, finance, education, agriculture, cybersecurity, or retail.
*Demonstrate the ability to design, develop, evaluate, and communicate an end-to-end unsupervised learning solution.*
