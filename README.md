# EchoBot

EchoBot is a simple voice-activated assistant built with Python. It listens to user voice commands and performs actions like playing songs on YouTube, telling the current date and time, or fetching the weather of a specific city.

🧠 Features
🔊 Voice Recognition: Recognizes and responds to spoken commands using speech_recognition.

🎵 Play Songs: Say the song name followed by the keyword "play" and it will play it on YouTube using pywhatkit.

📅 Tell Date & Time: Ask "what is the current date" or "what is the time" and it will respond accordingly.

🌦️ Weather Info: Ask "what is the weather in [city]" to get the current weather using OpenWeatherMap API.

🗣️ Text-to-Speech Response: Responds using pyttsx3 for a more interactive experience.

🛠️ Tech Stack
Python 3

speech_recognition

pyttsx3

pywhatkit

datetime

requests (for weather)

Jupyter Notebook (demo.ipynb) for development

🚀 How It Works
Voice Input: The assistant listens to your voice via the microphone.

Command Recognition: Your speech is converted to text and parsed to detect the intent.

Action:

If command includes "play", it searches and plays the song on YouTube.

If it includes "current date" or "time", it fetches the date/time.

If it includes "weather in [city]", it fetches weather from OpenWeatherMap.

Voice Output: The result is spoken back to you.

Get a free API key from OpenWeatherMap and insert it into the code.
