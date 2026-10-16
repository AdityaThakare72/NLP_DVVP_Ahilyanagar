# NLP Practicals — SPPU TE AI&DS

A hands-on workshop covering Natural Language Processing fundamentals: from linguistic analysis and text preprocessing to language models, sequence tagging, and modern deep learning approaches.

## What's Inside

**Group A: Text Foundation**
- **A1** — NLP pipeline & linguistic analysis (tokenization, POS tagging, dependency parsing basics)
- **A3** — Edit distance & spelling correction (Levenshtein distance, correction algorithms)
- **A4** — Preprocessing & OOV handling (cleaning, normalization, handling out-of-vocabulary words)
- **A5** — Feature extraction (TF-IDF, word embeddings, vectorization)

**Group B: Classical & Neural Methods**
- **B1** — Naive Bayes vs Logistic Regression (text classification comparison)
- **B2** — N-gram language models, smoothing & perplexity (MLE, Laplace, evaluation metrics)
- **B3** — POS tagging with HMM (sequence labeling, Viterbi algorithm)
- **B4** — Named Entity Recognition & evaluation (NER, precision/recall/F1)
- **B5** — Dependency parsing (syntactic structure, transition-based parsing)
- **B6** — Sentiment analysis pipeline (end-to-end sentiment classification)
- **B7** — BERT text classification (transformer-based classification, fine-tuning)

**Group C: Advanced & Generative**
- **C1** — Text summarization (BART / T5 for abstractive summarization)
- **C2** — LLM chatbot & prompt engineering (OpenAI SDK with Gemini or OpenRouter, RAG, Gradio interface)

## Key Features

- **Simple, one-step-per-cell notebooks** — each concept shown on one sentence first, then applied to data
- **No saved outputs for model-heavy cells** — B7, C1, C2 need to run in Colab (B7 & C1 require T4 GPU)
- **Study material decks** — theory and intuition in HTML slide decks (D1S1–D3S5)
- **Code only** — theory stays in the decks; notebooks focus on implementation

## What You Need

```
Python 3.8+
scikit-learn, nltk, pandas, seaborn, networkx
transformers, torch (for B7 & C1)
openai, gradio (for C2)
```

All dependencies are listed in `requirements.txt`.

## Running the Code

For **A1–B6, C1**: download, run locally or in Jupyter.

For **B7, C1, C2**: best run in Google Colab.
- B7 & C1 need a T4 GPU runtime (`Runtime > Change runtime type > T4 GPU`)
- C2 uses Colab secrets for API keys; set them up yourself in `Secrets` (⚙️ icon)
  - `GEMINI_API_KEY` for Gemini (get it from [Google AI Studio](https://aistudio.google.com/apikey))
  - `OPENROUTER_API_KEY` for OpenRouter (get it from [openrouter.ai/keys](https://openrouter.ai/keys))

## Related Study Material

Theory and deeper explanations live in the **D3S4** and **D3S5** decks:
- D3S4: Sequence-to-sequence models (BART, T5)
- D3S5: LLMs, prompt engineering, RAG


---

**Additional study material will be added soon in this repo.**

⭐ If you found this useful, please star the repo.

👤 Follow on GitHub: [AdityaThakare72](https://github.com/AdityaThakare72)