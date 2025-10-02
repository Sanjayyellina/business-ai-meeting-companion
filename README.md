## Business AI Meeting Companion
An AI-powered assistant that transcribes business meetings in real time, generates key summaries & action points, and provides a user-friendly Gradio interface. Built using OpenAI Whisper, IBM Watson AI, and LangChain, this project demonstrates how speech-to-text and summarization technologies can transform productivity in professional settings.
---

## Features
 Speech-to-Text (STT):
Converts meeting audio to accurate transcripts using OpenAI Whisper.
 Summarization & Key Points Extraction:
Powered by IBM Watson Machine Learning models to condense lengthy discussions into actionable insights.
 Interactive Web App:
A Gradio-based interface for uploading audio files, viewing transcripts, and downloading summaries.
  Business Use Case:
Designed for enterprises, teams, and classrooms to save time by eliminating manual note-taking.

---

## Tech Stack
Speech-to-Text: OpenAI Whisper
Summarization: IBM Watson Machine Learning
Orchestration: LangChain
Interface: Hugging Face Gradio
Backend: Python 3.10+
Audio Processing: ffmpeg

---


##  Project Structure
├── simple_llm.py              # Test script for Watson summarization
├── simple_speech2text.py      # Test script for Whisper transcription
├── speech2text_app.py         # Gradio application combining STT + Summarization
├── downloaded_audio.mp3       # Sample audio for testing
├── requirements.txt           # Project dependencies
└── README.md                  # Documentation

---

##Getting Started
1️⃣ Clone the repository
git clone https://github.com/Sanjayyellina/business-ai-meeting-companion.git
cd business-ai-meeting-companion
2️⃣ Create a virtual environment
pip install virtualenv
virtualenv my_env
source my_env/bin/activate
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run the app
python3 speech2text_app.py
This launches the Gradio interface at:
 http://0.0.0.0:7860
**  Example Workflow
Upload a meeting audio file (MP3/WAV).
The app transcribes the audio into accurate text.
IBM Watson summarizes the discussion and extracts key action points.
Download or copy the summary for use in reports, project trackers, or emails.

---

## Business Impact
 Saves Time: Automates meeting note-taking.
 Better Focus: Participants can engage in discussions instead of writing notes.
 Scalable: Works for remote teams, classrooms, and multinational corporations.
 Accessibility: Supports inclusivity by providing transcripts for hearing-impaired participants.

---

## Author
Abhinav Sanjay Yellina
 Master’s in Business Analytics & Computer Science
 Passionate about AI for Productivity, LLMs, and Enterprise Applications

---

## Showcase Value
This project demonstrates:
End-to-end AI application development (speech → text → summary).
Integration of OpenAI + IBM Watson + Gradio.
Strong alignment with business productivity use cases.

---
