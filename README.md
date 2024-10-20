# RAG_experiments
---

# 🛒 eCommerce Feedback Enhancement System

This project leverages **Retrieval-Augmented Generation (RAG)**, **clustering**, and **time-series analysis** to analyze customer feedback and generate actionable suggestions for enhancing an eCommerce website or mobile app.

## ✨ Key Features
- **Feedback Retrieval**: Uses FAISS to retrieve relevant customer feedback based on user queries.
- **Clustering**: Groups similar feedback into clusters using KMeans and SentenceTransformer embeddings.
- **Summarization**: Automatically summarizes common themes in each feedback cluster using a BART-based model.
- **LLM-Enhanced Suggestions**: Augments the suggestions from an LLM (e.g., GPT-Neo or LLaMA) with feedback summaries and time-series insights for targeted improvements.


## 🧠 Models Used
- **SentenceTransformer** (`paraphrase-MiniLM-L6-v2`): For generating feedback embeddings.
- **KMeans**: For clustering feedback.
- **FAISS**: For fast feedback retrieval.
- **Summarization** (`facebook/bart-large-cnn`): To summarize feedback clusters.
- **LLM Generation** (`meta-llama/Llama-3.2-1B-Instruct`): For generating enhancement suggestions.
