<img width="1080" height="1985" alt="1000195213" src="https://github.com/user-attachments/assets/c7b4f55f-36c6-4566-ad9d-2405d1cb8df4" />

AI Quiz Solver
An automated AI-powered userscript designed to instantly solve quizzes, extract questions, and provide accurate answers directly on your screen.
Features

<img width="1080" height="1808" alt="1000195235" src="https://github.com/user-attachments/assets/d5fc01dc-3cf5-444b-85f5-efdd092448a0" />

 * Instant Solving: Click SOLVE to automatically scan questions and highlight correct answers.
   
<img width="1080" height="1871" alt="1000195236" src="https://github.com/user-attachments/assets/d042c65d-10a2-4a2d-b3c7-e435f151b6a6" />

 * Model & API Key Management: Support for multiple Gemini models and custom API key rotation.

<img width="1080" height="2137" alt="1000195239" src="https://github.com/user-attachments/assets/64739d6c-ce44-483c-a047-1c88e46f05c3" />

 * Quiz History Table: View all extracted questions and corresponding answers in a neat table.
   
<img width="1080" height="2400" alt="1000195238" src="https://github.com/user-attachments/assets/60ec7d88-5c06-48da-b53a-39eb589e776f" />

 * Multiple Solver Modes: Search via Google (SEARCH GG), monitor active quizzes (MONITOR), or switch AI models on the fly.

Quick Installation
Step 1: Install Tampermonkey
First, install the Tampermonkey extension for your browser:
 * Tampermonkey for Chrome
 * Tampermonkey for Firefox
 * Tampermonkey for Edge
Step 2: Add the Loader Script
 * Open your browser and click on the Tampermonkey icon \rightarrow select Create a new script.
 * Copy and paste the following loader code into the editor:
// ==UserScript==
// @name         AI Quiz Solver (Loader)
// @namespace    http://tampermonkey.net/
// @version      9.0
// @description  Automated AI Quiz Solver Loader
// @match        *://*/*
// @grant        GM_setValue
// @grant        GM_getValue
// @run-at       document-start
// @require      https://raw.githubusercontent.com/ToanCreator/AI-QUIZ-SOLVER/refs/heads/main/AI-QUIZ-SOLVER.user.js
// ==/UserScript==

 * Press Ctrl + S (or Cmd + S on Mac) to save the script.
User Guide & Interface Walkthrough
1. Main Controls Overlay
When active, the floating control panel appears on the right side of your screen:
 * SOLVE: Trigger AI analysis to solve current questions.
 * MODEL: Configure active AI model settings.
 * MONITOR / SEARCH GG: Advanced search and live question tracking mode.
2. Configure Model & API Keys
Click the MODEL button to open configuration settings:
 * Enter your preferred Gemini model (e.g., gemini-3.5-flash-lite).
 * Add your API key(s) in the text box (one key per line for rotation).
 * Click Save Configuration.
3. Automatic Highlighting & Answer Table
Once processed, answers are presented in an easy-to-read pop-up window while correct choices are automatically highlighted green on the page:
4. Real-time Results Overview
View all question-and-answer pairs extracted during your quiz session directly within the table view:
