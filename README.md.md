
# 🧠 AI Article Summarizer Chrome Extension

A Chrome Extension that uses AI to summarize any article or webpage you're reading in one click. Perfect for students, researchers, and anyone short on time!

## 🚀 Features

- 📄 One-click article summarization
- 🤖 AI-generated TL;DRs using OpenAI API (or your own backend)
- 🌐 Works on any readable webpage or article
- 💾 Saves your summary history
- ⚙️ Simple and fast UI

<!-- ## 📸 Preview

![Summarizer Screenshot](./screenshots/extension-preview.png) -->

## 🛠️ Installation

### Option 1: Manual Installation

1. Clone or download this repo:

   ```bash
   git clone https://github.com/VsnviM/AI_summariser.git
   ```

2. Open Chrome and go to `chrome://extensions/`
3. Enable **Developer mode** (top right)
4. Click **Load unpacked**
5. Select the cloned `extension/` folder
6. Pin the extension and start summarizing!

### Option 2: [Download ZIP](https://github.com/your-username/ai-article-summarizer-extension/archive/refs/heads/main.zip)

## ⚙️ Usage

1. Visit any news article or blog
2. Click the extension icon 🧠
3. Wait a few seconds… and get a clean summary
4. Optionally copy or save the result

## 🔐 API Setup

- Sign up at [Google AI Studio](https://makersuite.google.com/)
- Create an API key from [Google CLoud Console](https://console.cloud.google.com/)
- Enable the Gemini API for your project
- Replace the placeholder in `config.js` or `background.js`:

```javascript
const GEMINI_API_KEY = "YOUR_GEMINI_API_KEY";
```

## 📂 Folder Structure

```
extension/
├── icons/
├── popup.html
├── popup.js
├── style.css
├── manifest.json
├── background.js
└── config.js
```

## 🧠 How It Works

The extension extracts article text using `DOMParser`, sends it to an AI summarizer backend or OpenAI API, and displays the summarized version in the popup.

## 📌 To-Do / Coming Soon

- ✅ Dark mode support
- ✅ Save summaries to local storage
- ⏳ Multi-language support
- ⏳ Chat-based Q&A from article

## 🧑‍💻 Built With

- JavaScript
- Chrome Extensions API
- Geimini API
- HTML/CSS

<!-- ## 📃 License

MIT License -->

---

> Created with 💙 for productivity lovers.
