# ZeroX Voice Agent to the Cloud

## 🧠 What We Built

  * **Public Deployment**: We have successfully deployed the agent to Render.com, a cloud platform with a generous free tier. This makes our agent accessible via a public URL.
  * **Live Agent**: Our voice agent is now live and can be accessed and used by anyone, anywhere.

-----

## 🚀 Run the App

Our voice agent is now live\! You can access and interact with it here:

**[https://zero-gklu.onrender.com](https://zero-gklu.onrender.com)**

Simply visit the link, click the settings icon to enter your API keys, grant microphone permissions, and start chatting\!

-----

## 🛠 Tech Stack

The tech stack remains the same, but we are now leveraging a cloud platform to host our application.

  * **Backend**: `FastAPI`, `uvicorn`, `requests`, `assemblyai`, `google-generativeai`, `python-dotenv`, `websockets`, `google-search-results`
  * **Frontend**: `HTML`, `Bootstrap`, `JavaScript` (with `AudioContext` and `WebSocket API`)
  * **Deployment**: `Render.com`
  * **AI APIs**:
      * Murf AI (Streaming Text-to-Speech)
      * AssemblyAI (Real-Time Speech-to-Text with Turn Detection)
      * Google Gemini (Streaming LLM with Function Calling)
      * SerpAPI (Real-time Google Search Results)


## 📂 Project Structure

The project structure is optimized for deployment.

```
AI Voice Agent/
├── main.py      # Handles WebSocket connections and API key logic
├── services/
│   ├── llm.py   # Handles interactions with the Gemini LLM
│   ├── stt.py   # Manages real-time speech-to-text
│   └── tts.py   # Manages text-to-speech conversion
├── schemas.py
├── templates/
│   └── index.html # Main UI for the voice agent
├── static/
│   ├── script.js  # Frontend logic for recording and settings
│   └── style.css  # UI styles
├── requirements.txt # Lists all project dependencies for deployment
└── .env           # Stores API keys for local development
```

-----
