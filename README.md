# Students Clustering

## Objective

The aim of this project is to make a clustering analysis based on the grades from 86 students. This way we will be able to detect and study different student profiles.

## The data
We have the grades from 86 students in 6 different subjects.

The subjects are:
• ML: Machine learning
• LA: Linear algebra
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

   
In order to carry out the above actions we will do the following:


1. Preprocessing
*  Consider different preprocessing steps and assess how do they affect the outcome.
2. Hierarchical Clustering
*  Vary linkage (single, complete, etc.) and distance metrics
*  Plot and analyze dendrograms, in order to answer:
3. How does the linkage or the distance influence the result?
4. What seems to be a reasonable clustering?
5. What are the clusters in that clustering?
6. Partitional Clustering
*  Do K-means varying the number of clusters
*  Analyze the Silhouette scores for the chosen clustering
