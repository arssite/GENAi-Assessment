# Gen AI Engineer / Machine Learning Engineer Internship Assessment

## Introduction
Hello! I'm **Anmol Ratan Srivastava**, currently pursuing a Bachelor's in Computer Science Engineering with a specialization in Artificial Intelligence and Machine Learning. This repository contains my submission for the Gen AI Engineer / Machine Learning Engineer internship assessment, where I developed a **Retrieval-Augmented Generation (RAG) Model** and an **Interactive QA Bot Interface**.

## Project Overview
This project is divided into two parts:

### Part 1: RAG Model for QA Bot
The RAG model is designed to answer questions based on a provided dataset or document. It uses a **vector database** like Pinecone to store and retrieve document embeddings efficiently and a **generative model** (e.g., Cohere API) to generate accurate, context-aware answers.

### Part 2: Interactive QA Bot Interface
I built an interactive frontend using **Gradio**, allowing users to upload documents (e.g., PDFs) and ask questions in real-time. The interface processes the uploaded content using the RAG model, retrieving relevant document sections and generating real-time responses.

## Key Features
- **Document Upload & Real-Time QA**: Users can upload documents and ask questions based on the content.
- **Efficient Retrieval**: Uses a vector database for fast and accurate document embedding retrieval.
- **Generative Model**: Answers are generated contextually using a state-of-the-art generative model.
- **Scalable and Modular Code**: Designed for easy scalability and modularity.

## Links

- [Colab Notebook For Part 1](https://colab.research.google.com/drive/1yOgpty6XBrr1kka9sZATK6lYuaGfClqx?usp=sharing)
- [Colab Notebook For Part 2](https://colab.research.google.com/drive/19qdUK0NnVdqPc6X4US4eNBUpaTBUGePL?usp=sharing)  
- [Live Gradio Demo](https://a35335e31a4b6d4cda.gradio.live/)

## How to Run
1. **Colab**: Use the Colab notebook to explore the end-to-end RAG pipeline.
2. **Gradio**: Try the interactive QA bot by uploading documents and asking questions in real-time via the Gradio interface.

## Deployment
The project is containerized using **Docker**, making it easy to deploy locally or in the cloud. Detailed deployment instructions can be found in the repository.

