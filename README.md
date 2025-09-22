# Semantic-Book-Recommender
An AI-powered book recommendation system that uses LLMs, embeddings, and emotion analysis to suggest the right book based on user mood or query. Built with LangChain, Transformers, ChromaDB, and Gradio.
---

## Features
- **Semantic search** using Hugging Face embeddings (`all-MiniLM-L6-v2`)
- **Emotion-aware filtering** (happy, sad, suspenseful, etc.)
- **Book dataset** enriched with emotions and metadata
- **Vector database** powered by Chroma for fast similarity search
- **Interactive UI** built with Gradio

---

## Tech Stack
- Python 3.10+
- Pandas, NumPy
- LangChain + Hugging Face Embeddings
- ChromaDB
- Gradio

---

## Project Structure
There are five components to this tutorial:
- Text data cleaning (code in the notebook data-exploration.ipynb)
- Semantic (vector) search and how to build a vector database (code in the notebook vector-search.ipynb). This allows users to find the most similar books to a natural        language query (e.g., "a book about a person seeking revenge").
- Doing text classification using zero-shot classification in LLMs (code in the notebook text-classification.ipynb). This allows us to classify the books as "fiction" or      "non-fiction", creating a facet that users can filter the books on.
- Doing sentiment analysis using LLMs and extracting the emotions from text (code in the notebook sentiment-analysis.ipynb). This will allow users to sort books by their      tone, such as how suspenseful, joyful or sad the books are.
- Creating a web application using Gradio for users to get book recommendations (code in the file gradio-dashboard.py).
  
---

## App Preview
[Semantic Book Recommender](<"C:\Users\bhati\OneDrive\Pictures\Screenshots\Screenshot (81).png">)

---

## Try It Online
You can try the Semantic Book Recommender app here: [Open the App](https://10e837b1a8511adee1.gradio.live)



