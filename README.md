# RAG-Document-Q-A-With-Groq-And-Lama3


An advanced **Retrieval-Augmented Generation (RAG)** system that enables accurate and context-aware question-answering from research papers. This project combines cutting-edge language models with efficient document processing and retrieval mechanisms.

---

## 🚀 Features  

- **Groq AI and Lama3 Integration:** Uses the Llama3-8b-8192 model for high-quality responses.  
- **Document Embedding:** Processes research papers with Hugging Face's `all-MiniLM-L6-v2` embeddings.  
- **Vector Database:** Implements FAISS for fast and scalable vector-based document retrieval.  
- **Interactive User Interface:** Streamlit-based interface for querying and exploring document similarity.  
- **Optimized Pipeline:** Combines structured prompts and retrieval chains for enhanced performance.  

---

## 🛠️ Technologies Used  

- **Programming Language:** Python  
- **Libraries:**  
  - `LangChain` for document splitting, retrieval chains, and embeddings.  
  - `Streamlit` for building the UI.  
  - `FAISS` for vector-based retrieval.  
  - `Hugging Face` for embeddings.  
  - `Groq` and `Llama3` for language model integration.  
- **Environment Management:** Python dotenv for API key management.  

---

## 📂 Project Structure  

```plaintext
├── research_papers/          # Directory containing input PDF documents.
├── app.py                    # Main Streamlit application file.
├── requirements.txt          # List of dependencies.
├── README.md                 # Project documentation.
├── .env                      # Environment variables file (API keys, tokens).
