PDF chatbot using Open AI

Overview:
=========

This project demonstrates how to use LangChain to build a document retrieval system for the given doc. It utilizes a pre-trained language model (LLM) to answer questions about the document.

Getting started
===============

Installation:
=============

pypdf- A Python library for working with PDF files, offering functionalities such as reading, writing, and manipulating PDF documents.

langchain- Presumably a term for a blockchain-based language, possibly referring to a decentralized system for language-related transactions or interactions.

openai- An artificial intelligence research laboratory known for developing advanced natural language processing models like GPT (Generative Pre-trained Transformer).

chromadb- Likely a database management system or tool related to Google Chrome, possibly for storing browser-related data or configurations.

tiktoken- Potentially a token related to the TikTok platform, possibly used for incentivization, rewards, or transactions within the TikTok ecosystem.

langchainhub- Probably a central hub or platform for language-related blockchain projects, serving as a nexus for development, collaboration, or exchange within the language technology space.

Install requirements:
=====================

Pip install -r requirements.txt

Usage:
======

Make sure you have an OpenAI API key (https://openai.com/pricing).

Replace zzzzzzzzzzzzffffffffffffffzzzzzzzzzzz in the code with your own API key.

Run the script:

Run all cell with Shift+Enter

How it Works:

The script follows these steps:

- Load the Mobily 2022 Annual Report (English) PDF using the PyPDFLoader class.

- Split the document into smaller chunks using the RecursiveCharacterTextSplitter class.

- Create a vector store using Chroma to store document embeddings generated by the OpenAIEmbeddings class (which utilizes

your OpenAI API key).

- Define a retrieval model using the vector store to find relevant document sections based on a query.

- Load the RAG prompt from LangChain's hub.

- Configure a chat interface with ChatOpenAI using the gpt-4 model and your API key.

- Combine the retriever, RAG prompt, and LLM into a single chain using LangChain's pipeline functionality.

- Run the chain with a sample question like "tell me about Mobily".