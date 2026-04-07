# 📚 StudyMate – AI Study Assistant

StudyMate is an AI-powered web application that helps students learn smarter by extracting knowledge from PDF documents and generating intelligent responses, flashcards, and quizzes.

## 🚀 Features
- 📄 Upload and process PDF study materials
- 🔍 Ask questions based on document content
- 🤖 AI-generated answers using multiple models (Gemini, GPT, BART)
- 🧠 Automatic flashcard generation
- 🧩 Quiz generation with multiple-choice questions
- 🎥 YouTube video recommendations
- 🔊 Text-to-Speech support
- 🌙 Dark mode UI

## 🛠️ Tech Stack
- Python
- Streamlit
- FAISS (Vector Search)
- Sentence Transformers
- Hugging Face Transformers
- Google Gemini API
- YouTube Data API

## ⚙️ How It Works
1. Upload PDF files
2. Text is extracted and converted into embeddings
3. FAISS is used for semantic search
4. AI models generate answers based on relevant content

## ▶️ Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
