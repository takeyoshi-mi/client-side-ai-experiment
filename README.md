# Real-time English-Japanese Speech Translation

A client-side real-time speech translation application using Chrome's built-in AI API (Gemini Nano).

## ✨ Features

- 🔒 **Complete Local Processing** - No data sent to external servers
- ⚡ **Real-time Translation** - Instant translation while speaking
- 🤖 **Chrome Built-in AI** - Uses Gemini Nano via Chrome Prompt API
- 📱 **Responsive Design** - Works on desktop and mobile
- 🎯 **Simple Setup** - One-click AI model download

## 🚀 Live Demo

[View Live Demo](https://your-railway-deployment-url.railway.app)

## 🛠️ Local Development

1. Clone the repository:
```bash
git clone https://github.com/takeyoshi-mi/client-side-ai-experiment.git
cd client-side-ai-experiment
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open http://localhost:3000 in Chrome/Edge

## 📋 Requirements

- Modern Chrome or Edge browser
- Microphone access permission
- Internet connection (for initial AI model download only)

## 🔧 How to Use

### First Time Setup (Once Only)
1. Click "AIモデルを準備する" button
2. Wait for AI model download (may take a few minutes)

### Regular Usage
1. Click "音声認識を開始" (Start Voice Recognition)
2. Speak in English
3. View real-time translation in Japanese

## 🚂 Deploy to Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/takeyoshi-mi/client-side-ai-experiment)

## 🏗️ Architecture

- **Frontend**: HTML5 + CSS3 + Vanilla JavaScript
- **Speech Recognition**: Web Speech API
- **AI Translation**: Chrome AI Prompt API (Gemini Nano)
- **Server**: Express.js (for deployment only)

## 📄 License

MIT License - feel free to use this project for learning and experimentation!