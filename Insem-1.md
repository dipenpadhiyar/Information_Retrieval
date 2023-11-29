# Information Retrieval Insem-1 Paper DAIICT
### Question List

1. A data structure that maps terms back to the parts of a document in which they occur is called an:
   - (a) Postings list
   - (b) Incidence Matrix
   - (c) Dictionary
   - **(d) Inverted Index**

2. A scheme where a weight is assigned to a term based upon the number of occurrences of the term within a document is called:
   - (a) Bag of Words
   - (b) Document Frequency
   - **(c) Term Frequency**
   - (d) Optimal weight

3. Issues with the Jaccard coefficient are:
   - **(a) It doesn't consider term frequency.**
   - **(b) It does not consider the fact that rare terms in a collection are more informative than frequent terms.**
   - **(c) It is biased towards shorter documents.**
   - **(d) All of the above.**

4. In TF-IDF the IDF contains a log operation. It is used to:
   - a. Decrease the weightage of other terms in the current document
   - b. Increase the weightage of frequently occurring words in the corpus
   - **c. Increase the weightage of rarely occurring words in the corpus**
   - d. Decrease the weightage of documents containing rare words in the corpus

5. Which of the following statements about Naive Bayes is incorrect?
   - **(a) Attributes are equally important.**
   - (b) Attributes are statistically dependent on one another given the class value.
   - (c) Attributes are statistically independent of one another given the class value.
   - **(d) All of the above**

6. A __________ language model is characterized by P(t1, t2, t3) = P(t1)P(t2|t1).
   - (a) Unigram
   - **(b) Bigram**
   - (c) Trigram
   - (d) Fourgram

7. Which of the following can act as possible termination conditions in K-Means?
   - (a) For a fixed number of iterations.
   - (b) Assignment of observations to clusters does not change between iterations. Except for cases with a bad local minimum.
   - (c) Centroids do not change between successive iterations.
   - **(d) All of the above**

8. Consider a scenario where total documents are 128. Relevant documents for a given query are 28. 
   IR System-I retrieves 25 documents. Out of 25, 16 are relevant. 
   What is the precision and recall of System-I?
   - (a) precision = 0.5 and recall = 0.1
   - **(b) precision = 0.57 and recall = 0.64**
   - (c) precision = 0.64 and recall = 0.57 
   - (d) precision = 0.5 and recall = 0.5

9. Which one of the following is not a learning method?
   - **(a) BM25**
   - (b) Naive Bayes
   - (c) Logistic Regression
   - (d) None of the above

10. Consider a vector space model which uses only term frequency for retrieving the documents given a query. 
    Suppose we add some new documents to the collection. 
    Will the weights of the terms in the documents that were indexed before change?
    - a. It affects the term frequencies of a few terms
    - b. It affects the term frequencies of all terms
    - **(c) It has no effect on the term frequencies of a few terms**
    - d. It has no effect on the term frequencies of all terms
