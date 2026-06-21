# 📚 Multi-PDF AI Chat Assistant

An AI-powered web application that allows users to upload one or multiple PDF documents and interact with them through natural language conversations. The application uses Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) to answer questions based only on the content of the uploaded PDFs.

## 🚀 Features

* Upload single or multiple PDF files
* Extract and process text from PDFs
* AI-powered question answering
* Context-aware responses from uploaded documents
* Conversational chat interface
* Fast document retrieval using vector embeddings
* Supports multiple PDFs simultaneously

## 🛠️ Tech Stack

* Python
* Streamlit
* LangChain
* FAISS Vector Database
* Groq / OpenAI LLM
* PyPDF2

## 📖 How It Works

1. Users upload one or more PDF files.
2. The application extracts text from the documents.
3. The text is split into manageable chunks.
4. Embeddings are generated and stored in a vector database.
5. When a user asks a question, relevant document chunks are retrieved.
6. The LLM generates an answer based on the retrieved content.

## 🎯 Example Use Cases

* Research paper analysis
* Study material assistance
* Notes and document querying
* Company document search
* Academic PDF exploration

## 💡 Project Evolution

### Initial Idea

Our original concept was an AI-powered learning platform designed to improve reading comprehension and knowledge retention.

The proposed workflow was:

1. User uploads a PDF document.
2. The AI generates a concise summary of the document.
3. Based on the summary length, the system estimates the required reading time.
4. A reading timer is provided to the user.
5. After the user finishes reading, the AI automatically generates questions from the summary.
6. The user answers those questions.
7. The system evaluates the answers and provides marks, feedback, and performance analysis.

The goal was to create an interactive learning environment where users could not only read content but also test and measure their understanding.

### Current Implementation

To build a strong foundation, we first implemented the document question-answering system. Users can now upload multiple PDFs and ask questions directly to the AI, receiving answers grounded in the uploaded documents.

Future versions may integrate the original learning and assessment features, including:

* AI-generated summaries
* Reading time estimation
* Quiz generation
* Automated grading
* Progress tracking
* Learning analytics dashboard

## 📷 Future Enhancements

* PDF summarization
* Reading-time estimation
* Quiz generation from documents
* Automatic answer evaluation
* User authentication
* Performance dashboard
* Export chat history
* OCR support for scanned PDFs

## ⚙️ Installation

```bash
git clone https://github.com/Aashutosh-Sah/pdfsummarizer.git
cd pdfsummarizer

pip install -r requirements.txt

streamlit run app.py
```

## 🤝 Contributors

Developed as an educational AI project exploring the capabilities of Large Language Models, Retrieval-Augmented Generation (RAG), and intelligent document interaction.

## 📄 License

This project is intended for educational and research purposes.
