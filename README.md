# Machine-Learning
TOPIC - PDF Document Clustering & optimizing the time for Finding Optimum Number of Categories(K)

PROBLEM STATEMENT: 
Document Clustering is an application of Machine Learning. It simply means lets say we are given some 100 PDFs & we don’t know which category they belong to. Some might be Machine Learning docs, some may be Physics docs, etc. Now we want to categorize into various categories is Document Clustering. Now to separate them into various clusters is the problem. But another problem is if we apply Unsupervised ML tech like K-means on the term-document matrix of docs, we don’t know the optimal value of K.

PROPOSED SOLUTION:
We will use Elbow technique to find the optimum number of clusters for the set of PDF documents. In Elbow technique the clustering is
done for k=1 to k=n where n is defined by the programmer.Then a metric is calculated for each ‘k’ (variance, distortion, or inertia)
and a graph is plotted of metric vs ‘k’. From the shape of the graph the value of ‘k’ is picked that forms the elbow in the graph.
