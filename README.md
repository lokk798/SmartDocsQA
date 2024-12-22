# SmartDocsQA: A Question-Answering System for Documents

SmartDocsQA is a question-answering system that allows users to ask questions based on content fetched from provided URLs. It uses OpenAI embeddings, FAISS for fast similarity search, and Langchain for efficient document processing. The system is built using Streamlit to provide an interactive user interface.

## Features

- Load documents from URLs.
- Automatically split documents into chunks for processing.
- Generate vector embeddings for document chunks using OpenAI's API.
- Store document embeddings in a FAISS index for fast retrieval.
- Answer user queries by finding relevant document chunks and generating responses using OpenAI models.
- Display the sources used to generate answers.

## Setup

Follow these steps to set up and run the project:

### 1. Clone the repository:

```bash
git clone https://github.com/lokk798/SmartDocsQA.git
```

### 2. Create a configuration file (config.ini)

[OPEN_AI]

api_key = your_openai_api_key_here

### 3. You can install all dependencies by running:

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit app:

```bash
streamlit run app.py
```
