## Text Mining and Information Retrieval (ITIS 6010 @ UNCC) HW/Projects

### Preprocessing Pipeline
- Preprocessor that identifies numbers and punctuation  
- Preprocessor that identifies three-letter sets  

### Sentiment Analysis
- Identifies whether a tweet is positive or negative, given a Twitter data set
- Uses NLTK, scikit-learn, TF-IDF, word embeddings, Naïve Bayes, and Random Forest

### Topic Modeling
- Extracts clusters of topics from a collection of text documents (research abstracts) using unsupervised learning  
- Utilizes LDA from scikit-learn and Gensim, Doc2Vec, and SBERT (all-MiniLM-L6-v2) for text embeddings  
- Applies t-SNE for dimensionality reduction, hierarchical clustering with dendrograms, and visualizes results using pyLDAvis 

### Document Search
- Implements SBERT models ("allenai-specter" and "all-MiniLM-L6-v2") to create document embeddings, and uses TF-IDF and TF to create word-level embeddings
- Constructs a search engine based on cosine similarity, dot product, euclidean distance, and geometric mean scores to handle and test query functionality
- Evaluates search effectiveness using metrics such as Recall@1 and Mean Reciprocal Rank (MRR)
