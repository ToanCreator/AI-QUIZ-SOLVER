# AI Quiz Solver

> An automated, AI-powered userscript designed to instantly solve quizzes, extract questions, and highlight accurate answers directly on your screen.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/c7b4f55f-36c6-4566-ad9d-2405d1cb8df4" alt="AI Quiz Solver Demo" width="340" />
</p>

---

## ✨ Features

- **⚡ Instant Solving:** Click **SOLVE** to automatically scan questions and highlight correct answers on the page.
- **🔑 Model & API Key Management:** Support for custom Gemini models and automatic multi-key rotation.
- **📊 Quiz History Table:** View all extracted questions and answers in an interactive pop-up window.
- **🛠️ Multiple Modes:** Search via Google (**SEARCH GG**), monitor active quiz elements (**MONITOR**), or switch AI models on the fly.

---

## ⚡ Quick Installation

### Step 1: Install Tampermonkey
First, install the **Tampermonkey** browser extension:
- [Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
- [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
- [Tampermonkey for Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikflimdfogobddfiocoggipbdnbkoip)

### Step 2: Add the Loader Script
1. Click on the **Tampermonkey extension icon** in your browser toolbar.
2. Select **Create a new script...**
3. Replace the default template with the following code:

```javascript
// ==UserScript==
// @name         AI Quiz Solver
// @namespace    http://tampermonkey.net/
// @version      10.0
// @description  Automated AI Quiz Solver by ToànCreator
// @match        *://*/*
// @grant        GM_setValue
// @grant        GM_getValue
// @run-at       document-start
// @require      https://raw.githubusercontent.com/ToanCreator/AI-QUIZ-SOLVER/main/AI-QUIZ-SOLVER.user.js?v=10.0
// ==/UserScript==
```

4. Click File > Save or Press `Ctrl + S` (or `Cmd + S` on Mac) to save the script.

---

## 📖 User Guide & Interface Walkthrough

### 1. Main Controls Overlay
When active, the floating control panel appears on the right side of your screen:

<p align="center">
  <img src="https://github.com/user-attachments/assets/d5fc01dc-3cf5-444b-85f5-efdd092448a0" alt="Main Controls Overlay" width="340" />
</p>

- **`SOLVE`**: Triggers AI analysis to solve current questions.
- **`MODEL`**: Opens model and API key configuration modal.
- **`MONITOR` / `SEARCH GG`**: Toggles live question tracking and external search tools.

---

### 2. Configure Model & API Keys
Click the **`MODEL`** button to open configuration settings:

<p align="center">
  <img src="https://github.com/user-attachments/assets/d042c65d-10a2-4a2d-b3c7-e435f151b6a6" alt="Configure Model & Keys" width="340" />
</p>

1. Enter your target model name (e.g., `gemini-3.5-flash-lite`).
2. Add your API key(s) in the text box (**one key per line** for rotation).
3. Click **Save Configuration**.

---

### 3. Automatic Highlighting & Answer Table
Once processed, answers are presented in an easy-to-read pop-up window while correct choices are automatically highlighted green on the page:

<p align="center">
  <img src="https://github.com/user-attachments/assets/c7b4f55f-36c6-4566-ad9d-2405d1cb8df4" alt="Automatic Highlighting" width="340" />
</p>

---

### 4. Real-time Results Overview
View all question-and-answer pairs extracted during your quiz session directly within the table view:

<p align="center">
  <img src="https://github.com/user-attachments/assets/64739d6c-ce44-483c-a047-1c88e46f05c3" alt="Quiz Solver Output Table" width="340" />
</p>
