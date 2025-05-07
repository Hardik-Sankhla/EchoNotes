# EchoNotes - AI Meeting Notes Generator


EchoNotes is an intelligent voice-to-summary tool for meetings and memos.

## ✨ Features
- 🎙 Upload any voice memo (.mp3 or .wav)
- 📝 Instant summary and transcript
- ✅ Action items identified
- 📥 Download transcript

## 🚀 Tech Stack
- **Whisper** (transcription)
- **LLaMA2 via Ollama** (LLM summarization)
- **FastAPI** backend
- **Streamlit** frontend

## 📦 How to Run
```bash
git clone https://github.com/yourusername/echonotes.git
cd echonotes
bash setup.sh
```
1. Pull LLaMA2 locally:
```bash
ollama pull llama2
```
2. Start backend:
```bash
uvicorn backend.main:app --reload
```
3. Start frontend:
```bash
streamlit run frontend/app.py
```

## 📤 Optional Docker Run
```bash
docker build -t echonotes .
docker run -p 8000:8000 echonotes
```

## 🧪 Sample Audio
Use the `samples/sample_audio.mp3` to test.

## 📫 Contributing
Pull requests welcome! Let's build together.

---

**Made with ❤️ by Hardik Sankhla**
