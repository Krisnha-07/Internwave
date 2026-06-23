# 🌊 Internwave — Official Website

> **Learn with Internwave** — A student-first internship & training platform helping learners gain real-world skills across Engineering, Technology, Management, Biotechnology, and more.

🔗 **Live Site:** [internwave.co.in](https://internwave.co.in)

---

## 📌 About

Internwave is a structured internship and professional training platform built for college students and fresh graduates. It bridges the gap between academic learning and industry requirements through hands-on programs, live projects, mentorship, and industry-recognised certificates.

---

## ✨ Features

- 🤖 **AI Chatbot** — Built-in smart chatbot that answers visitor queries instantly, with a custom Q&A admin panel to add your own questions and answers
- 💬 **WhatsApp Integration** — One-click WhatsApp chat support via Click-to-Chat plugin
- 📱 **Fully Responsive** — Mobile-friendly design built with Elementor on WordPress
- 🎓 **Course Catalog** — Wide range of internship programs across multiple domains
- 🏅 **Certificates** — Industry-recognised certificates on program completion
- 🌐 **Campus Ambassador Program** — Affiliate & ambassador opportunities for students

---

## 🗂️ Internship & Training Programs

### 💻 CSE / IT
`Web Development` `Full Stack` `Data Science` `Machine Learning` `Artificial Intelligence` `Python` `Java` `Cloud Computing` `AWS` `Cyber Security` `IoT` `App Development` `UI/UX` `Graphic Design` `Game Development` `Data Structures & Algorithms`

### ⚡ ECE / EEE
`Embedded Systems` `Internet of Things` `Robotics Engineering` `VLSI Training` `IC Engine` `Battery Electric Vehicles` `Hybrid & Electric Vehicle`

### 🏗️ Civil / Mechanical
`AutoCAD Training` `Construction Planning` `Hybrid & Electric Vehicle`

### 🧬 Biotechnology
`Bio-Informatics` `Nanotechnology`

### 📊 Management
`Finance Training` `Digital Marketing` `Business Analytics` `Operations Management` `Human Resources` `Stock Market`

### 🧠 Life Science
`Psychology`

---

## 🤖 AI Chatbot — How It Works

The chatbot is embedded directly into the website HTML and requires no backend server.

**Answer Priority:**
1. **Custom Q&A** — Admin-defined questions checked first (stored in browser `localStorage`)
2. **Built-in Knowledge Base** — 20+ pre-loaded answers about Internwave programs, fees, enrollment, etc.
3. **Claude AI Fallback** — Calls the Anthropic API for anything not covered locally

**Features:**
- 🏠 Main Menu button to reset conversation from anywhere
- ⚡ Quick reply buttons after every response
- ⚙️ Admin panel (bottom-left ⚙️ icon) to add/delete custom Q&A — no coding needed
- 📍 Chat button positioned above the WhatsApp button (no overlap)

**To add your own Q&A:**
1. Open the website in a browser
2. Click the ⚙️ icon at the bottom-left
3. Enter keywords in "Question" (comma-separated for multiple triggers)
4. Enter the answer text
5. Click ➕ Add Q&A

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| CMS | WordPress |
| Page Builder | Elementor Pro |
| Theme | Hello Elementor |
| WhatsApp | Click to Chat by HoliThemes |
| Chatbot | Vanilla JS + Anthropic Claude API |
| Hosting | internwave.co.in |
| Cache | LiteSpeed Cache |

---

## 📁 Repository Structure

```
├── index.html          # Main homepage (exported from WordPress)
└── README.md           # This file
```

---

## 🚀 Deploying the Chatbot

The chatbot code is injected at the bottom of `index.html`. To use it on a WordPress site:

1. Go to **Appearance → Theme File Editor** (or use a custom HTML plugin)
2. Paste the chatbot `<style>`, HTML, and `<script>` blocks before the closing `</body>` tag
3. Or use a plugin like **Insert Headers and Footers** to add the script sitewide

No additional dependencies or npm packages are required.

---

## 📞 Contact

- 🌐 Website: [internwave.co.in](https://internwave.co.in)
- 📱 WhatsApp: [+91 84311 57281](https://wa.me/918431157281)
- 📧 Contact Form: [internwave.co.in/contact-us](https://internwave.co.in/contact-us/)

---

© 2025 Internwave. All rights reserved.
