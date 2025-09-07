# 📌 Project Overview

Filmception is an AI-powered system that processes movie summaries in three ways:

1. Multilingual Translation → Translate summaries into Urdu, Arabic, Korean.

2. Text-to-Speech (TTS) → Convert translations into natural-sounding speech.

3. Genre Prediction → Predict multiple genres using multi-label classification.

Built with an interactive Streamlit interface, the system allows users to:

- Enter a summary, translate it, and generate speech in their chosen language.

- Predict one or more genres of a movie using ML models.

# 🔧 Technologies Used

- Python, Streamlit (UI)

- NLP & ML: scikit-learn, Logistic Regression (One-vs-Rest), TF-IDF, Sentence-BERT (SBERT)

- Translation & TTS: Googletrans, gTTS, Pygame (audio playback)

- Data Preprocessing: NLTK (tokenization, stopwords, lemmatization)

# 🚀 How to Run

- streamlit run app.py
