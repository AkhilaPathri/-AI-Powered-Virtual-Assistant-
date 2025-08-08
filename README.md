# SmartAI Virtual Assistant

A professional, GenAI-powered virtual assistant app (ChatGPT-style clone) built with [Streamlit](https://streamlit.io/), OpenRouter API (using Mistral-7B Instruct model), and advanced voice features for both speech recognition and text-to-speech (TTS).  
Designed to run as a modern, interactive desktop or web assistant with customizable appearance, voice options, export tools, and productivity features.

---

## ✨ Features

- **Conversational AI**: Chat with an intelligent assistant using OpenRouter's Mistral-7B model.
- **Voice Input & Output**:
  - Speak to the assistant (speech recognition via microphone)
  - Listen to responses (text-to-speech with gender selection, Windows native voice)
- **Customizable UI**:
  - Multiple chat themes (Light, Dark, Cyberpunk, Ocean Blue, Emerald)
  - Show/hide timestamps, quick action buttons, personalized user name
- **Chat Tools**:
  - Export conversation as TXT or JSON
  - Copy responses easily
  - Show conversation statistics
  - Start new chats, refresh, and test voice output
- **Productivity Shortcuts**:
  - Quick ask for time, date, productivity tips, or random facts
- **Robust Session Handling**: Keeps chat context, supports conversation history and auto-speak mode

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/AkhilaPathri/-AI-Powered-Virtual-Assistant-.git
cd -AI-Powered-Virtual-Assistant-
```

### 2. Install dependencies

Requires Python 3.8+.

```bash
pip install -r requirements.txt
```

**Main dependencies:**
- streamlit
- requests
- pyttsx3
- SpeechRecognition
- pyperclip

(You may need to install [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/) separately for microphone support.)

### 3. Set up OpenRouter API Key

The project uses OpenRouter's API for AI chat.  
**Replace** the following line in `Chat Bot.py` with your own API key:

```python
OPENROUTER_API_KEY = "sk-or-..."  # <-- Insert your key here!
```

Sign up and get your API key at [https://openrouter.ai/](https://openrouter.ai/).

### 4. Run the app

```bash
streamlit run "Chat Bot.py"
```

The assistant will open in your web browser.

---

## 🖥️ Usage

- Type or speak your message in the input area.
- Use the sidebar to customize theme, voice, export tools, and chat controls.
- Click the microphone to speak, and listen to responses with the speaker button.
- Export conversations, copy responses, or view chat statistics as needed.

---

## 🗣️ Voice & Speech Notes

- Windows native speech is used for best voice quality (choose Male/Female).
- Voice features require Windows and PowerShell.
- Microphone input uses Google Speech Recognition (internet required).

---

## 📦 File Overview

- `Chat Bot.py` — Main Streamlit application
- `requirements.txt` — Python package requirements

---

## ⚡ Example Screenshot

![SmartAI Virtual Assistant Screenshot](screenshot.png) <!-- Add your own screenshot file if available -->

---

## 🛡️ Disclaimer

- This is a personal project and not affiliated with OpenAI, OpenRouter, or Microsoft.
- Never share or commit your OpenRouter API key publicly.

---

## ✍️ Author

Developed by Pathri Akhila

---

## 📄 License

MIT License (see [LICENSE](LICENSE) if present).

---

Enjoy your new SmartAI Virtual Assistant! 🤖
