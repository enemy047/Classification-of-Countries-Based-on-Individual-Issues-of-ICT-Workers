# ICT Worker Cluster Analysis

This project performs a clustering analysis of 37 countries based on nine issues affecting ICT workers.

## Methods Used
- K-Means Clustering
- Hierarchical Clustering
- PCA Visualization
- Silhouette Score Analysis
- Elbow Method

## Dataset
37 countries with 9 ICT worker issues including:

- Friendship Circles
- Job Insecurity
- Self-efficacy
- Work Satisfaction
- Work Overload
- Work-Home Conflict
- Work Exhaustion
- Turnover Intention
- Turnaway Intention

Each issue is measured using:
- FSMean (factor score mean)
- Smean (simple mean)

## Key Findings
The optimal clustering solution identified **2 distinct clusters** of countries with different ICT worker environments.

Cluster 0: Emerging and developing markets  
Cluster 1: Developed and semi-developed economies

The clustering results show strong robustness with an **Adjusted Rand Index of 0.8765** between FSMean and Smean clustering methods.

## Tools
Python  
Pandas  
Scikit-learn  
Matplotlib  
Seaborn  

## Files
- `ict_worker_clustering_analysis.ipynb` – full analysis code
- `ICT_Worker_Cluster_Analysis_Report.docx` – full report
