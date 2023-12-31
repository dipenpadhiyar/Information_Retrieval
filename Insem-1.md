# Information Retrieval Insem-1 Paper DAIICT
### Question List

### Part A: Multiple Choice Questions
1. A data structure that maps terms back to the parts of a document in which they occur is called an:
   - (a) Postings list
   - (b) Incidence Matrix
   - (c) Dictionary
   - **(d) Inverted Index**
   - Explanation: An Inverted Index maps terms to the documents in which they appear, enabling efficient full-text searches.

2. A scheme where a weight is assigned to a term based upon the number of occurrences of the term within a document is called:
   - (a) Bag of Words
   - (b) Document Frequency
   - **(c) Term Frequency**
   - (d) Optimal weight
   - Explanation: Term Frequency assigns weights based on how often a term appears within a document.

3. Issues with the Jaccard coefficient are:
   - (a) It doesn't consider term frequency.
   - (b) It does not consider the fact that rare terms in a collection are more informative than frequent terms.
   - (c) It is biased towards shorter documents.
   - **(d) All of the above.**
   - Explanation: The Jaccard coefficient fails to consider term frequency, overlooks the significance of rare terms, and demonstrates bias towards shorter documents.
     
4. In TF-IDF the IDF contains a log operation. It is used to:
   - a. Decrease the weightage of other terms in the current document
   - b. Increase the weightage of frequently occurring words in the corpus
   - **(c) Increase the weightage of rarely occurring words in the corpus**
   - d. Decrease the weightage of documents containing rare words in the corpus
   - Explanation: IDF in TF-IDF increases the weightage of rarely occurring words by applying the logarithm.

5. Which of the following statements about Naive Bayes is incorrect?
   - **(a) Attributes are equally important.**
   - (b) Attributes are statistically dependent on one another given the class value.
   - (c) Attributes are statistically independent of one another given the class value.
   - **(d) All of the above**
   - Explanation: The incorrect statement is that attributes are equally important; Naive Bayes assumes attribute independence.

6. A __________ language model is characterized by P(t1, t2, t3) = P(t1)P(t2|t1).
   - (a) Unigram
   - **(b) Bigram**
   - (c) Trigram
   - (d) Fourgram
   - Explanation: A Bigram language model computes the probability of a sequence using the probability of individual words in pairs.

7. Which of the following can act as possible termination conditions in K-Means?
   - (a) For a fixed number of iterations.
   - (b) Assignment of observations to clusters does not change between iterations. Except for cases with a bad local minimum.
   - (c) Centroids do not change between successive iterations.
   - **(d) All of the above**
   - Explanation: Any of these conditions can be used to terminate the K-Means clustering algorithm.

8. Consider a scenario where total documents are 128. Relevant documents for a given query are 28. 
   IR System-I retrieves 25 documents. Out of 25, 16 are relevant. 
   What is the precision and recall of System-I?
   - (a) precision = 0.5 and recall = 0.1
   - **(b) precision = 0.57 and recall = 0.64**
   - (c) precision = 0.64 and recall = 0.57 
   - (d) precision = 0.5 and recall = 0.5
   - Explanation: Precision measures the accuracy of relevant results, while recall measures how many relevant results are returned.

9. Which one of the following is not a learning method?
   - **(a) BM25**
   - (b) Naive Bayes
   - (c) Logistic Regression
   - (d) None of the above
   - Explanation: BM25 is a ranking function used in information retrieval, not a machine learning learning method.

10. Consider a vector space model which uses only term frequency for retrieving the documents given a query. 
    Suppose we add some new documents to the collection. 
    Will the weights of the terms in the documents that were indexed before change?
    - a. It affects the term frequencies of a few terms
    - b. It affects the term frequencies of all terms
    - **(c) It has no effect on the term frequencies of a few terms**
    - d. It has no effect on the term frequencies of all terms
    - Explanation: If the new documents do not contain those terms, the weights for those terms will remain unchanged.

### Part B: Calculation Questions

1. Calculate the TF/IDF matrix for the following three sentences:
   - a. "I love big data processing but I hate Python."
   - b. "I love Information Retrieval."
   - c. "I love signal processing and Information Retrieval."

2. Given query Q, the following document IDs are relevant w.r.t. query Q [1, 4, 5, 9, 11, 13, 14, 15, 19, 20, 21]. Given a retrieval system, it retrieves a set of documents. The table below consists of a list of retrieved documents along with their relevance judgments. Calculate the Precision, Recall, F1-score, and MAP score of the retrieval. Show all the steps that you use for calculating the metrics. Draw an interpolated precision-recall curve. There are 11 relevant documents in the collection for query Q.

| Doc # | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 |
|-------|---|---|---|---|---|---|---|---|---|----|----|----|----|----|----|
| Rel   | 1 | 0 | 0 | 1 | 1 | 0 | 0 | 0 | 1 |  0 |  1 |  0 |  1 |  1 |  1  |
