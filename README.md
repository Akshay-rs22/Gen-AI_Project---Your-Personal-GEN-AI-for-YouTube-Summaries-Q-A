[youtube_pro.pdf](https://github.com/user-attachments/files/23847830/youtube_pro.pdf)
# EchoTube 🎧🤖 — AI YouTube Summaries & Q&A (LangChain + TinyLlama)

EchoTube is a **local AI-powered** tool that:
- Extracts YouTube audio → converts to transcript
- Creates embeddings & vector search using **FAISS**
- Uses **TinyLlama** LLM for smart question-answering
- Lets users **chat with any YouTube video** in real-time

This project runs **offline** — no paid APIs required!  
All models are loaded locally and run on your machine.

---

## 🚀 Features

- 🔗 Accepts any YouTube video URL
- ✍️ Auto-generates accurate transcripts
- 📚 Builds vector database for contextual search
- 🧠 Answers user questions using retrieved transcript chunks
- 🧩 Supports TinyLlama & multiple embedding models
- 🔄 Fully interactive Q&A loop in terminal

---

## 📌 Architecture / Workflow

> From code reference: Model loading, chunking, RAG pipeline, user query interaction :contentReference[oaicite:1]{index=1}


---

## 🛠️ Tech Stack

- **Python**
- **LangChain**
- **FAISS**
- **YouTubeTranscript API**
- **sentence-transformers** for embeddings
- **TinyLlama** (Local LLM via HuggingFace Pipeline)

---


---

## 📦 Installation & Setup

1️⃣ Clone the repo
```bash
git clone https://github.com/Akshay-rs22/Gen-AI_Project---Your-Personal-GEN-AI-for-YouTube-Summaries-Q-A.git
cd youtube-ai-rag

2. User runs a script to auto-install dependencies
python model_and_package_download.ipynb



