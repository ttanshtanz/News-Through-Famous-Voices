# 🎭 News Through Famous Voices

> **Real news. Legendary personalities. Powered by Agentic AI.**

An agentic AI app built with **Langflow + Gemini + DuckDuckGo** that fetches real-time news on any topic and rewrites it entirely in the voice of a famous personality — complete with **text-to-speech output** in persona-matched voices.

---

## ✨ Demo

| Topic | Persona | Output Style |
|---|---|---|
| Elon Musk latest news | Gordon Ramsay 👨‍🍳 | Angry, chaotic British rants |
| OpenAI GPT-5 release | Sherlock Holmes 🔍 | Deductive, Victorian reasoning |
| iPhone price increase | Angry Redditor 😤 | Fast, agitated American outrage |
| Developers at 3am | David Attenborough 🌿 | Calm, deep nature documentary |
| Twitter/X drama | Shakespeare 🎭 | Dramatic, formal Elizabethan |

---

## 🧠 How It Works

```
User Input (Topic + Persona)
        │
        ▼
┌─────────────────────────────────────┐
│           LANGFLOW AGENT            │
│                                     │
│  DuckDuckGo Search ──► Fetches      │
│  real news about topic              │
│                                     │
│  Gemini 2.5 Flash ──► Rewrites      │
│  news entirely in persona's voice   │
└─────────────────────────────────────┘
        │
        ▼
HTML Frontend ──► Displays + Speaks aloud
                  (persona-matched voice!)
```

---

## 🚀 Features

- 🔍 **Real-time news fetching** via DuckDuckGo Search
- 🎭 **8 built-in personas** + custom persona support
- 🔊 **Text-to-speech** with persona-matched voices
- 🌊 **Animated voice waveform** while speaking
- 📋 **Copy to clipboard** button
- 🎨 **Beautiful dark UI** — looks like a real product
- ⚡ **Powered by Gemini 2.5 Flash** for fast responses

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| [Langflow](https://langflow.org) | Agentic AI flow builder |
| Gemini 2.5 Flash | Language model |
| DuckDuckGo Search | Real-time news fetching |
| Web Speech API | Free browser text-to-speech |
| HTML/CSS/JS | Frontend interface |

---

## 📁 Project Structure

```
news-famous-voices/
├── flow.json                  ← Langflow flow (import this!)
├── news-famous-voices.html    ← Frontend app
├── .env.example               ← API key template
└── README.md
```

---

## ⚙️ Setup & Installation

### Prerequisites
- [Langflow Desktop](https://langflow.org) installed
- [Google Gemini API key](https://aistudio.google.com) (free)
- A modern browser (Chrome recommended)

---

### Step 1 — Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/news-famous-voices.git
cd news-famous-voices
```

### Step 2 — Import the Langflow flow

1. Open **Langflow Desktop**
2. Click **"Import Flow"**
3. Select `flow.json` from this repo
4. Your flow will load with all components connected

### Step 3 — Add your API keys

In the Langflow flow:
- **Agent component** → paste your **Gemini API key**
- *(Optional)* Go to **Settings → API Keys** → create a Langflow API key

In `news-famous-voices.html`, find this line and replace:
```javascript
'x-api-key': 'YOUR_LANGFLOW_API_KEY_HERE'
```

### Step 4 — Run it!

1. Make sure **Langflow Desktop is running**
2. Open `news-famous-voices.html` in your browser
3. Type a topic, pick a persona, hit **Deliver the News** 🎤

---

## 🎭 Available Personas

| Persona | Voice Used | Style |
|---|---|---|
| 👨‍🍳 Gordon Ramsay | Microsoft George (fast) | Aggressive British chef |
| 🔍 Sherlock Holmes | Google UK Male (slow) | Calm deductive reasoning |
| 🌿 David Attenborough | Microsoft George (deep) | Nature documentary narration |
| 🎭 Shakespeare | Google UK Male (dramatic) | Elizabethan formal drama |
| 😤 Angry Redditor | Google US (fast) | Agitated internet outrage |
| 🟢 Yoda | Microsoft Hazel (slow) | Wise, mysterious speech |
| 🏴‍☠️ Pirate Captain | Microsoft George (gruff) | Dramatic sea adventure |
| ✏️ Custom | Google US (default) | Any person you type! |

## 📁 Screenshots
<img width="998" height="604" alt="Screenshot 2026-05-02 171535" src="https://github.com/user-attachments/assets/5e648b28-648f-415a-b4c2-e80dd8dcc1b0" />
<img width="1600" height="1680" alt="screencapture-file-E-voice-agent-html-2026-05-02-17_27_57" src="https://github.com/user-attachments/assets/0941ac4f-0a36-438c-8d19-d714c4c666ba" />

---

## 🔑 Environment Variables

Create a `.env` file based on `.env.example`:

```env
LANGFLOW_API_KEY=your_langflow_api_key_here
GEMINI_API_KEY=your_gemini_api_key_here
```

> ⚠️ **Never commit your actual API keys to GitHub!**

---

## 🤝 Contributing

Pull requests are welcome! Some ideas for improvements:
- Add more personas
- Integrate ElevenLabs for even more realistic voices
- Add voice speed/pitch controls
- Save and share generated outputs
- Add more news sources

---

## 📜 License

MIT License — feel free to use, modify, and share!

---

## 🙏 Acknowledgements

- [Langflow](https://langflow.org) for the incredible agentic AI builder
- [Google Gemini](https://ai.google.dev) for the language model
- [DuckDuckGo](https://duckduckgo.com) for privacy-friendly search

---

<div align="center">

**Built with ❤️ using Langflow Agentic AI**

⭐ Star this repo if you found it useful!

</div>
