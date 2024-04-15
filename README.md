# 102117059_Topsis-for-pretrained-models
## EXPLAINATION
## Performance Matrix Definition: 
The code defines a performance matrix where each row represents a task (e.g., Text Summarization, Text Generation) and each column represents a pre-trained model's performance on that task.
## Tasks Definition: 
The code defines a list of tasks corresponding to the rows of the performance matrix.
## KMeans Clustering:
The code performs KMeans clustering on the transposed performance matrix. This clustering groups similar models together based on their performance across different tasks.
## Principal Component Analysis (PCA): 
PCA is applied to reduce the dimensionality of the performance matrix. This reduces the number of dimensions (features) while preserving the variance in the data. In this case, PCA is used to transform the performance matrix into a two-dimensional space for visualization purposes.
## Scatter Plot Visualization: 
The transformed data points from PCA are plotted in a scatter plot. Each point in the scatter plot represents a model in the reduced two-dimensional space. Models belonging to the same cluster are typically plotted closer to each other.
## Results Display: 
The code prints a results table showing the model indices and their assigned clusters. This table provides an overview of which models belong to each cluster.
