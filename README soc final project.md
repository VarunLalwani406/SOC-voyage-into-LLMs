
# 🤖 PDF Chatbot using Retrieval-Augmented Generation (RAG)

This project implements a simple chatbot that can answer questions from any PDF (e.g., UG Rulebook) using RAG architecture.

## ✅ Features
- Uses `google/flan-t5-large` (no Hugging Face token needed)
- Parses PDF with `pdfplumber`
- Embeds chunks with `sentence-transformers`
- Stores embeddings in `FAISS`
- Simple UI via `Gradio`

## 📂 Folder Setup

Place your `ug_rulebook.pdf` or any other PDF inside the working directory or upload it manually.

## 🚀 How to Run

1. Install dependencies:
    ```bash
    pip install -U langchain langchain-community pdfplumber gradio transformers sentence-transformers faiss-cpu accelerate
    ```

2. Run the notebook: `pdf_chatbot_rag.ipynb`

3. Ask questions about your PDF! 🎉

## 📌 Example Questions (UG Rulebook)
- What is the grading policy?
- How is CPI calculated?
- What are the attendance rules?
- What is academic probation?

---

Developed as part of an academic assignment to build a chatbot over PDFs using RAG.
