<div align="center">
  <img src="logo.svg" alt="ChatLens Logo" width="120" />
  <h1>ChatLens</h1>
  <p><b>AI transcript parser & clean conversation UI</b></p>
  <p>Parse and format raw Ollama terminal logs into a beautiful, modern chat interface instantly.</p>
</div>

## 🌟 Overview

**ChatLens** is a fully local, single-page application that takes raw, messy terminal output from AI models (like Ollama) and instantly converts it into a clean, readable, premium chat UI.

No backend, no dependencies, no tracking. Just drop your logs into the parser and let it work its magic.

## ✨ Features

- 🎨 **Premium UI/UX:** Built with Tailwind CSS and custom Uiverse components for a highly polished, interactive experience.
- ⚡ **Instant Parsing:** Extracts `>>> user message`, model thinking blocks, and final answers from raw terminal logs.
- 🔍 **Live Search:** Quickly filter and highlight through the entire conversation history instantly.
- 🧠 **Smart Thinking Blocks:** Auto-collapses the model's `<think>` or "Thinking..." reasoning blocks to keep the chat clean, with a toggle to expand them when needed.
- 📋 **One-Click Copy:** Copy individual responses or the entire formatted chat easily.
- 🛠 **Zero Setup:** 100% vanilla JavaScript. Just open the HTML file in any modern browser.

## 🚀 How to Use

1. **Open the App:** Simply double-click `ollama-chat-viewer.html` to open it in your web browser.
2. **Paste your Logs:** Copy the raw terminal output from an Ollama session and paste it into the left-hand text area.
3. **Format Chat:** Click the **Format Chat** button.
4. **Enjoy:** Your terminal logs will be transformed into a beautiful chat timeline!

*Alternatively, use the **Import TXT** button to upload a saved terminal log file directly.*

## 🛠️ Built With

- **HTML5 & Vanilla JavaScript** - No bulky frameworks
- **Tailwind CSS (via CDN)** - For rapid, beautiful styling
- **Marked.js (via CDN)** - For Markdown rendering
- **Uiverse.io** - Custom buttons and input field styling

## 📄 License

This project is free to use and modify for your personal AI workflow!
