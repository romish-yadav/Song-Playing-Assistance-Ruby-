# 🎙️ Ruby - Python Voice Assistant

## 📋 Description

**Ruby** is a simple voice-activated assistant built using Python. It can perform tasks such as playing songs on YouTube, telling the current time, fetching short summaries from Wikipedia, telling jokes, and responding to basic voice commands. Ruby uses speech recognition and text-to-speech libraries to interact with the user in real-time.

---

## 🧠 Features

* 🎵 **Play Songs**: Say “Ruby play \[song name]” to play music on YouTube.
* 🕒 **Tell Time**: Ask “Ruby what’s the time?” to hear the current time.
* 🧠 **Wikipedia Info**: Say “Ruby who is \[person or topic]” to get a quick Wikipedia summary.
* 😂 **Tell Jokes**: Ask “Ruby tell me a joke” for a random joke.
* ❌ **Exit Command**: Say “Ruby stop” to terminate the assistant.

---

## 🚀 How to Run

### 1. Install Required Libraries

Ensure you have Python 3 installed. Then install the following dependencies:

```bash
pip install SpeechRecognition pyttsx3 pywhatkit pyjokes wikipedia pyaudio
```

> 🔧 **Note**: You may need to install PyAudio separately based on your OS.
> For Windows: `pip install pipwin` then `pipwin install pyaudio`

### 2. Save the Script

Save the code as `ruby_voice_assistant.py`.

### 3. Run the Script

```bash
python ruby_voice_assistant.py
```

Now, speak your commands after saying **“Ruby”** (e.g., "Ruby play Despacito").

---

## 🧑‍💻 How It Works

* Uses **SpeechRecognition** to capture and convert speech to text.
* Uses **pyttsx3** for text-to-speech output.
* Uses **pywhatkit** to play YouTube videos.
* Uses **wikipedia** to fetch brief summaries.
* Uses **pyjokes** to tell jokes.
* Continuously listens for commands in a `while True` loop.

---

## ❗ Commands You Can Use

* "Ruby play \[song name]"
* "Ruby what time is it"
* "Ruby who is \[person or topic]"
* "Ruby tell me a joke"
* "Ruby stop"

---

## 🛑 Known Issues

* Silent failure if no speech is recognized.
* No internet check for YouTube or Wikipedia requests.
* Background noise may affect recognition.

---

## 📄 License

This project is open-source and free to use for learning and development purposes.

---

## 🙋‍♂️ Author

Developed as a basic voice assistant project in Python. Contributions and improvements are welcome!
