# SNLP_SemanticSimilarity

Repo contains some experiments to check semantic similarity between sentences which may not necessarily have same words but semantically may be similar, for the three most popular datasets that are used in the Semantic Similarity task: Semantic Text Similarity (STS), Microsoft Research Paraphrase Corpus (MSR) and  Quora Question pair (QQP) datasets. Two popular methods for the vector representation: Term Frequency - Inverse Document Frequency (TF-IDF) and Sentence-BERT (SBERT) were used. Cosine similarity is used as for the similarity metric between these representations.

TF-IDF and SBERT were evaluated on the test data and observe how well they are classified as similar or not similar. This is a baseline, which can be compared to the finetuned results with fine-tuned Llama 2.

The following were the results across the three datasets. 
![alt text](https://github.com/pal-priyanshi/SNLP_SemanticSimilarity/blob/main/TFIDF_SBERT.jpg)
