# 📄 DocuChat-RAG: AI-Powered Document Question-Answering

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.27-orange)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🚀 Overview
**DocuChat-RAG** is a **Retrieval-Augmented Generation (RAG) system** that allows you to interact with your documents in a conversational manner. Simply upload documents (PDFs, text, etc.), and ask questions. The system retrieves relevant information and generates context-aware answers using AI.

This project is ideal for:
- Knowledge management
- Academic research
- Business document summarization
- Quick Q&A over large document sets

---

## ✨ Features
- **Multi-document support:** Upload multiple PDFs or text files at once.
- **RAG-based Q&A:** Combines retrieval with generation for accurate answers.
- **Smart document parsing:** Handles PDFs, text, and other document formats.
- **Interactive Streamlit UI:** Clean, user-friendly interface.
- **Embeddings & semantic search:** Retrieves contextually relevant content.
- **Extensible pipeline:** Easily integrate with custom LLMs or vector databases.

---

## 🛠️ Tech Stack
- **Frontend:** [Streamlit](https://streamlit.io/)
- **Backend:** Python 3.11
- **NLP & AI:** Hugging Face Transformers, LangChain
- **Vector Database:** FAISS / Chroma / Weaviate (configurable)
- **Document Processing:** PyPDF2, pdfminer, textract

---

## ⚡ Installation
Clone the repository:

```bash
git clone https://github.com/yourusername/docuchat-rag.git
cd docuchat-rag
```
## Create and activate virtual environment:

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
```
## Install dependencies:
``` bash
streamlit run app.py
```
- 1.Upload your documents (PDFs or text files).
- 2.Ask questions in the input box.
- 3.Receive AI-generated answers instantly.
- 4.Optionally, download or export responses.

## 📂 Project Structure
```bash
docuchat-rag/
│
├─ app.py              # Streamlit frontend
├─ requirements.txt    # Python dependencies
├─ docs/               # Sample documents
├─ embeddings/         # Precomputed embeddings (optional)
├─ utils/              # Preprocessing and helper functions
└─ README.md
```
## 🌟 Future Enhancements

- Add voice input for question asking.
- Support multilingual documents.
- Integrate real-time document updates.
- Add explainability features to show answer sources.

## 👩‍💻 Author
- Made with ❤️ by [Pooja Dave](https://www.linkedin.com/in/poojaddave)
- Connect on [LinkedIn](https://www.linkedin.com/in/poojaddave)


## 📄 License
- This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
- ⭐ Don’t forget to star this repo if you found it helpful!

