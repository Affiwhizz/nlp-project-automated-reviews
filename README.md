# NLP Project 3 — Automated Customer Reviews (Electronics)

## What this project does
- **Classification:** Sentiment on a single review with RoBERTa (fine-tuned checkpoint).
- **Clustering:** Reviews grouped into 6 meta-categories (e.g., headphones_audio, photo_video, ...).
- **Summarization:** LLM (BART) generates short product summaries and category write-ups.
- **Deployed App:** Gradio web app with two tabs:
  1) **Single Review** → sentiment, category guess, short summary
  2) **Category Browser** → choose a category to see **Top-3 products** + **Worst product** with frequent complaints

## Quick start
```bash
pip install -r requirements.txt
python app.py
