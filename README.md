# STT-ChatGPT-and-TTS

# Task 7: Speech-to-Text, ChatGPT, and Text-to-Speech Integration

## Description
This project integrates speech-to-text (STT), ChatGPT, and text-to-speech (TTS) functionalities into a single web application. It allows users to convert speech to text, interact with ChatGPT, and convert the response back to speech.


## Demo
https://github.com/user-attachments/assets/df8b230c-c881-4a1e-8ced-e0f13c54046a


## Code Overview

### [`index.html`](https://github.com/GDHadeel/STT-ChatGPT-and-TTS/blob/main/index.html)
- **Structure**: Creates the interface with a language selector, a text input area, and buttons for recording speech, sending messages to ChatGPT, and speaking text.

### [`style.css`](https://github.com/GDHadeel/STT-ChatGPT-and-TTS/blob/main/style.css)
- **Styles**: Styles the interface for a responsive, user-friendly design.

### [`script.js`](https://github.com/GDHadeel/STT-ChatGPT-and-TTS/blob/main/script.js)
- **Speech-to-Text**: Converts speech to text using the Web Speech API.
- **ChatGPT Integration**: Sends text to OpenAI's API and displays the response.
- **Text-to-Speech**: Reads the ChatGPT response out loud using the Web Speech API.


## How to Use

1. **Open [`index.html`](https://github.com/GDHadeel/STT-ChatGPT-and-TTS/blob/main/index.html)** in a web browser.

2. **Select Language**: Choose between English and Arabic.

3. **Start Recording**: Click "Start Recording" to convert speech to text.

4. **Send Message**: Click "Send" to send the text to ChatGPT and display the response.

5. **Listen**: Click "Listen" to convert the response text back to speech.

## Setup

1. **Add Your API Key**: Replace `YOUR API` with your OpenAI API key.


## Acknowledgements

- Uses the Web Speech API for STT and TTS functionalities.
- Integrates with OpenAI's ChatGPT for generating responses.
