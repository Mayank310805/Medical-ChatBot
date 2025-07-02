# 🩺 MedicBot — Your Personal Voice-Enabled AI Doctor

MedicBot is a multimodal, voice-interactive AI healthcare assistant that enables users to speak their symptoms and upload medical images (like X-rays or reports). The system uses state-of-the-art generative models to understand and respond with a diagnosis, which is then converted into speech and optionally downloaded for reference.

---

## 🔍 Features

- 🎤 Voice-based symptom input using microphone
- 🖼️ Medical image upload (X-rays, skin rashes, etc.)
- 🤖 AI-powered diagnosis using a multimodal LLM (Meta-LLaMA via GROQ API)
- 📝 Real-time transcription using Whisper
- 🔊 Doctor's diagnosis converted to natural-sounding speech (gTTS)
- 💾 Option to download voice diagnosis as an audio file
- 🧪 Fully interactive Gradio-based UI

---

## 🛠️ Tech Stack and Libraries Used

| Component        | Tool/Library                         |
|------------------|--------------------------------------|
| Interface        | [Gradio](https://gradio.app/)        |
| Speech Input     | `speech_recognition`, `pyaudio`      |
| Transcription    | Whisper via [GROQ API](https://groq.com/) |
| Image Encoding   | `base64`, `PIL`, `io`                |
| AI Diagnosis     | Meta-LLaMA 4 model via GROQ          |
| Text-to-Speech   | [gTTS](https://pypi.org/project/gTTS/) |
| Audio Handling   | `pydub`, `subprocess`, `platform`    |
| Environment Vars | `dotenv` (optional)                  |

---

## 📁 Project Structure

