# Medibot - AI Medical Chatbot using RAG
MediBot demonstrates the utility of combining vector-based retrieval with generative models for domain-specific QA. It shows strong potential as an educational and assistive tool for navigating complex medical texts.
The exponential growth of medical literature, research papers, and clinical documents presents a major challenge: how can healthcare professionals and researchers quickly retrieve accurate, contextually relevant information from unstructured medical data?
MediBot addresses this problem by enabling natural language interaction with medical documents. It is a Retrieval-Augmented Generation (RAG) based chatbot that allows users to ask medical questions and receive precise answers grounded in uploaded medical documents. Unlike traditional chatbots, MediBot does not rely on predefined intents or static responses—it dynamically retrieves relevant content using vector similarity and augments a powerful LLM to generate context-specific responses.



# README: Setting Up Your Environment with Pipenv

## Prerequisite: Install Pipenv
Follow the official Pipenv installation guide to set up Pipenv on your system:  
[Install Pipenv Documentation](https://pipenv.pypa.io/en/latest/installation.html)

---

## Steps to Set Up the Environment

### Install Required Packages
Run the following commands in your terminal (assuming Pipenv is already installed):

```bash
pipenv install langchain langchain_community faiss-cpu pypdf
pipenv install huggingface-hub==0.22.2
pipenv install streamlit



