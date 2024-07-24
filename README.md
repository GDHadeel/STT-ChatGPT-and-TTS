# STT-ChatGPT-and-TTS

# Task 7: Speech-to-Text, ChatGPT, and Text-to-Speech Integration

## Description
This project integrates speech-to-text (STT), ChatGPT, and text-to-speech (TTS) functionalities into a single web application. It allows users to convert speech to text, interact with ChatGPT, and convert the response back to speech.


## Demo
https://github.com/user-attachments/assets/df8b230c-c881-4a1e-8ced-e0f13c54046a


## Code Overview

### HTML
- **Structure**: Defines the layout with a language selector, text area for user input, and buttons for recording, sending messages, and speaking text.

### CSS
- **Styles**: Provides a clean, user-friendly interface with responsive design and modern styling.

### JavaScript
- **Speech-to-Text**: Uses the Web Speech API to transcribe spoken words to text.
- **ChatGPT Integration**: Sends the transcribed text to the OpenAI API and displays the response.
- **Text-to-Speech**: Uses the Web Speech API to read out the response from ChatGPT.


## How to Use

1. **Open `index.html`** in a web browser.

2. **Select Language**: Choose between English and Arabic.

3. **Start Recording**: Click "Start Recording" to convert speech to text.

4. **Send Message**: Click "Send" to send the text to ChatGPT and display the response.

5. **Listen**: Click "Listen" to convert the response text back to speech.

## Setup

1. **Add Your API Key**: Replace `YOUR API` with your OpenAI API key.


## Acknowledgements

- Uses the Web Speech API for STT and TTS functionalities.
- Integrates with OpenAI's ChatGPT for generating responses.
