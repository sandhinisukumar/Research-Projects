# AUTOMATIC TEXT SUMMARIZATION WITH KEYWORD EXTRACTION IN MALAYALAM


## 1. INTRODUCTION

Text mining is the process of providing high-quality data from the text. The process is done based on some Natural Language processing (NLP) techniques like Parts-of-speech (POS) tagging, parsing, tokenization and so on. The text mining includes the two tasks, such as Text summarization and keyword extraction. Automatic text summarization is the method of automatically summarizing the text or document.  The keyword extraction is the process of extracting the phrases and words from the text.  This summary provides an overview of the entire document to the reader. The input to the summarization process may contain one or more documents. When only one document is the input, the process is known as single document summarization. The multi document summarization related to group of documents. The output of the process is the summary consisting of number of sentences related to the input.

## 2. MOTIVATION

The main motivation behind this is to develop a tool which computationally efficient and provide a short abstract of a document to the users. This helps to find more relevant information. In single document summarization, can judge if the document is relevant to the topic or not. In multi-document summarization, reduce the search time, the goal is to provide the short information. And also can cluster the similar documents and provides a multi-document summary based on the similarities.  

## 3. PROBLEM DEFINITION
Text summarization methods have been recently implemented in some Indian languages. For Malayalam, proposes an automatic text summarization based on keyword extraction.

## 4. REQUIREMENTS
A Dataset: The corpus is created from the data extracted from online Malayalam news articles.
Indexing: The next is indexing. Normal indexing methods are used to extract the words by splitting the document. 
Keyword extraction: The keyword extraction is based on simple statistical approach.  Here extract the keywords from the documents based on the position of a word inside the document, the term frequency, and inverse document frequency.
Text summarization: From the documents, we have to provide a meaningful summary. Calculating  the word frequency, term frequency, and inverse document frequency for all words in the given document. From the weight of the sentence is calculated based on the mentioned scores. The sentences are extracted.

## 5. SYSTEM DESIGN
Proposes an automatic Summarizer for Malayalam using keyword extraction method. The first step is creating the corpus of the data extracted from online Malayalam news articles.


 ## 6. FUTURE SCOPE
The future work is generating the summary of the document by using neural networks.
