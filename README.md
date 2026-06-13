# AI-ML-project
AI-powered Financial Assistant using RAG, LangChain, ChromaDB, HuggingFace Embeddings, and Ollama for intelligent document-based financial guidance.
# 💰 Financial Assistant RAG Chatbot

An AI-powered Financial Assistant built using LangChain, Hugging Face Embeddings, ChromaDB, and Ollama. This project leverages Retrieval-Augmented Generation (RAG) to provide intelligent, context-aware responses to financial queries using information extracted from financial documents.

## 🚀 Features

- 📄 PDF document ingestion and processing
- ✂️ Intelligent text chunking using RecursiveCharacterTextSplitter
- 🧠 Semantic embeddings with Hugging Face models
- 🗄️ Vector database storage using ChromaDB
- 🔍 Retrieval-Augmented Generation (RAG)
- 🤖 Local LLM integration through Ollama
- 💵 Financial guidance and education
- 📈 Investment and savings recommendations
- 📊 Budget planning assistance
- 💳 Debt management insights
- ⚡ Fast semantic search and retrieval

---

## 🏗️ Project Architecture

```text
PDF Documents
       │
       ▼
Document Loader
       │
       ▼
Text Splitter
       │
       ▼
Embedding Model
       │
       ▼
Chroma Vector Database
       │
       ▼
Retriever
       │
       ▼
LLM (Ollama)
       │
       ▼
Financial Assistant Responses
```

---

## 🛠️ Technologies Used

- Python
- LangChain
- ChromaDB
- Hugging Face Embeddings
- Ollama
- RecursiveCharacterTextSplitter
- PyPDFLoader

---

## 📂 Project Workflow

### Step 1: Load Financial Documents

The system loads PDF documents containing financial information.

### Step 2: Split Documents

Documents are divided into smaller chunks for efficient retrieval.

### Step 3: Generate Embeddings

Text chunks are converted into vector embeddings using a Hugging Face embedding model.

### Step 4: Store in ChromaDB

Embeddings are stored in ChromaDB for semantic search.

### Step 5: Retrieve Relevant Context

When a user asks a question, the system retrieves the most relevant document chunks.

### Step 6: Generate Response

The retrieved context is provided to the LLM to generate accurate and context-aware answers.

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/financial-assistant-rag.git
cd financial-assistant-rag
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Start Ollama

Make sure Ollama is installed and running:

```bash
ollama serve
```

Pull the required model:

```bash
ollama pull llama3
```

---

## ▶️ Usage

Run the notebook or Python script:

```bash
jupyter notebook
```

or

```bash
python app.py
```

Ask financial questions such as:

- How can I create a monthly budget?
- What are the benefits of emergency savings?
- Explain compound interest.
- What are common debt repayment strategies?
- How should I start investing as a beginner?

---

## 📁 Project Structure

```text
financial-assistant-rag/
│
├── Financial_Document.pdf
├── chroma_langchain_db/
├── notebook.ipynb
├── requirements.txt
├── README.md
└── app.py
```

---

## 🎯 Use Cases

- Personal Finance Education
- Budget Planning
- Investment Learning
- Debt Management Guidance
- Financial Literacy Assistance
- Document-Based Financial Question Answering

---

## 🔮 Future Enhancements

- Web Interface using Streamlit
- Voice-Based Financial Assistant
- Multi-document Support
- Real-Time Financial News Integration
- Personalized Financial Recommendations
- Chat History and Memory

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgements

- LangChain
- Hugging Face
- ChromaDB
- Ollama
- Open Source AI Community
