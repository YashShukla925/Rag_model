# Rag_model

# 📄 QnA with PDF 

This is a **Streamlit-based** application that allows users to upload PDF files and ask questions related to the document using **Google Gemini AI** and **FAISS** for vector search.

## 🚀 Features
- 📂 Upload multiple PDF files  
- 🔍 Extract text from PDFs  
- 🧩 Split text into chunks  
- 📖 Store embeddings using FAISS  
- 🤖 Answer questions based on PDF content using Gemini AI  

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/qna-with-pdf.git
cd qna-with-pdf
python -m venv venv
pip install -r requirements.txt
GOOGLE_API_KEY=your_google_api_key_here
```

## How it works
- Upload one or more PDF files.
- Click Submit & Process to extract and store embeddings.
- Type your question in the input box and get AI-generated answers based on the uploaded PDFs.

## Tech Stack
- Python
- Streamlit
- Google Gemini AI
- FAISS (Facebook AI Similarity Search)
- LangChain
- PyPDF2
