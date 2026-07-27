# RAG-PDF-Chatbot
# 📚 Personal PDF Chatbot using RAG & Gemini

An interactive Retrieval-Augmented Generation (RAG) application that enables users to query PDF document content with high accuracy using Google Gemini API, ChromaDB, and Gradio.

---

## 🌟 Key Features

- **PDF Parsing & Text Extraction:** Extracts and compiles text across multi-page PDF documents using `pypdf`.
- **Text Chunking with Overlap:** Splits long texts into structured chunks (500 chars with 50 char overlap) to preserve semantic context.
- **Vector Embeddings:** Generates high-dimensional text embeddings using Google's `gemini-embedding-001`.
- **Vector Storage & Search:** Stores embeddings in memory via `ChromaDB` for fast similarity retrieval.
- **Context-Bound LLM Generation:** Uses `gemini-2.5-flash` with strictly conditioned prompts to answer queries solely based on retrieved document chunks.
- **Interactive Web Interface:** Built with `Gradio` for easy deployment and real-time interaction.

---

## 🛠️ Tech Stack

- **Language:** Python 3.10+
- **LLM & Embeddings:** Google GenAI SDK (`gemini-2.5-flash`, `gemini-embedding-001`)
- **Vector Store:** ChromaDB
- **PDF Parser:** PyPDF (`PdfReader`)
- **Web UI:** Gradio
- **Environment:** Google Colab / Local Python

---

## 📁 Repository Structure

```text
.
├── RAG_PDF_Chatbot.ipynb    # Main Google Colab Notebook
└── README.md                # Project documentation
