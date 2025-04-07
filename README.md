# Citation Analysis
This project focuses on Citation Network Analysis to recommend most relevant research papers based on various factors such as pageranking, h-index, author influence, number of publications and user-defined criteria. The project analyzes graph-based network using citation data and recommends corresponding research papers.

### Impact
1. Quantifying academic influence
2. Tracking knowledge dissemination
3. Identifying emerging research trends
4. Predicting future research directions

## Module1: Install Libraries & Preprocess Data
1. install and import libraries like dask-expr, python-louvain, prophet, pandas, numpy, networkx, matplotlib, ast etc. Setup require environment in google colab
2. Generate information about the dataset like shape, missing values, duplicates, etc. 
3. Fill null values in references, abstract and author column.

## Module2: Build & Visualize networks
1. *Author Citation Network*: connection between an author cited by other authors
2. *Co-Authorship Network*: connection between authors who have collaborated in any research paper
3. *Paper Citation Network*: connection between a research papers cited by other research papers
### STEPS
1. Create and visualize various networks
2. Calculate degree_centrality, closeness_centrality, betweenness_centrality, eigenvector_centrality of each network
3. Find most influential authors based on h-index and most relevant papers based on centrality measures
4. User Query to recommend research papers.

## Module3: Derived & Modify dataset for model training

## Module4: Train & Test Model
1. *XGBOOST*
2. *Neural Network*
