# CodeAlpha AI Internship Tasks

This repository contains AI/ML projects completed as part of the CodeAlpha AI Internship.

---

## Task 1: Language Translation Tool

A web-based translation tool that supports 40+ languages with text-to-speech and clipboard copy functionality.

### Tools & Libraries: 
- Python
- Google Cloud Translation API
- gTTS (Google Text-to-Speech)
- Gradio (UI)
- python-dotenv

### Features:
- Translate text between 40+ languages
- Text-to-speech playback of translated text
- Copy translation to clipboard
- Input validation and error handling

### How to Run:
1. Clone the repository
2. Install dependencies: 'pip install requests gradio gTTS python-dotenv'
3. Create a '.env' file and add: 'GOOGLE_TRANSLATE_API_KEY=**'your_key_here'**
4. Run the notebook: 'Language Translation Tool.ipynb'

---

## Task 2: Chatbot for FAQs

A university student helpdesk chatbot that matches user questions against a FAQ dataset using NLP techniques.

### Tools & Libraries:
- Python
- NLTK (tokenization, stopword removal, lemmatization)
- scikit-learn (TF-IDF vectorization, cosine similarity)
- Gradio (chat UI)

### Features:
- 30+ FAQ entries covering admissions, fees, courses, exams, and campus life
- Text preprocessing pipeline: tokenization, stopword removal, lemmatization
- TF-IDF vectorization with cosine similarity matching
- Fallback response for unmatched questions
- Interactive chat UI with Send button, Enter key support, and Clear Chat

### How to Run:
1. Clone the repository
2. Install dependencies: 'pip install nltk scikit-learn gradio'
3. Run the notebook: 'University Helpdesk Chatbot.ipynb'

---

## Task 3: Music Generation with AI

An LSTM-based deep learning model trained on classical MIDI data to generate new music sequences.

**Tools & Libraries:**
- Python
- music21 (MIDI parsing and generation)
- TensorFlow/Keras (LSTM model)
- NumPy

**Features:**
- Extracts note and chord sequences from MIDI files using music21
- Prepares sequences for LSTM training with integer encoding and normalization
- Two-layer LSTM model with dropout for sequence learning
- Generates 100-note sequences from a random seed
- Saves generated output as a playable MIDI file

**Notes:**
- Trained on 5 Chopin MIDI files, 10,265 training samples, vocabulary of 216 unique notes
- Trained for 10 epochs on CPU: output quality improves significantly with more epochs and GPU resources
- Loss reduced from 4.81 to 4.38 over 10 epochs

**How to Run:**
1. Clone the repository
2. Install dependencies: 'pip install music21 tensorflow numpy'
3. Add MIDI files to a 'midi_files/' folder in the same directory
4. Run the notebook: 'task3_music_generation.ipynb'

*Internship tasks completed!.*
