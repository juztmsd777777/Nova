# Nova AI Assistant 🤖

A simple **Jarvis-like AI Assistant** built using **Python** and **ElevenLabs Conversational AI**.  
The assistant can greet the user, understand spoken input, generate AI-powered responses, and reply using realistic text-to-speech.

This project was built as a learning exercise to understand **conversational AI**, **voice interfaces**, and **API integration**.

---

## ✨ Features

- 🎙️ Voice-based interaction  
- 🧠 AI-powered conversational responses  
- 🔊 Text-to-Speech using ElevenLabs  
- 👤 Personalized greeting using user name  
- 📅 Context-aware responses using user schedule  

---

## 🛠️ Tech Stack

- **Python**
- **ElevenLabs Conversational AI SDK**
- **python-dotenv**

---

## 📁 Project Structure

├── main.py
├── .env
├── README.md



---

## ⚙️ Environment Setup

Create a `.env` file in the project root and add the following:

API_KEY=your_elevenlabs_api_key
AGENT_ID=your_agent_id


⚠️ **Important:** Do not push the `.env` file to GitHub.

---

## ▶️ How to Run

Install dependencies:

``bash
pip install python-dotenv elevenlabs

Run the application:

python main.py

Ensure your microphone and audio output are properly configured.

🧠 How It Works

Loads API credentials securely using environment variables

Configures an ElevenLabs conversational AI agent

Sets a custom system prompt and greeting message

Listens to user speech and converts it to text

Generates AI responses and converts them back to speech

Displays both user input and AI responses in real time

🎯 Learning Outcomes

Working with third-party AI APIs

Secure handling of API keys

Understanding conversational AI workflows

Building a voice-enabled AI assistant

🚀 Future Improvements

Add task-based commands (open apps, reminders, search)

Improve prompt customization

Add text-only interaction mode

Better error handling and logging

---

## 👤 Author

Mohammed Eliyas

If you found this project interesting, feel free to ⭐ the repository and connect with me on LinkedIn.
