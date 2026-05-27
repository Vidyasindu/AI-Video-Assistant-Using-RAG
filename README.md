### 🎥 AI Video Assistant With RAG

An AI-powered Video & Meeting Assistant built using Streamlit, LangChain, Whisper, and Retrieval-Augmented Generation (RAG).  
This application can process audio/video files, generate transcripts, summarize meetings, extract action items, and answer user questions intelligently using LLMs.

---

## 🚀 Features

✅ Audio & Video Processing  
✅ Speech-to-Text Transcription using Whisper  
✅ AI-Powered Summarization  
✅ Action Item Extraction  
✅ Key Decision Extraction  
✅ Intelligent Question Answering with RAG  
✅ Vector Database Integration  
✅ Streamlit Interactive UI  
✅ Multi-file Processing Support  
✅ Downloadable Results  

---

### 🛠️ Tech Stack

## Frontend
- Streamlit

## Backend
- Python

## AI / LLM Tools
- LangChain
- Whisper
- Mistral AI / Groq API
- RAG Pipeline

## Vector Database
- ChromaDB / Vector Store

## Audio Processing
- FFmpeg
- pydub
- yt-dlp

---

### 📂 Project Structure

```bash
AI Video Assistant With RAG/
│
├── app.py
├── main.py
├── requirements.txt
├── .gitignore
├── .env
│
├── core/
│   ├── transcriber.py
│   ├── summarizer.py
│   ├── extractor.py
│   ├── rag_engine.py
│
├── utils/
│   ├── audio_processor.py
│
├── downloads/
├── vector_db/
└── __pycache__/
