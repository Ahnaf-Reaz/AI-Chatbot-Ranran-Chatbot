**Ran Ran ChatBot
**Original Author:** Martin Tejada  
**Gradio UI & Groq Integration:** Ahnaf  
**Version:** 2.1  
**Since:** 3/12/2025  

> Forked from the original [Ran Ran ChatBot](https://github.com/mart-codes-good/AI-Chatbot---Ranran-Chatbot) by Martin Tejada

---

## Description
Ran Ran ChatBot is an AI chatbot with a graphical interface. Version 2.1 builds on Version 2.0 by introducing a modern web-based UI alternative using Gradio, along with a switch to the Groq API for faster and free AI responses (Using OpenAI Libraries).

<img width="648" height="477" alt="rrbv2 image 1" src="https://github.com/user-attachments/assets/3af8f3bb-456e-4519-8a29-5f00f919ae94" />
<img width="714" height="533" alt="rrbv2 image2" src="https://github.com/user-attachments/assets/37a2f5eb-6caa-4f4d-848b-8cec0fc0e225" />

---

## What's New in Version 2.1
- Added Gradio web UI as an alternative to the PyQt6 desktop app
- Added pywebview launcher to run the web UI as a native desktop window
- Switched AI backend from OpenAI to Groq API (llama-3.3-70b-versatile)
- Updated API client to modern OpenAI 1.0+ syntax
- First-launch API key setup screen for new users
- Animated RanRan avatar in chat bubbles and at the bottom of the UI
- Suggested message buttons that hide after first use

---

## What's in Version 2.0
- Added basic multi turn memory
- Removed "Bye" button
- Greeting messages on program launch
- Added initial suggested messages in the interface
- Full chat history is now shown
- Added microphone (MIC) button for speech-to-text
- Audio plays on program open, close, and when sending messages
- Ran Ran now uses context from previous messages
- Memory is automatically cleared after 100 messages

---

## Technologies Used

### Original App
- OpenAI API – for AI responses
- PyQt6 – for the graphical interface
- gTTS and pygame – for text-to-speech and sound
- SpeechRecognition – for microphone input

### Gradio UI (v2.1)
- Groq API – for faster, free AI responses
- Gradio – for the web-based UI
- pywebview – for the native desktop window
- pygame – for audio playback
- Web Speech API – for microphone input in the browser

---

