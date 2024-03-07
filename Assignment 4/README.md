# GROUP ASSIGNMENT 4 - ADVANCED AI APPLICATIONS

This repository contains code for an advanced AI application focused on generating craft beer recommendations and providing information about craft beers using various AI techniques.

## Necessary Imports and Installations

Before running the code, ensure you have installed the required packages using the following command:

```python
!pip -q install langchain huggingface_hub google-search-results tiktoken chromadb lark langchain-together sentence_transformers gradio sentence_transformers -qqq
```

## Loading the Data

The dataset consists of AI-generated descriptions of craft beers with attached metadata including name, year, rating, style, ABV (Alcohol by Volume), IBU (International Bitterness Units), country, and price per bottle.

## Storing the Embeddings in Chroma

The embeddings for the craft beer descriptions are created using the HuggingFace sentence-transformers model and stored in Chroma for efficient retrieval.

## Creating Self-Querying Retriever

A self-querying retriever is initialized using the Together.ai API to retrieve relevant craft beer documents based on user queries. Metadata schema is defined to support querying based on beer attributes.

## Exploring Different Prompt Engineering Techniques

Three different prompt engineering techniques are explored for generating responses to user queries:
1. **N-shot Prompting Template**: Utilizes examples of beer recommendations to generate responses.
2. **CoT (Chain-of-Thought) Prompting Template**: Guides the AI to think step by step to answer the question based on context.
3. **Generated Knowledge Prompting Template**: Generates insights about craft beers and uses them to answer user queries.

## Gradio Deployment

A Gradio interface is provided for users to interact with the AI application. Users can input their questions and select the prompting technique they prefer to receive craft beer recommendations or information about craft beers.

To run the application, launch the Gradio interface using the provided code.
