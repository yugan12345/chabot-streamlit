# 🤖 Chatbot with RAG, FAISS, and Web Scraping

[![🔗 Live Demo](https://chabot-app-bsrraf2efxzxgimpsngbmd.streamlit.app/)

Welcome to the official repository of our **Retrieval-Augmented Generation (RAG)**-based chatbot! This chatbot is designed to provide intelligent, context-aware responses using a hybrid approach of vector-based retrieval and large language models.

---

## 🚀 Features

- 🔍 **Retrieval-Augmented Generation (RAG)** for accurate, contextually aware answers  
- 🧠 **FAISS** for fast and efficient vector similarity search  
- 🌐 **Web Scraping with Selenium** to build the knowledge base dynamically  
- 📁 Automatically builds dataset from live web pages  
- 💬 Interactive interface for real-time Q&A

---

## 📸 Demo Preview

Click the button above to explore the working demo of the chatbot and see it in action!  
> ⚡ Ask questions from a domain-specific dataset that was scraped, processed, and indexed using FAISS.

---

## 🛠️ Tech Stack

| Tool/Library     | Purpose                                      |
|------------------|----------------------------------------------|
| **RAG**          | Core framework for combining search & LLMs   |
| **FAISS**        | Efficient similarity search over embeddings  |
| **Selenium**     | Web scraping to gather training documents    |
| **BeautifulSoup**| HTML parsing and data cleaning               |
| **OpenAI / LLM** | For generating responses based on context    |
| **Streamlit/Gradio** | Frontend interface for chatbot (if any) |

---

## 🧱 How It Works

1. **Data Collection:**  
   Using **Selenium** to scrape relevant pages from the web.

2. **Text Cleaning & Processing:**  
   Extract raw text using BeautifulSoup, then chunk and embed it.

3. **Indexing with FAISS:**  
   Text chunks are converted into embeddings and stored in a FAISS index.

4. **RAG Pipeline:**  
   On each query, relevant documents are retrieved and passed to the language model for generating answers.

---

## 📦 Installation

```bash
git clone https://github.com/your-username/chatbot-rag-faiss.git
cd chatbot-rag-faiss
pip install -r requirements.txt
