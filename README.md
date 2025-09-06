Ruby: The Voice Assistant 🤖
Ruby is a simple voice-activated assistant written in Python. It can perform basic tasks such as playing YouTube videos, telling the current time, providing information from Wikipedia, and sharing a joke, all through voice commands.

Features ✨
Voice Control: Responds to voice commands after hearing the wake word "Ruby".

Play Music: Plays a specific song or video on YouTube.

Example: "Ruby, play Bohemian Rhapsody"

Get Time: Tells the current time.

Example: "Ruby, what's the time?"

Search Wikipedia: Provides a summary of a person or topic.

Example: "Ruby, who is Albert Einstein?"

Tell a Joke: Shares a random joke.

Example: "Ruby, tell me a joke."

Stop Command: Shuts down the assistant.

Example: "Ruby, stop."

Prerequisites 🔧
Before you run the code, you'll need to install the necessary Python libraries. Make sure you have pip installed.

Open your terminal or command prompt and run the following commands:

Bash

pip install SpeechRecognition
pip install PyAudio
pip install pyttsx3
pip install pywhatkit
pip install wikipedia
pip install pyjokes
PyAudio Note: Some users might encounter issues installing PyAudio. If you do, you may need to install it with a pre-built wheel from Christoph Gohlke's website or use a different method specific to your operating system.

How to Run the Code ▶️
Save the code: Save the provided Python code in a file named ruby.py.

Run from the terminal: Open your terminal or command prompt, navigate to the directory where you saved the file, and run the script:

Bash

python ruby.py
Start Speaking: The program will print "Start Speaking!!" in the terminal. Wait for this message, and then say your command starting with the wake word "Ruby". For example, "Ruby, tell me a joke."
