# AI-WebScrapper: RAG-Powered Article Summarizer
"Don't have time to read the whole article? Let AI do the hard work for you!"

# Project Overview
In my exploration of AI and Large Language Models, I created an intelligent web scraper powered by RAG (Retrieval-Augmented Generation) using LangChain and Ollama.
This tool helps you automatically extract, summarize, and query information from any article or web page, so you don’t have to read it all manually.

The goal is simple: Save your precious time and get straight to the point.

# Features
-> URL Input: Fetches the content of a given article/webpage.

->RAG Pipeline: Combines document retrieval and LLM-powered generation for smart summarization and Q&A.

-> Ask Questions: Interact with the article content using natural language.

-> Runs Locally: No need for cloud APIs; works with Ollama on your own machine.

-> Fast & Lightweight: Optimized for performance using LangChain components and local LLM models.

-> Modular Design: Easily adaptable to other document types or sources (e.g., PDFs, blogs, etc.).

# Tech Stack
Ollama – Run open-source LLMs locally like llama 3.2        

LangChain – Framework for building LLM-powered applications

selenium - Scrape content from web pages

Streamlit – For creating a user-friendly UI


# Installation
Clone the repository
git clone https://github.com/GonnaBeCoder/AI-Webscrapper.git

cd AI-Webscrapper

# Run this command to install required dependencies 
-> pip install -r requirements.txt

# Install and run Ollama
->Download from https://ollama.com/

->Download the desired model:(run in command prompt)

  ollama run llama3.2

# Start the Streamlit UI (Run in Terminal)
-> streamlit run app.py

# How It Works
1.User Inputs a URL

2.Webpage content is scraped

3.Text is chunked and converted to embeddings

4.Relevant chunks are retrieved using vector similarity

5.User asks questions or gets summaries via the LLM (RAG)

# Credits:-
Inspired by open-source RAG projects

Lecture by :- Narman codes

Built with ❤️ using Python, Ollama, and LangChain

# Connect with Me:-

If you found this project helpful or have ideas for improvement, feel free to connect:

LinkedIn :- https://www.linkedin.com/in/badrinath-reddy-98785a279/
