# 🛡️ Fake Email Detector Plus

**Fake Email Detector Plus** is a beginner-friendly, browser-based tool that analyzes email content and headers to identify signs of phishing or spoofing. It's designed for educational use and built with pure HTML, CSS, and JavaScript — no frameworks or backends required.

## 🔍 What It Does

This tool helps you:
- Detect suspicious keywords like "urgent", "verify", or "login"
- Identify fake or lookalike domains (e.g., `gmaill.com`, `micros0ft.com`)
- Flag insecure or shortened links
- Analyze technical headers for:
  - ❌ SPF and DKIM failures
  - ⚠️ Return-Path mismatches (with trusted sender exceptions)

The app uses a simple scoring system to highlight potential risks and includes explanation tooltips to guide users — perfect for learning or awareness training.

## 🚀 Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Paste suspicious email content (and optionally headers)
4. Click **Scan Email** to see the results

No installation needed. Everything runs locally in your browser.

## 🌐 Live Demo

You can try the tool online (if hosted using GitHub Pages):

```
https://your-username.github.io/fake-email-detector/
```

> Replace `your-username` with your actual GitHub username.

## 💡 Why I Built This

This was created as part of my internship project to understand phishing techniques and improve frontend skills. I wanted to build something practical, easy to use, and helpful for beginners who want to explore cybersecurity fundamentals.

## 📂 Features Overview

- 📥 Paste email body and headers
- 🧠 Real-time analysis with helpful tooltips
- ✅ Whitelisted return-path check (e.g., `amazonses.com`)
- 🎯 Risk score indicator (green / orange / red)
- ✨ Clean UI with accessible design

## 📖 Learning Highlights

- DOM manipulation and dynamic HTML generation
- Regex usage for pattern matching
- Email security concepts (SPF, DKIM, Return-Path)
- User experience (tooltips, guidance, visual feedback)

## 🙋‍♂️ About Me

**Manash Kamal Das**  
Aspiring developer and cybersecurity enthusiast. This is one of my first hands-on tools combining web development with real-world security concepts.

---

> ⚠️ Disclaimer: This tool is for educational and awareness purposes only. It is not a substitute for professional email filtering or security software.
