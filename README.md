# 📄 HR Policy Assistant - RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot that enables users to
upload an HR Policy PDF and ask natural language questions.

## Features

-   Upload HR Policy PDF
-   Semantic Search using FAISS
-   Gemini 2.5 Flash
-   MMR Top-K Retrieval
-   Similarity Threshold
-   Source Pages
-   Chat Interface
-   Chat History

## Tech Stack

-   Python
-   Streamlit
-   LangChain
-   Gemini API
-   FAISS
-   PyPDF
-   python-dotenv

## Installation

``` bash
pip install -r requirements.txt
streamlit run app.py
```

Create a `.env` file:

``` text
GOOGLE_API_KEY=YOUR_API_KEY
```
