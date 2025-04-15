```markdown
# OmniAgent 🎙️🌐🤖

**OmniAgent** is your intelligent voice-activated assistant powered by Python and ElevenLabs. Inspired by J.A.R.V.I.S, this assistant can search the web, generate content, create websites, speak in multiple languages, and interact using natural voice.

---

## 🚀 Features

- 🎤 **Voice Interface**: Interact via natural speech using ElevenLabs TTS/STT
- 🌎 **Multilingual**: Understand and speak in multiple languages
- 🔍 **Web Search Integration**: Ask anything, get real-time results
- 🧠 **AI-Powered Tools**: Code generators, file utilities, image creators
- 🌐 **Website Creator**: Build static sites with simple voice or text commands
- 🖼️ **Image Generation**: Text-to-image creation using local or API models

---

## 📁 Project Structure

```bash
OmniAgent/
├── agents/
│   ├── voice_agent.py
│   ├── translator.py
│   └── web_search.py
├── tools/
│   ├── file_writer.py
│   ├── site_builder.py
│   └── image_generator.py
├── config/
│   └── settings.py
├── main.py
├── requirements.txt
└── README.md
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/mcakyerima/OmniAgent.git
cd OmniAgent
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure ElevenLabs API
Add your ElevenLabs API key to `config/settings.py` or use environment variables:
```python
ELEVENLABS_API_KEY = "your-api-key"
```

---

## 🧠 How It Works

1. User speaks a command
2. Speech is transcribed using Whisper or ElevenLabs
3. NLP determines intent (search, create file, translate, etc.)
4. Response is processed and spoken back
5. Custom tools handle specific tasks (write files, generate images, etc.)

---

## 📌 Roadmap

- [x] Voice Assistant Setup
- [x] Web Search with LangChain/SerpAPI
- [x] File & Website Generation
- [x] Multilingual Support
- [x] Memory + Personalization
- [x] Integration with Home Automation (optional)
- [x] Chat UI for Raspberry Pi

---

## 💬 Supported Commands

- “Search for Python tutorials”
- “Create a website about solar energy”
- “Translate this to French”
- “Draw a cat flying in space”
- “Write a blog post about AI in education”

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## 📜 License

MIT License © 2025 Mohammed Kaka
```
