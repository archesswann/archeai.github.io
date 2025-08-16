# 🤖 Web ChatBot with AI Integration

A modern, responsive, and feature-rich web-based chatbot built with HTML, CSS, and JavaScript. This chatbot supports text input, voice input, file/image uploads, multi-language support, night mode, chat history, and integrates with AI via the OpenRouter API to generate intelligent responses.

![ChatBot Screenshot](screenshot.png) <!-- Tambahkan screenshot jika ada -->

## ✨ Features

- 💬 Real-time AI-powered chat responses
- 🔊 Voice input & voice-direct mode (speak and get spoken replies)
- 📎 Upload and analyze `.txt`, `.pdf`, and image files (OCR)
- 🌐 Multi-language support: English, Indonesian, Mandarin
- 🌙 Day/Night mode toggle
- 💾 Persistent chat history using `localStorage`
- 📱 Fully responsive design (mobile & desktop)
- 🎯 Typewriter effect for bot responses
- 📂 Organized UI with sidebar and quick-links panel
- 🚀 Lightweight and dependency-minimal (uses CDN for libraries)

## 🔧 Technologies Used

- **Frontend**: HTML5, CSS3 (with Flexbox & Grid), JavaScript (ES6+)
- **Libraries**:
  - [Marked.js](https://marked.js.org/) – Markdown rendering
  - [PDF.js](https://mozilla.github.io/pdf.js/) – PDF text extraction
  - [Tesseract.js](https://github.com/naptha/tesseract.js) – OCR for images
- **APIs**:
  - Web Speech API (SpeechRecognition & SpeechSynthesis)
  - OpenRouter AI API (using DeepSeek model)
- **Styling**:
  - Bootstrap 4 (CDN)
  - Font Awesome (icons)
  - Google Fonts (Inter)

## 🔑 API Key

This project uses **OpenRouter AI** to communicate with the DeepSeek model.

> 🔐 **Security Note**: The API key is currently hardcoded in the source for demo purposes. In production, use environment variables or a backend proxy to hide sensitive keys.

```js
