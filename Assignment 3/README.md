# RAG System with Langchain

## Introduction
This repository contains code for building a Retrieval-Augmented Generation (RAG) system using Langchain. The system is designed to extract information from a synthetic dataset of diffrent wine varieties and generate responses based on the retrieved information. The implementation leverages Langchain's capabilities for integrating retrieval-augmented generation techniques, utilizing a database for storing document vectors, and designing customized prompts for effective use of GPT models.

## Objective
The main objective of this project is to demonstrate the capabilities of RAG techniques in information extraction and synthesis. The system can be used for various tasks such as question answering, summarization of research papers, content recommendation, and more.

## Components
The key components of the system include:

1. Database Integration:
   - Utilizes Chroma for setting up a database to store and retrieve vectors representing document information.

2. Customized Prompts:
   - Designs and implements prompts using PromptTemplate to effectively utilize GPT models for generation based on retrieved data.

3. RAG Implementation:
   - Integrates retrieval-augmented generation using Langchain, combining retrieval with generation for answering queries or generating responses.

4. Data:
   - Utilizes a synthetic dataset of diffrent wine varieties and descriptions for demonstration purposes, ensuring suitability for showcasing the capabilities of the RAG system.

## Usage
To use the system:
1. Clone the repository.
2. Install the necessary dependencies specified in the notebook.
3. Run the notebook to set up the system and test its functionalities.
4. Experiment with different prompts, queries, and document sets to explore the capabilities of the RAG system.

## Example Queries
Here are some example queries you can try with the system:
- "What can you tell me about Cabernet Sauvignon?"
- "Tell me about the most popular wine varieties in France, using 2-3 sentences."

## Acknowledgements
This project utilizes several open-source libraries and tools, including Langchain, Hugging Face Transformers, and PyPDF2.
