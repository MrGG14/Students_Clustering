# Clustering_ML

## The data
You will study data on student’s grades (grades.csv). These are grades in 6 subjects for 86 students.

The subjects are:
• ML: Machine learning
• LA: Linear algebra
1
• OR: Operations research
• BD: Big Data
• ST: Statistics
• PR: Probability
Not all subjects are graded on the same scale. Some use the 0 to 100 scale, some 0 to 10, some 0 to 1, and
some E to A scale.


## What to do?

The aim is to try and discover meaningful clusters in the data and describe, that is, interpret them. In order
to do this, several actions need to be carried out:
1. Preprocess the data;
2. Consider different clustering algorithms;
3. Assess their output.
4. Choose a single, final clustering and describe it.
In order to carry out the above actions, you need to, at least, do the following:
1. Preprocessing
• Consider different preprocessing steps and assess how do they affect the outcome.
2. Hierarchical Clustering
• Vary linkage (single, complete, etc.) and distance metrics
• Plot and analyze dendrograms, in order to answer:
1. How does the linkage or the distance influence the result?
2. What seems to be a reasonable clustering?
3. What are the clusters in that clustering?
3. Partitional Clustering
• Do K-means varying the number of clusters
• Choose a number of clusters and justify the choice
• Analyze the Silhouette scores for the chosen clustering
