# 102117059_Topsis-for-pretrained-models
## EXPLAINATION
## Performance Matrix Definition: 
The code starts by defining a performance matrix. Each row of the matrix represents a task (e.g., Text Summarization, Text Generation), and each column represents a pre-trained model's performance on that task.
## Tasks Definition: 
The code defines a list of tasks corresponding to the rows of the performance matrix.
## Ideal and Anti-ideal Solutions Calculation: 
The code calculates the ideal and anti-ideal solutions for each column of the performance matrix. The ideal solution is the maximum value among all models for each task, while the anti-ideal solution is the minimum value.
## Distances Calculation: 
Using the ideal and anti-ideal solutions, the code calculates the Euclidean distances of each model's performance from both the ideal and anti-ideal solutions.
## TOPSIS Scores Calculation: 
Using the distances calculated in the previous step, the code computes the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) scores for each model and task. These scores represent the relative proximity of each model to the ideal solution compared to the anti-ideal solution.
## Best Model Selection: 
For each task, the code selects the model with the highest TOPSIS score, indicating its closeness to the ideal solution.
## Results Visualization:
The code plots a horizontal bar chart showing the TOPSIS score for each task, with the best model highlighted.
## Results Display: 
Finally, the code prints a table summarizing the results, including the task, the best model selected for each task, and the corresponding TOPSIS score.
