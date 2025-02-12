# 📌 Sahayak - AI-Powered Virtual Assistant
Sahayak is a Flask-based AI assistant that integrates real-time chatbot capabilities, personalized news, speech recognition, PDF summarization, and multilingual translation.

# 🚀 Features
```
🔹 Chatbot: AI-powered chatbot using Cohere API.
🔹 Speech Recognition: Convert speech to text using Google Speech Recognition.
🔹 News Fetching: Personalized news recommendations.
🔹 PDF Summarization: Extract and summarize text from PDFs.
🔹 Web Search: Fetch real-time information from the web.
🔹 Multilingual Support: Translate text between different languages.
🔹 Event Scheduling: Manage personal events and reminders.
🔹 User Authentication: Secure login, registration, and session management.
```

# 📂 Project Structure
```
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
```

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
git clone https://github.com/Prayag-18/Sahayak.git
cd Sahayak
```

<h2>3️⃣ Create a Virtual Environment</h2>

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```
<h2>4️⃣ Install Dependencies</h2>

```bash
pip install -r requirements.txt
```

<h2>5️⃣ Set Up Environment Variables</h2>

Rename .env.example to .env and add your secret keys:
```ini
SECRET_KEY=your_flask_secret_key
COHERE_API_KEY=your_cohere_api_key
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_db_password
DB_NAME=UserDB
```

<h2>6️⃣ Initialize the Database</h2>

```bash
python db.py
```

<h2>7️⃣ Run the Flask App</h2>

```bash
python app.py
```

# 🛠️ Tech Stack

- **Backend**: Flask (Python)
- **Database**: MySQL
- **AI/ML**: Cohere API, Google Speech-to-Text, Google Translate
- **Web Scraping**: BeautifulSoup, Google Search API
- **Audio Processing**: FFmpeg, gTTS (Google Text-to-Speech)
