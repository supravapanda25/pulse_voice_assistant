# PULSE - Voice Assistant

Pulse is a simple voice assistant built using Python. It can perform various tasks such as opening websites, playing songs, getting the current time and date, sending emails etc.

## Features

- **Voice Recognition:** Pulse uses the SpeechRecognition library to recognize voice commands.
- **Text-to-Speech:** Pyttsx3 is employed for converting text responses to speech.
- **Task Execution:** The assistant can perform tasks based on user commands, such as opening websites etc.
- **Email Functionality:** Pulse can send emails with a specified recipient, subject, and body.
- **Weather Information:** Get real-time weather updates for a specific city using the OpenWeatherMap API.

## **Configure the assistant:**
1. Set your Gmail credentials in the send_email function.
2. Replace 'your_openweathermap_api_key' with your OpenWeatherMap API key.

## Usage
1. **Greetings: Pulse greets you based on the time of the day.**
2. **Commands: Speak commands such as:**
          - Hello
          - Open YouTube
          - Play a song
          - Get the time
          - Send an email
          - Check the weather

3. **Exit: Say "Exit" or "Bye" to end the interaction.**

## Prerequisites
Ensure you have the required Python libraries installed. To install them, type the following commands in terminal:
pip install pyttsx3
pip install SpeechRecognition
pip install datetime
pip install pyowm
pip install webbrowser
