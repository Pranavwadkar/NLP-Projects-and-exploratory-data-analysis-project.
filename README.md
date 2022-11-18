# NLP-Projects-and-exploratory-data-analysis-project.
The models of NLP that i created working with tcs



Elaboration of the nlp notebooks 




![image](https://user-images.githubusercontent.com/61554733/202656712-a0cd13b5-be8b-4a84-845b-4258baccc262.png)


Text summarization is the process of shortening a set of data computationally, to create a subset that represents the most 
important or relevant information within the original content. In addition to text.


### There are mainly two types of text summarization techniques


1. Extractive Text summarization
Def - Extractive summarization aims at identifying the salient information that is then extracted and grouped together to form a concise summary. 

Algorithms - Google BERT ,LSA, GPT ,GPT-3

3. Abstractive Text summarization
Def- An abstractive summarization method is generating the meaningful summary without copying the contents of the input text but to present the relevent
summary in the form of new and relevent information

Algorothms -Transformer,Google'Prgasus



## Steps for implementation of extractive text summarization-
1. Text cleaning
2. Sentence tokenization
3. Word frequency table
4. Clustering
5. Generating the summary by calcularting the score of each tokensised sentence.


Extractive Summarization that i proceseed using Word2vec
### Text summarization using word2vec on chinese rocket falling news with metrics

One of the important libraries used in the domain of Natural language processing is NLTK(ie. Natural language Toolkit)

NLTK is a leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for 
classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries, and an active discussion forum.



The following code is the core part of Text sumaary using word2vec it basically gives the vectors present in the pre trained word embeddings and assigns it
for the words that are present in the input paragraph

<img width="607" alt="image" src="https://user-images.githubusercontent.com/61554733/202703736-0287a7f3-4da3-4778-a924-0c5c9eb14e65.png">



Text summarization using Word2vec is a unique kind of text summarization which uses the pre-trained word embeddings to process the input para and generating 
summary for the same.


### Evaluation of the scores for different summarization model


Metrics Used- 

Bleu(BiLingual Evaluation Understudy) Score- It is a metric for automatically evaluating machine-translated text. BLEU score is a number between zero and one that measures the similarity of the machine-translated text to a set of high quality reference translations.

Rouge Score- 

Rouge also know as Recall-Oriented Understudy for Gisting Evaluation,is a set of metrics and a software package used for evaluating automatic summarization and machine translation software in natural language processing. The metrics compare an automatically produced summary or translation against a reference or a set of references (human-produced) summary or translation.




#### Different levels in rouge score-


Now diving deep in about the rouge score, there are three types of rouge scores ie. Rouge-1,Rouge-2,Rouge-3
Rouge-1 is described as  the overlap of unigram (each word) between the system and reference summaries.
Rouge -2  the overlap of bigrams between the system and reference summaries.




#### More detailed analysis of all my nlp workbooks and projects are in the DOC which is uploaded in this same repo ,'Analysis and evaluation of various text summasrization model for summary extraction from financial documents'








