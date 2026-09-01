# EduAble – AI Assistant for Visually Impaired

EduAble is a voice-based AI assistant that helps visually impaired students access study materials more easily. It reads materials aloud, answers questions, and gives motivational feedback, with support for multiple languages.

## Features

- **Text-to-Speech**: Reads uploaded study materials aloud
- **Voice Q&A**: Answers student queries in natural language
- **Motivational Feedback**: Gives sentiment-aware, encouraging responses
- **Multilingual Support**: Interacts with users in multiple languages
- **Adaptive Learning**: Adjusts response style based on how the user interacts with it

## Tech Stack

- **Language**: Python
- **Interface**: Streamlit
- **AI/NLP**: OpenAI GPT, Hugging Face Transformers
- **Speech**: SpeechRecognition, gTTS (text-to-speech), Pydub, Soundfile
- **Document Handling**: PyPDF2

## How to Run

1. Clone the repository
```bash
   git clone https://github.com/JAISHREE-BABU/EduAble.git
   cd EduAble-AI-Assistant
```

2. Install dependencies
```bash
   pip install -r requirements.txt
```

3. Run the app
```bash
   streamlit run app.py
```

## Status

This project was built as part of academic coursework and was published as a paper at ICDSAAI 2026 (IEEE Xplore).
