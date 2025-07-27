Here’s a professional and well-structured `README.md` for your **Conversational RAG Chatbot with PDF Upload** project:

---

# 🧠 Conversational RAG Chatbot with PDF Uploads

A powerful, interactive chatbot built using **Streamlit** and **LangChain** that allows you to upload PDFs, chat with their content, and maintain contextual chat history. It integrates **Groq LLMs**, **HuggingFace Embeddings**, and **ChromaDB** for a seamless conversational retrieval-augmented generation (RAG) experience.

---

## 🚀 Features

- ✅ Upload and parse multiple PDF documents
- 💬 Ask questions and get answers from PDF content
- 🧠 Maintains contextual chat history for coherent conversations
- 🔎 Reformulates follow-up questions using LangChain's History-Aware Retriever
- 🔐 Secure API key input
- 📄 Powered by Groq LLM (`Gemma2-9b-it`) and HuggingFace Embeddings
- 🗂️ Uses Chroma as the vector store

---

## 📸 Demo UI

> (You can add a screenshot or Loom video link here later)

---

## 🧱 Tech Stack

- [Streamlit](https://streamlit.io/)
- [LangChain](https://www.langchain.com/)
- [Groq API](https://console.groq.com/)
- [HuggingFace Embeddings](https://huggingface.co/)
- [ChromaDB](https://www.trychroma.com/)
- [Python-dotenv](https://pypi.org/project/python-dotenv/)

---

## 📁 Project Structure

```
├── app.py                 # Main Streamlit app
├── .env                   # Environment variables (HF_TOKEN)
├── requirements.txt       # Dependencies
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Add Environment Variables

Create a `.env` file:

```ini
HF_TOKEN=your_huggingface_token_here
```

---

## 🔑 Required API Keys

- **Groq API Key** → [https://console.groq.com/](https://console.groq.com/)
- **HuggingFace Token** → [https://huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 📝 How to Use

1. Enter your **Groq API key**
2. Upload one or more **PDF files**
3. Ask your questions in natural language
4. See results in real time with persistent **chat history**

---

## 📦 Example Requirements.txt

```txt
streamlit
langchain
langchain-community
langchain-core
langchain-groq
langchain-huggingface
langchain-chroma
python-dotenv
```

You may need to add: `chromadb`, `pypdf`, or `tiktoken` depending on your environment.

---

## 🧠 Future Improvements

- Add file deletion after session
- Cache vectorstore to avoid repeated embeddings
- Support for non-PDF file types (e.g., DOCX, TXT)
- UI polish with Streamlit Chat Components

---

## 💡 Inspiration

Built with LangChain’s conversational retrieval components and Groq’s blazing-fast inference for efficient RAG applications.

---

## 📜 License

MIT License

---

Let me know your GitHub repo name if you’d like me to generate a badge/header or commit it for you!
"# Rag-based-chatbot" 
