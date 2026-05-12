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

*More tasks will be added as the internship progresses.*
