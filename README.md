# LangChain - Building applications that Reason

LangChain is a framework that allows developers build applications powered by large langauge models (LLMs)

## Introduction

In this project, I explore the integration of LangChain with OpenAI and Anthropic models to perform various natural language processing tasks. The project is divided into three main notebooks, each focusing on different aspects of the integration and usage of these models.

## Notebooks Overview

### 1. LangChain LLM with OpenAI

In this notebook, I demonstrate how to set up and use the OpenAI language model with LangChain. I start by importing necessary libraries and loading environment variables. After retrieving the OpenAI API key, I initialize the OpenAI model using LangChain's `ChatOpenAI` class. I then configure the model and prompt it with messages to perform tasks such as translation.

### 2. Prompt Templates with LangChain OpenAI

This notebook focuses on creating and using prompt templates with the OpenAI model. I begin by importing libraries and loading environment variables. After initializing the OpenAI model, I create prompt templates using LangChain's `ChatPromptTemplate` class. These templates allow for dynamic and reusable prompts, which I use to interact with the model. Additionally, I explore using the Anthropic model for similar tasks.

### 3. Embeddings and Vector Similarity

In this notebook, I explore how to generate embeddings using the OpenAI model and calculate vector similarities. I start by importing necessary libraries and loading environment variables. After retrieving the API key, I initialize the OpenAI client and define a function to get embeddings for given texts. I then generate embeddings for a set of documents and calculate cosine similarity and distance between these embeddings to measure their similarity.

#### Understanding Vector Embeddings

Vector embeddings are numerical representations of text that capture the semantic meaning of words, phrases, or documents. These embeddings are essential in LLM applications because they enable the model to understand and process text in a way that is both efficient and effective. 

By converting text into vectors, we can perform various operations such as similarity calculations, clustering, and classification. This allows for more advanced NLP tasks like semantic search, recommendation systems, and context-aware responses.

## Conclusion

This project demonstrates the powerful capabilities of integrating LangChain with OpenAI and Anthropic models. By following the steps outlined in the notebooks, you can perform various NLP tasks, from generating text to calculating vector similarities. The use of environment variables ensures that sensitive information, such as API keys, is securely managed.

Feel free to explore the notebooks and adapt the code to your specific use cases. Happy coding!
