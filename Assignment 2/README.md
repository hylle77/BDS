
# Group Assignment 2 README

## Introduction

This exercise is designed to deepen your understanding and skills in modern deep learning techniques. We have two main tasks for you. The first is focused on using SBERT for semantic search, and the second involves hands-on exercises with gradient descent and the attention mechanism.

### Objective

The primary aim of this assignment is to provide hands-on experience with deep learning techniques, fostering innovation and creativity in their application.

## Part 1: SBERT and Semantic Search

### Task Description

Your challenge is to devise an innovative application utilizing SBERT and semantic search. The scope is deliberately broad to stimulate inventive approaches. Here are some suggestions to inspire your project:

- Implement a GIF search engine or a YouTube search function employing images and CLIP.
- (Optional) Utilize SetFit for supervised tasks with SBERT models.
- Explore the creation of a search engine through a Gradio or Streamlit app.

This segment encourages exploring semantic search capabilities to enhance or create search functionalities that are intuitive and efficient.

## Part 2: Gradient Descent and Attention Mechanism Exercises

### Task Description

- **Gradient Descent Exercise:** Conduct the procedure of weight updates for two examples using Stochastic Gradient Descent (SGD). Document each phase, including the computation of inputs, predictions, loss evaluation, adjustments of weights, and updates.
  
- **Attention Mechanism Exercise:** Apply the attention mechanism to two different sentences. Opt for sentences containing polysmous words to effectively showcase the mechanism's utility.

These exercises aim to solidify your understanding of two fundamental components of deep learning: gradient descent and the attention mechanism.

### Getting Started

1. Ensure you have the necessary Python environment and packages installed.
2. Familiarize yourself with the Jupyter notebook interface if you haven't already.
3. Follow the instructions within each part of the assignment closely.

### Requirements

- Python 3.x
- Libraries: PyTorch, Transformers, SBERT, Gradio/Streamlit (for web app development), and any other libraries specified within the notebook.


### Data
The notebooks are using the following dataset:


@inproceedings{saravia-etal-2018-carer,
    title = "{CARER}: Contextualized Affect Representations for Emotion Recognition",
    author = "Saravia, Elvis  and
      Liu, Hsien-Chi Toby  and
      Huang, Yen-Hao  and
      Wu, Junlin  and
      Chen, Yi-Shin",
    booktitle = "Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing",
    month = oct # "-" # nov,
    year = "2018",
    address = "Brussels, Belgium",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D18-1404",
    doi = "10.18653/v1/D18-1404",
    pages = "3687--3697",
    abstract = "Emotions are expressed in nuanced ways, which varies by collective or individual experiences, knowledge, and beliefs. Therefore, to understand emotion, as conveyed through text, a robust mechanism capable of capturing and modeling different linguistic nuances and phenomena is needed. We propose a semi-supervised, graph-based algorithm to produce rich structural descriptors which serve as the building blocks for constructing contextualized affect representations from text. The pattern-based representations are further enriched with word embeddings and evaluated through several emotion recognition tasks. Our experimental results demonstrate that the proposed method outperforms state-of-the-art techniques on emotion recognition tasks.",
}

Aswell as the:

README for GIPHY dataset

Dataset originally created 05/07/2018
UPDATED 10/04/2018 (removed file name column)

This dataset includes one CSV file:

giphy.csv
The GIPHY dataset was generated from content harvested from GIPHY, and includes 14,787 total GIFs, of which 10,972 are unique. The data sets include some minimal metadata for these GIFs. The data set does not include the GIFs themselves, however it does provide links to where you can access their web archive copies within the Library's web archive.

Created by Chase Dooley, Digital Collections Specialist, DCM, Library of Congress.
