# implementation-of-Sentiment-Analysis-using-Natural-Language-Processing
The increasing quantity of false information circulating on its platform worries the corporation. You have been tasked with finding out how to spot fake news and developing a system to do so. Together, let's investigate and tidy up the data before attempting to categorise fabricated vs real news reports.




**Lowercase** refers to the process of converting all letters in a text to their lowercase form. Lowercasing is a common preprocessing step applied to text data for various NLP tasks. It helps in standardizing text by ensuring that words are treated consistently regardless of their original casing, thereby reducing the vocabulary size and improving model performance.

Some reasons why lowercase is commonly used in NLP are Normalization, Reducing Vocabulary Size, Improved Generalization and Consistency…

**Stopwords** refer to commonly used words in a language that are often removed from text during preprocessing due to their high frequency and lack of significant semantic meaning.
The removal of stopwords is a common preprocessing step in NLP tasks, and it serves several purposes like
Improved Accuracy, Normalization, Improving Efficiency, Reducing Noise…

**Lemmatization** is a fundamental technique in Natural Language Processing (NLP) used to reduce words to their base or canonical form, known as a lemma. The process involves grouping together different inflected forms of a word to analyze them as a single item.
Key points about lemmatization: Context Preservation, Part-of-Speech (POS) Consideration, Improved Accuracy, Word Normalization…


**Bag of Words (BoW)** is a fundamental technique used in Natural Language Processing (NLP) for text representation and feature extraction. It involves converting text data into numerical vectors, disregarding grammar and word order but focusing on word occurrence frequencies within the document.
Here's an overview of how the Bag of Words model works:

**Tokenization:** The process begins by tokenizing the text into individual words or tokens. This step typically involves removing punctuation, splitting text into words, and converting them to lowercase. 

**Vocabulary Construction:** Next, a vocabulary or dictionary is created, containing unique words from the entire corpus (collection of documents). Each unique word becomes a feature in the vocabulary. 

**Vectorization:** For each document in the corpus, a numerical vector is created. The length of the vector equals the size of the vocabulary. Each element in the vector represents the count or frequency of the corresponding word from the vocabulary in the document. 

**Sparse Representation:** As many words may not occur frequently in a document, resulting vectors are often sparse, containing mostly zeros. This representation is typically stored in a sparse matrix format to efficiently handle large datasets. 

