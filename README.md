# 📄 RAG PDF Q&A with LangChain + Ollama (LLaMA 3)

This project demonstrates a **Retrieval-Augmented Generation (RAG)** pipeline using [LangChain](https://www.langchain.com/) and [Ollama](https://ollama.ai/) running the **LLaMA 3 model**. It allows you to parse a PDF, embed its contents, and ask questions interactively with the context of the document — guided by a customizable **base prompt**.

---

## 🚀 Features
- ✅ Load and parse PDF files into structured text chunks  
- ✅ Create embeddings with **FastEmbed** for efficient retrieval  
- ✅ Store and query embeddings using **Chroma vector database**  
- ✅ Use **LangChain Retrieval Chains** to combine retrieval with generation  
- ✅ Run **Ollama’s LLaMA 3 model** locally for fast and private inference  
- ✅ Provide a **base system prompt** to control responses  

---

## 🛠️ Tech Stack
- [Python 3.10+](https://www.python.org/)  
- [LangChain](https://github.com/langchain-ai/langchain)  
- [Ollama](https://ollama.ai) (LLaMA 3 model)  
- [ChromaDB](https://www.trychroma.com/)  
- [FastEmbed](https://github.com/qdrant/fastembed)  
- [PDFPlumber](https://github.com/jsvine/pdfplumber)  

---

## Requirements
- langchain
- langchain-community
- chromadb
- pdfplumber
- fastembed
- ollama
