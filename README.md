# News-Classification-using-Unsupervised-Learning
This project uses clustering algorithms (KMeans, Agglomerative) to categorize news articles based on truthfulness. It involves text preprocessing, TF-IDF, PCA, and silhouette score evaluation to find the optimal clusters for classifying news articles.

# Key Steps:
# 1.Data Loading and Preprocessing:
Load the news dataset.
Clean the text by removing irrelevant characters, converting to lowercase, and tokenizing.
Apply stemming to reduce words to their root form.
# 2.Feature Engineering:
Use TF-IDF (Term Frequency-Inverse Document Frequency) to convert text data into numerical vectors.
Apply Principal Component Analysis (PCA) to reduce the dimensionality of the data for better clustering performance.
# 3.Clustering:
Implement K-Means and Agglomerative Hierarchical Clustering algorithms.
Determine the optimal number of clusters using the elbow method for K-Means and dendrogram analysis for Agglomerative Clustering.
Train the models with the optimal number of clusters.
# 4.Evaluation:
Evaluate the clustering performance using the silhouette score.
Compare the scores of the two algorithms to identify the best-performing model.
# 5.Visualization:
Visualize the clusters using scatter plots, highlighting the centroids (K-Means) or cluster boundaries (Agglomerative Clustering).
# 5.Testing and Interpretation:
Test the model with sample news articles.
Preprocess the sample data and apply the trained model to predict their cluster assignments.
Interpret the results based on the cluster characteristics.

# Conclusion: The project demonstrates the application of unsupervised learning techniques for news classification. By identifying clusters of news articles with similar characteristics, this approach can be used for tasks such as fake news detection, news topic categorization, and personalized news recommendations.
