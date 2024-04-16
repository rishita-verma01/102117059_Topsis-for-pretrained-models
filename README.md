# 102117059_Topsis-for-pretrained-models
## EXPLAINATION
## Importing Libraries: 
We start by importing the necessary libraries. NumPy is used for numerical computations, and matplotlib is used for data visualization.
## Define the Decision Matrix:
We define a decision matrix that represents the performance of each pre-trained model on each criterion. Each row of the matrix corresponds to a model, and each column corresponds to a criterion. In this example, we assume we have three models (Model A, Model B, and Model C) and three criteria (accuracy, fluency, and diversity of responses).
## Normalize the Decision Matrix: 
The decision matrix is normalized to ensure that all criteria are on the same scale. This is done by dividing each element of the matrix by the square root of the sum of squares of the elements in the corresponding column.
## Define Weights for Criteria: 
We define weights for each criterion to reflect their relative importance in the decision-making process. These weights are subjective and should be adjusted based on the specific requirements of the problem.
## Calculate Weighted Normalized Decision Matrix: 
The weighted normalized decision matrix is obtained by element-wise multiplication of the normalized matrix with the weights.
## Determine Ideal and Negative-Ideal Solutions: 
The ideal solution is calculated as the maximum value along each criterion, and the negative-ideal solution is calculated as the minimum value along each criterion.
## Calculate Distance to Ideal and Negative-Ideal Solutions:
The Euclidean distance between each alternative (model) and the ideal solution, as well as the distance to the negative-ideal solution, is calculated.
## Calculate Relative Closeness: 
The relative closeness of each alternative to the ideal solution is calculated using the formula-
Relative Closeness
=
Distance to Negative-Ideal
Distance to Ideal
+
Distance to Negative-Ideal
Relative Closeness= 
Distance to Ideal+Distance to Negative-Ideal
Distance to Negative-Ideal
## Rank the Alternatives:
The alternatives (models) are ranked based on their relative closeness to the ideal solution. Models with higher relative closeness values are considered better.
## Print the Ranked Models: 
The ranked models are printed along with their corresponding ranks.
## Optional: Visualization:
The decision matrix is visualized using a heatmap, where each cell represents the performance of a model on a criterion. This visualization helps in understanding the relative performance of different models across criteria.
