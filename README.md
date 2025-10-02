Autism Support Chatbot
A smart and accessible chatbot designed to support parents of autistic children. The system provides real-time conversational guidance through text and voice, with multilingual support for major Indian languages. Built using Python (Flask backend) and HTML/CSS/JS frontend, integrated with Gemini API for natural language understanding.

✨ Features
🤖 Real-time chatbot for autism-related parental support

🌐 Multilingual Support – English, Hindi, Tamil, Telugu, Malayalam, Kannada, Bengali

🎤 Voice Input – Speech-to-Text (STT) using Web Speech API

🔊 Voice Output – Text-to-Speech (TTS) with auto-speak option

💬 Context-aware conversations with session handling

🎨 Responsive and modern chat UI

🏗️ Project Architecture
Frontend → HTML, CSS, JavaScript (chat UI + speech integration)

Backend → Python Flask (handles requests, API calls, sessions)

LLM Integration → Google Gemini 1.5 Pro API

APIs Used → REST API for chatbot responses

📂 Project Structure
├── static/
│   └── style.css       # Frontend styling
├── templates/
│   └── index.html      # Chat UI
├── app.py              # Flask backend
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
⚡ Installation & Setup
Clone the repository

git clone https://github.com/your-username/autism-support-chatbot.git
cd autism-support-chatbot
Create virtual environment & install dependencies

python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
pip install -r requirements.txt
Set your Gemini API key (inside app.py or environment variable).

Run the Flask server

python app.py
Open in browser

http://127.0.0.1:5000
🎯 Usage
Type a message or use 🎤 voice input.

Select preferred language from the dropdown.

Enable/disable auto-speak replies.

Receive instant chatbot guidance.

🧩 Dependencies
Flask

Requests

SpeechRecognition (optional for backend speech support)

Google Gemini API

📌 Future Scope
Offline version with fine-tuned BERT model

Mobile app integration (Android/iOS)

Expanded dataset for Indian Sign Language (ISL)

📜 License
This project is licensed under the MIT License.
