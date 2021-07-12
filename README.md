# Text_Summarizer_Using_TextRank

Text summarization is a process of generating a concise and meaningful summary of text from multiple text resources such as books, news articles, blog posts, research papers, emails, and tweets.

Text summarization can broadly be divided into two categories — Extractive Summarization and Abstractive Summarization.

  1. Extractive Summarization: These methods rely on extracting several parts, such as phrases and sentences, from a piece of text and stack them together to create a summary. Therefore, identifying the right sentences for summarization is of utmost importance in an extractive method.
  2. Abstractive Summarization: These methods use advanced NLP techniques to generate an entirely new summary. Some parts of this summary may not even appear in the original text.
  
Here, we will be focusing on the extractive summarization technique.
 
The main algorithm which has been used in text summarization is TextRank. TextRank is an extractive and unsupervised text summarization technique.
 
In text summarization other than TextRank another algorithm came in use and it is called PageRank. PageRank is used primarily for ranking web pages in online search results.
 
The dataset can be downloaded from the link below:
 
    https://drive.google.com/file/d/1HPShiXSrHMNlfcMZn-WFYjoftitOH9fJ/view?usp=sharing
    
GloVe word embeddings are vector representation of words. These word embeddings will be used to create vectors for our sentences. We could have also used the Bag-of-Words or TF-IDF approaches to create features for our sentences, but these methods ignore the order of the words and the number of features is usually pretty large.

Use the link given below for the pre-trained Wikipedia 2014 + Gigaword 5 GloVe vectors.

    https://nlp.stanford.edu/data/glove.6B.zip
