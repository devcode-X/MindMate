# 🧠 MindMate — AI Mental Wellness Companion with Emotion-Aware Journaling

> Write or speak your thoughts → MindMate's NLP engine detects your emotional state and responds with personalized, supportive reflections powered by transformer-based sentiment analysis.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-FFD21E?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-412991?style=flat-square&logo=openai&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Backend-000000?style=flat-square&logo=flask&logoColor=white)

---

## 🎯 Overview

MindMate is an AI-powered mental wellness app that transforms personal journaling into an interactive emotional support experience. Using transformer-based emotion detection and LLM-generated reflections, it provides contextual, empathetic responses — not generic advice.

---

## ✨ Features

- 📝 **Smart Journaling** — write or speak your thoughts, MindMate listens
- 🔍 **Emotion Detection** — transformer model classifies emotional state (joy, sadness, anxiety, anger, etc.)
- 💬 **AI Reflections** — GPT/Gemini generates personalized, context-aware supportive responses
- 🚨 **Crisis Detection** — identifies high-distress signals and surfaces helpline resources
- 🌍 **Multi-language** — supports English, Hindi, Spanish
- 📱 **Responsive UI** — works on mobile and desktop

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Emotion Analysis | HuggingFace Transformers (DistilBERT / RoBERTa) |
| AI Responses | OpenAI GPT / Google Gemini |
| Backend | Python + Flask |
| Frontend | HTML/CSS/JS (Responsive) |
| Speech Input | Web Speech API |

---

## 🚀 Quick Start

```bash
git clone https://github.com/devcode-X/MindMate
cd MindMate
pip install -r requirements.txt

# Set API keys
export OPENAI_API_KEY=your_key
# or
export GEMINI_API_KEY=your_key

python app.py
# Open http://localhost:5000
```

---

## 📁 Structure

```
MindMate/
├── app.py                # Flask app
├── emotion/
│   └── detector.py       # Transformer-based emotion classifier
├── llm/
│   └── reflector.py      # GPT/Gemini reflection generator
├── templates/            # HTML UI
├── static/               # CSS, JS
└── requirements.txt
```

---

> ⚠️ **Disclaimer**: MindMate is not a substitute for professional mental health care. If you're in crisis, please contact a licensed professional or helpline.
