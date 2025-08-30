🎙️ Voice Assistant

An intelligent, voice-driven conversational AI built with FastAPI. Voice Assistant listens, understands, and talks back—making human-computer interaction feel natural and seamless.

---

🚀 What It Does

🎤 Speak to Interact – Talk to the assistant and get instant responses in a natural voice.

📝 Live Transcription – Your speech appears as text on the screen in real time.

🧠 Context-Aware Conversations – Keeps track of chat history for smooth, flowing dialogue.

🔄 Session Handling – Start fresh sessions or continue where you left off.

🎙️ Custom Voices – Pick from multiple voices to personalize responses.

🌦️ Smart Skills – Weather updates, news headlines, jokes, and more.

💻 Clean UI – Modern, responsive frontend with history tracking.

---

🛠️ Tech Stack

FastAPI – REST + WebSocket backend

Jinja2 – Frontend templating

AssemblyAI – Real-time speech-to-text

Google Gemini – Natural language generation

Murf.ai – Lifelike text-to-speech streaming

python-dotenv – Secure API key management

HTML, CSS, JS – Interactive frontend

---

🏗️ How It Works

User speaks → audio captured from the browser

Audio sent to backend via WebSocket

AssemblyAI → converts speech → text

Gemini → generates AI response with context

Murf.ai → transforms text → natural voice

Frontend → displays transcription + plays response

---

📂 Project Structure
voice-assistant/
│── main.py           # FastAPI backend entry
│── config.py         # Configuration & settings
│── schemas.py        # Data models & validation
│── api_keys.json     # API keys (example file)
│── requirements.txt  # Dependencies
│── services/         # Core services (STT, TTS, LLM)
│── static/           # JS, CSS, assets
│── templates/        # HTML templates
│── uploads/          # Audio uploads
│── voice_assistent.png # Project snapshot
└── README.md

---

⚡ Getting Started
1️⃣ Prerequisites

Python 3.8+

pip

API keys for:

AssemblyAI

Google Gemini

Murf.ai

---

2️⃣ Installation
# Clone repository
git clone https://github.com/dhiraj-ydv45/Voice-agent

cd Voice-agent

---

# Install dependencies
pip install -r requirements.txt

---
3️⃣ Configure API Keys

Create a .env file in the project root:

MURF_API_KEY="your_murf_api_key"

ASSEMBLYAI_API_KEY="your_assemblyai_api_key"

GEMINI_API_KEY="your_gemini_api_key"

NEWS_API_KEY="your_news_api_key"

---
4️⃣ Run the App
uvicorn main:app --reload
---

👉 Open http://127.0.0.1:8000
 in your browser.
 
