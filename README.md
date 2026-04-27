<h1>JARVIS - Python Voice Assistant</h1>

<p>
  JARVIS is a simple Python-based voice assistant that can listen to user commands,
  recognize speech, respond using text-to-speech, open websites, tell the current time,
  and search information from Wikipedia.
</p>

<h2>🚀 Features</h2>

<ul>
  <li>Voice command recognition using microphone</li>
  <li>Text-to-speech response using <code>pyttsx3</code></li>
  <li>Greets user based on time of day</li>
  <li>Tells current system time</li>
  <li>Opens websites like Google and Facebook</li>
  <li>Searches Wikipedia and reads results aloud</li>
  <li>Maintains application logs</li>
</ul>

<h2>🛠️ Tech Stack</h2>

<ul>
  <li>Python</li>
  <li>SpeechRecognition</li>
  <li>pyttsx3</li>
  <li>Wikipedia API</li>
  <li>Webbrowser module</li>
  <li>Logging module</li>
</ul>

<h2>📁 Project Structure</h2>

<pre>
JARVIS-Voice-Assistant/
│
├── main.py
├── logs/
│   └── application.log
└── README.html
</pre>

<h2>📦 Installation</h2>

<p>Clone the repository:</p>

<pre>
git clone https://github.com/your-username/JARVIS-Voice-Assistant.git
cd JARVIS-Voice-Assistant
</pre>

<p>Install required dependencies:</p>

<pre>
pip install SpeechRecognition pyttsx3 wikipedia pyaudio
</pre>

<h2>▶️ How to Run</h2>

<pre>
python main.py
</pre>

<p>
  After running the file, JARVIS will greet you and start listening for your voice commands.
</p>

<h2>🎙️ Example Commands</h2>

<ul>
  <li><code>What is the time?</code></li>
  <li><code>What is your name?</code></li>
  <li><code>Open Google</code></li>
  <li><code>Open Facebook</code></li>
  <li><code>Wikipedia artificial intelligence</code></li>
  <li><code>Exit</code></li>
</ul>

<h2>🧠 How It Works</h2>

<p>
  The project uses the microphone to capture the user's voice. The captured audio is converted
  into text using Google's speech recognition service. Based on the recognized command,
  JARVIS performs specific actions such as opening websites, telling the time, or searching Wikipedia.
  The response is then spoken back to the user using text-to-speech.
</p>

<h2>📝 Logging</h2>

<p>
  The application automatically creates a <code>logs</code> folder and stores logs inside:
</p>

<pre>
logs/application.log
</pre>

<p>
  This helps in tracking errors and debugging the application.
</p>

<h2>⚠️ Requirements</h2>

<ul>
  <li>Working microphone</li>
  <li>Internet connection for speech recognition and Wikipedia search</li>
  <li>Python 3.x installed</li>
</ul>

<h2>🔮 Future Improvements</h2>

<ul>
  <li>Add OpenAI/Gemini integration for intelligent responses</li>
  <li>Add system commands like opening apps and files</li>
  <li>Add weather updates</li>
  <li>Add email automation</li>
  <li>Add WhatsApp or Telegram integration</li>
  <li>Create a GUI interface</li>
</ul>

<h2>👨‍💻 Author</h2>

<p>
  Developed by <strong>Rishav Patel</strong>
</p>

<h2>📌 Project Status</h2>

<p>
  This is a beginner-friendly Python voice assistant project built for learning automation,
  speech recognition, and text-to-speech concepts.
</p>
