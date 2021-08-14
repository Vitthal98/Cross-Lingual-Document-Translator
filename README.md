# Cross-Lingual-Document-Translator
*Implementation of IBM models 1 and 2 for English &lt;--> Dutch document translator*

This project was completed in partial requirement of the course INFORMATION RETRIEVAL (CS F469) offered during First Semester 2019-20 at BITS Pilani, Pilani Campus.

In our assignment, we have implemented the code for IBM models 1 and 2 to create a translator and we have calculated our accuracy based on cosine similarity and jaccard coefficient.

## What is Cross-language information retrieval (CLIR)?

> Cross-language information retrieval (CLIR) is a subfield of information retrieval dealing with retrieving information written in a language different from the language of the user's query.

The IBM Models are a sequence of models with increasing complexity, starting with lexical translation probabilities, adding models for reordering and word duplication.
In IBM models, a sentence aligned bilingual corpora is used. However, there is no alignment of words. 

## 1. IBM Model 1
In IBM Model 1, the only consideration is lexical translations of words which means that we are trying to find word translation probabilities. By using an expectation-maximization algorithm for solving the two-sided problem, which if we know alignment of words, we can investigate word translation probabilities and if we know word translation probabilities, we can investigate alignment probabilities.

## 2. IBM Model 2
Because IBM Model 1 does not consider the alignment of the words and takes all alignment probabilities equally, a new model was introduced by IBM which is IBM Model 2. In IBM Model 2, in addition to the lexical translation model, alignment probabilities were introduced for probability calculation. The result of IBM Model 2 outputs alignment probabilities and word translation probabilities.

#### Want to know more?
Please read the [problem statement](https://github.com/Vitthal98/Cross-Lingual-Document-Translator), [design report](https://github.com/Vitthal98/Cross-Lingual-Document-Translator/blob/main/Design_Document.pdf) and [results document](https://github.com/Vitthal98/Cross-Lingual-Document-Translator/blob/main/Result%20Document.pdf) as they contain detailed information about the datasets used, methods implemented, results obtained and discussion.

For any doubts don't hesitate to contact me at vitthalbhandari98@gmail.com

If you find our work helpful, do not forget to :star: the repository!
