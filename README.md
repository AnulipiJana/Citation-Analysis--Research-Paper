# Citation Analysis
This project focuses on Citation Network Analysis, to recommend best research papers based on various factors such as page ranking, h-index, author popularity, number of publications and user-defined criteria. The project visualized graph-based network using citation data and help to analyze best research papers.

### Impact
1. Quantifying academic influence
2. Tracking knowledge dissemination
3. Identifying emerging research trends
4. Predicting future research directions

## Module1: Install Libraries & Preprocess Data
1. install and import libraries like dask-expr, python-louvain, prophet, pandas, numpy, networkx, matplotlib, ast etc. Setup require environment in google collab
2. generate information like shapes, missing values, duplicates about the dataset
3. Fill null values in references, abstract and auther column.

## Module2: Build & Visualize networks
1. *Author Citation Network*: connection between a auther cited by another authors
2. *Co-Authorship*: connection beteenw authers work together in a paper
3. *Paper Citation*: connection between papers cited by each other
### STEPS
1. Create citation networks
2. Visualize citation networks
3. Calculate degree_centrality, closeness_centrality, betweenness_centrality, eigenvector_centrality
4. Find best authors and papers based on centrality measure
5. User Quiry to search best recommend paper as per their criteria.

## Module3: Derived & Modify dataset for model training

## Module4: Train & Test Model
1. *XGBOOST*
2. *Neural Network*
