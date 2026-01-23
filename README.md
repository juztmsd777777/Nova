A simple Jarvis-like AI assistant, built using Python and ElevenLabs Conversational AI. The assistant can greet the user, understand spoken input, respond with AI-generated answers, and speak back using text-to-speech.

This project focuses on learning how to integrate:

Environment variables for security

Conversational AI agents

Voice input/output in a terminal environment

Features

🎙️ Voice-based interaction

🧠 AI-powered conversational responses

🔊 Text-to-Speech using ElevenLabs

👤 Personalized greeting using user name

📅 Context-aware prompt (daily schedule awareness)

Tech Stack

Python

ElevenLabs Conversational AI SDK

dotenv (for environment variables)

Project Structure
.
├── main.py
├── .env
├── README.md
Environment Setup

Create a .env file in the project root and add:

API_KEY=your_elevenlabs_api_key
AGENT_ID=your_agent_id


How It Works

Loads API credentials securely from environment variables

Initializes an ElevenLabs Conversational AI agent

Sets a custom system prompt and first greeting

Starts a voice-based conversation session

Prints both user speech and agent responses in real time

How to Run
pip install python-dotenv elevenlabs
python main.py

Make sure your microphone and audio output are properly configured for voice interaction.

Example Use Case

Ask general questions

Get responses aware of your daily schedule

Experiment with voice-based AI agents

Learning Outcomes

Working with third-party AI APIs

Secure handling of API keys

Understanding conversational AI workflows

Building a voice-enabled assistant from scratch

Future Improvements

Add command-based tasks (open apps, web search, reminders)

Improve prompt customization

Add text-only fallback mode

Better error handling

Author

Eliyas

If you found this interesting, feel free to ⭐ the repo and connect with me on LinkedIn!
