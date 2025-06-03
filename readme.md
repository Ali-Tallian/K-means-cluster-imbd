🎬 IMDB Movie Ratings Clustering
This project performs K-means clustering on IMDB movie ratings using Python. The aim is to group movies into clusters based on their rating and analyze the genre distribution within each cluster.

📁 Dataset
The project uses the IMDB-Movie-Data.csv dataset, which includes various details about movies such as:

Rating: User rating score

Genre: Movie genres (comma-separated)

Revenue (Millions)

Metascore

🔍 Note: Only movies with both Revenue (Millions) and Metascore values are included in the analysis.

🔍 Objective
Group movies into clusters based on ratings

Visualize the clusters

Analyze the most common genres within each cluster

🧪 Clustering Strategy
Predefined Rating Thresholds for Initial Clusters:

>= 8.0: Top Rated (Cluster 0)

6.0 - 7.9: Average Rated (Cluster 1)

< 6.0: Low Rated (Cluster 2)

K-means Clustering:

Ratings are clustered using a simple K-means algorithm (1D)

Initial centroids: [8.5, 7.0, 5.0]

Convergence based on unchanged centroids

📊 Output & Visualization
Scatter Plot: Displays clustering of movies based on ratings with different colors

Genre Analysis: Prints the frequency of genres within each cluster

🧰 Libraries Used
pandas — for data manipulation

numpy — for numerical operations and clustering

matplotlib — for visualization
