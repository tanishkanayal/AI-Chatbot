# AI Chatbot

## Overview

The NDMC AI Chatbot is an intelligent citizen service assistant developed for the New Delhi Municipal Council (NDMC). The chatbot helps citizens access information related to municipal services such as property tax, water supply, electricity services, complaints, certificates, and NDMC 311.

The system uses Natural Language Processing (NLP), semantic search, and Retrieval-Augmented Generation (RAG) techniques to provide relevant responses to user queries.

---

## Features

* AI-Powered Citizen Assistance
* Natural Language Query Processing
* Semantic Search-Based Information Retrieval
* Property Tax Information Support
* Water and Electricity Service Assistance
* Complaint Registration Guidance
* NDMC 311 Information Support
* Birth and Death Certificate Information
* Interactive Web Interface using Gradio
* Fast and User-Friendly Experience

---

## Technology Stack

* Python
* Sentence Transformers
* Transformers
* TinyLlama
* Gradio
* Pandas
* Natural Language Processing (NLP)
* Retrieval-Augmented Generation (RAG)

---

## Project Architecture

User Query
↓
Sentence Transformer Embeddings
↓
Semantic Similarity Search
↓
NDMC Knowledge Base
↓
Relevant Information Retrieval
↓
Response Generation
↓
Gradio Interface

---

## Working Principle

1. The user enters a query through the chatbot interface.
2. The query is converted into vector embeddings.
3. Semantic similarity search identifies the most relevant NDMC information.
4. The chatbot retrieves the relevant content from the knowledge base.
5. The response is displayed through the Gradio web interface.

---

## Example Queries

* How can I pay my property tax?
* What is NDMC 311?
* How can I register a complaint?
* How can I book a water tanker?
* How can I get a birth certificate?
* What services does NDMC provide?
