# gen-ai-project
# 🎌 Anime Movie Recommender System using LangChain & LLMs

This project recommends anime movies based on user input using Groq's LLaMA 3 model, LangChain, and ChromaDB. It processes anime data, performs semantic search, and generates recommendations using an LLM.

---

## 🚀 Tech Used
- LangChain
- Groq (LLaMA 3)
- HuggingFace Embeddings
- ChromaDB
- Gradio UI
- Pandas

---

## 📁 Files in This Repository
- `AnimeMovieRecommendSystem.ipynb` — Main notebook (safe version without API key)
- `anime_with_synopsis.csv` — Original anime dataset
- `anime_updated.csv` — Preprocessed dataset used for embeddings
- `README.md` — Project info

---

## ▶️ How to Run (in Google Colab)
1. Manually set your API key:
   ```python
   import os
   os.environ["GROQ_API_KEY"] = "your-api-key"
