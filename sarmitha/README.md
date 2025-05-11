# 🎙️ Real-Time SRT for Customer Support Automation

This project enables real-time transcription of customer support calls using speech-to-text (ASR) technology. It captures live audio, converts it into text and SRT subtitles, and allows for automated processing like intent recognition, sentiment analysis, and CRM ticketing.

---

## 📌 Overview

- Capture **live audio** from customer support calls.
- Transcribe audio to **real-time text and SRT subtitle format**.
- Use **NLP automation** to detect user intent and trigger actions.
- Display transcription in a **live agent UI (optional)**.
- Automate CRM updates and generate support tickets.

---

## 🧰 Technologies Used

| Layer               | Technology                              |
|---------------------|------------------------------------------|
| Audio Input         | Twilio, SIP.js, WebRTC                   |
| Real-Time ASR       | OpenAI Whisper, Google STT, AWS Transcribe |
| Backend Framework   | FastAPI / Flask (Python)                 |
| NLP Automation      | spaCy, OpenAI, HuggingFace Transformers  |
| UI (Optional)       | React.js, WebSockets                     |
| Subtitle Format     | `.srt` (SubRip Text)                     |

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-org/realtime-srt-support.git
cd realtime-srt-support
2. Set Up Python Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Sample requirements.txt
txt
Copy
Edit
whisper
faster-whisper
openai
flask
fastapi
uvicorn
websockets
python-dotenv
spacy
transformers