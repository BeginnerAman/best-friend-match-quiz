# 🤝 Aman Vishwakarma’s Best-Friend Match Quiz

A modern, interactive, and responsive web-based compatibility quiz designed to test how well your friends know you! It features 21 carefully curated lifestyle and preference questions to calculate the ultimate friendship bond percentage. 🎯

## ✨ Features
* **21 Dynamic Questions:** Covers fun and relatable topics like weekend plans, chai vs coffee preference, music choices, and late-night rescue meals.
* **Interactive UI with Smooth Transitions:** Clean modern dark-theme interface built with glassmorphism and animated progress bars.
* **Smart Quiz Flow:** Includes built-in functionality to navigate backward (`Back` button) or skip a question with a confirmation modal prompt.
* **Live Timer & Analytics:** Tracks the time taken to complete the quiz and shows a visual step-by-step progress bar.
* **Detailed Score & Review Screen:** 
  * Generates custom badges based on performance (`Perfect Sync`, `Strong Match`, `Good Vibes`).
  * Features an advanced **Review System** showing what the user answered vs what the owner (Aman) preferred, color-coded for clarity.
* **Web Audio API Integration:** Uses lightweight, zero-dependency, programmatically generated audio tones (base64 synthesized strings) for actions like selecting options, skipping, and results.
* **Native Web Sharing:** Features a sharing system using `navigator.share` (or fallback automatic clipboard copy) so friends can instantly share their results.

## 🚀 Tech Stack
* **HTML5** - Structured semantic layouts and modal dialogs
* **CSS3** - Variables (`:root`), grid layouts, custom scrollbars, and keyframe animations (`@keyframes pulse`, `ripple`, etc.)
* **JavaScript (Vanilla)** - Quiz state handling, timer algorithms, scoring logic, and native sharing utility API

## 🛠️ How to Play
1. Enter your name on the welcome screen to unlock the quiz.
2. Answer all 21 questions based on what you think Aman would choose.
3. Check your final score, review your correct/incorrect choices, and share it with others!
