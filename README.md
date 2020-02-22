# Graph Embedding  
## Problem Statement  
* Similarity measurement of subgraph  
* Anormaly detection of subgraph  
* Prediction of next node - Hidden node  

## Reference materials
### Graph Embeddings — The Summary 
This article presents what graph embeddings are, their use, and the comparison of the most commonly used graph embedding approaches.
https://towardsdatascience.com/graph-embeddings-the-summary-cc6075aba007  

### Machine Learning — Text Classification, Language Modelling using fast.ai  
https://towardsdatascience.com/machine-learning-text-classification-language-modelling-using-fast-ai-b1b334f2872d  

## Research Approach  
Parallel to transfer learning in text analytic.  
1. Build a language model to predict the next words.  
2. Use the weights of last layer of the RNN as features (~400)  
3. Use those features to do different tasks  
- Translation - mapping features space in English to feature space in French  
- Classification - mapping features to prediction  
- Clustering of document  

Graph
1. Build model to predict the next node  
2. Use the embedding for different task  
- Clustering graph with similarity  



