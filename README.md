# 🎬 Smart Movie Shazam (Semantic Search Engine)

An AI-powered audio retrieval system that identifies movies or TV shows simply by listening to a short audio clip. It transcribes audio speech to text and uses vector embeddings to perform semantic similarity matches against a subtitle database.

## 🚀 Features
- **Audio Transcription:** Leverages OpenAI's Whisper model for robust speech-to-text conversion.
- **Semantic Mapping:** Converts text into meaning-based vectors using `SentenceTransformers` (`all-MiniLM-L6-v2`).
- **Vector Storage:** Efficiently indexes and queries thousands of dialogue chunks via `ChromaDB`.
- **Modern UI:** Built-in interactive frontend using Streamlit (Incoming).

## 🛠️ Tech Stack
- **Language:** Python
- **AI Models:** OpenAI Whisper, Sentence Transformers
- **Database:** ChromaDB (Vector Database)
- **Frontend:** Streamlit

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   https://github.com/vivekanand85/movie-shazam-ai.git
   
