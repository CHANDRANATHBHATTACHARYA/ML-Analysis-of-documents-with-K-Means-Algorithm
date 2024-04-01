# ML-Analysis-of-documents-with-K-Means-Algorithm
Text Document Clustering with K-means and Jaccard Index
This project aims to cluster documents from the "Bag of Words" dataset obtained from the UCI Machine Learning Repository. 
The dataset contains five text collections represented as bags-of-words. 
The task is to apply K-means clustering for different values of K and determine the optimal value of K for each dataset.

Dataset Description:
The datasets consist of text collections, where each document is summarized as a bag (multiset) of words. The individual documents are identified by document IDs, and the words are identified by word IDs.

After preprocessing, each collection has a vocabulary of unique words truncated to only include words that occurred more than ten times overall in that collection.

For each collection XYZ:

vocab.XYZ.txt: Vocabulary file listing all words that appear in the collection XYZ, one word per line.
docword.XYZ.txt: File listing the number of times each word in vocab.XYZ.txt occurs in each document. It contains header lines followed by lines in the format: docID wordID count.
Dataset Information
Enron Emails:

Original source: www.cs.cmu.edu/~enron
D=39861, W=28102, N=6,400,000 (approx)
NIPS Full Papers:

Original source: books.nips.cc
D=1500, W=12419, N=1,900,000 (approx)
KOS Blog Entries:

Original source: dailykos.com
D=3430, W=6906, N=467714
Approach
Clustering Algorithm: K-means clustering
Similarity Measure: Jaccard index, measuring similarity between two documents based on the overlap of words present in both documents.
Results
The project will report the clustering results for different values of K on the three smaller datasets: Enron Emails, NIPS Blog Entries, and KOS Blog Entries.

