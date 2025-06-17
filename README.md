# 💡 AZ Enhancer – AI Chat Assistant for Maang.in

**AZ Enhancer** is a Chrome extension that enriches your competitive coding experience on [Maang.in](https://maang.in) by embedding an intelligent, interactive chatbot directly into the problem-solving interface.

Powered by the **Google Gemini API**, this tool provides **real-time assistance**, **debugging support**, **context-aware hints**, and **voice input**, all in a seamless chat interface.

---

## 📌 Description

> "A Chrome extension to enhance the Maang.in experience by adding a chat bot."

Whether you're stuck on a logic bug or looking for step-by-step guidance, AZ Enhancer helps you think, debug, and learn better — without leaving the coding environment.

---

## 🚀 Features

### 🤖 AI Chat Assistance

- Context-aware responses based on **problem title**, **description**, **constraints**, and **user code**.
- Intelligent **prompt engineering** ensures meaningful help, not just answers.

### 🔍 Problem Context Extraction

- Uses **DOM parsing** and **XHR interception** to gather metadata and code directly from the page.
- Supports dynamic updates when navigating between problems.

### 🗨️ Custom Chat UI

- Clean, minimal interface with **Markdown support**.
- **Session persistence** using `chrome.storage` for chat history.
- **Export/Delete** conversation options.

### 🎙️ Voice Input

- **Hands-free communication** via **Web Speech API**.
- Speak your doubt and get instant help!

---

## 🛠️ Tech Stack

- **JavaScript (ES6)**, **HTML5**, **CSS3**
- **Chrome Extension API (Manifest v3)**
- **Google Gemini API** (Generative Language API)
- **DOM Manipulation**, **XHR Interception**
- **Web Speech API**
- **Local Storage** for session management

---

## 🧪 How to Use

1. **Clone or Download** this repo.
2. Go to `chrome://extensions/` in your browser.
3. Enable **Developer Mode**.
4. Click **"Load unpacked"** and select the project folder.
5. Enter your **Google Gemini API key** in the popup.
6. Navigate to a problem on [maang.in](https://maang.in) and click the 💬 button to start chatting.

---

## 📁 Project Structure

```
.
├── manifest.json
├── README.md
├── background.js
├── content.js
├── popup/
│   ├── popup.html
│   ├── popup.js
│   └── popup.css
├── styles/
│   └── style.css
└── icons/
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
```

---

## 🛡️ Disclaimer

This extension is built for **educational and personal use**. It does not collect any personal data and stores all chat history **locally**.

---

## 📬 Feedback / Contributions

Feel free to open issues or submit pull requests for improvements or bug fixes.  
Want to add new platforms? Let's collaborate!

---

> Made with 💻 by Apurba Kumar Show
