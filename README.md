## What is a LLM?

A llm is a model  trained with a large amount of data. The model is based on neural networks (specifically transformers) et the principle is to adjust the model by predicting a token with respect to its context (the context is the words that are next this word). Therefore, a token is the basic unit
of an LLM is the token, and a token could be a word, a subword, a set of words. For instance, for the GPT models, the token size is approximately 4
words. To perform inference task, we need to learn weights which are numerical values that allow that define the model behavior.

## Generative AI

Generative AI is about generating new contents. This is generally done by submitting a query to a LLM which in turn generates a new content. This task is specifically performed with RAG.

## What is RAG?
RAG stands for retrieval augmented generation, and the main components of RAG are:
1. Indexing: the data is recovered an split into chunks with specified size.
2. Retrieval: the closest matches are recovered by a using a similarity measure.
3. Generation: the closest matches are combined with the initial query expand it, and this new query is fed into a LLM model that yields an output.

In practice, 
