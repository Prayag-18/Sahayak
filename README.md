# Sahayak
AI Assistant which contains a Chatbot, Events tab, Summary tab, News tab and Search Web option

# 📌 Sahayak - Your AI Assistant

Sahayak is a Flask-based AI assistant that integrates real-time chatbot capabilities, personalized news, speech recognition, PDF summarization, and multilingual translation.

# 🚀 Features
🔹 Chatbot: AI-powered chatbot using Cohere API.
🔹 Speech Recognition: Convert speech to text using Google Speech Recognition.
🔹 News Fetching: Personalized news recommendations.
🔹 PDF Summarization: Extract and summarize text from PDFs.
🔹 Web Search: Fetch real-time information from the web.
🔹 Multilingual Support: Translate text between different languages.
🔹 Event Scheduling: Manage personal events and reminders.
🔹 User Authentication: Secure login, registration, and session management.

# 📂 Project Structure
📁 Sahayak
│── 📄 app.py              # Main Flask application
│── 📄 chatbot.py          # Chatbot logic using Cohere API
│── 📄 cohere_chat.py      # Cohere API integration
│── 📄 db.py               # MySQL Database operations
│── 📄 news.py             # News scraping & recommendations
│── 📄 pdf_reader.py       # PDF text extraction & summarization
│── 📄 searchweb.py        # Web search & content extraction
│── 📄 translatebot.py     # Language translation bot
│── 📄 requirements.txt    # Python dependencies
│── 📄 .env.example        # Example environment variables
│── 📄 README.md           # Project documentation

# 🛠️ Setup and Installation
<h2>1️⃣ Prerequisites</h2>
Ensure you have the following installed:
- Python 3.8+
- MySQL Server
- Virtual Environment (venv)
- FFmpeg (for audio processing)

<h2>2️⃣ Clone the Repository</h2>
To clone the repository and navigate to the project directory, run the following commands:

```bash
git clone https://github.com/yourusername/Sahayak.git
cd Sahayak
```

<h2>3️⃣ Create a Virtual Environment</h2>

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```
