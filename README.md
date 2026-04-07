<div align="center">

# 🚀 Resume Optimizer

**AI-powered resume optimization to match job descriptions, close skill gaps, and improve ATS compatibility — runs entirely in the browser, no backend required.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![GeekStrom Hackathon](https://img.shields.io/badge/GeekStrom-Hackathon-blueviolet?style=for-the-badge)](/)

</div>

---

## 🏆 Hackathon

> This project was built as part of the **GeekStrom Hackathon**.

| Field | Details |
|---|---|
| 🏅 **Hackathon** | GeekStrom Hackathon |
| 👥 **Team Name** | Innoventures |
| 👤 **Members** | G. Naga Sai Prasanna &nbsp;·&nbsp; AB. Keerthana |

---

## 📋 Table of Contents

- [Features](#-features)
- [Requirements](#-requirements)
- [Getting Started](#-getting-started)
- [How to Use](#-how-to-use)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Disclaimer](#️-disclaimer)
- [License](#-license)

---

## ✨ Features

| Tab | Feature |
|---|---|
| 📝 **Input** | Paste your resume and job description side-by-side |
| 🔍 **Gap Analysis** | Detects missing skills and calculates an ATS match score |
| ✨ **Optimizations** | Rewrites bullets using STAR method with quantified metrics |
| 💼 **Summary** | Generates a tailored professional summary |
| 📄 **Final Output** | Formatted preview with checklist and next steps |
| 🏆 **Final Resume** | Print-ready, fully parsed resume document |

- ✅ Zero dependencies — single HTML file, works offline
- ✅ Smart section parser — handles Experience, Skills, Education, Projects, Certifications
- ✅ Auto-detects contact info (email, phone, LinkedIn) from resume text
- ✅ Adds missing keywords from the job description directly into your Skills section
- ✅ One-click copy as Markdown or Print / Save as PDF

---

## 📦 Requirements

### To Run (End User)

| Requirement | Details |
|---|---|
| 🌐 **Browser** | Any modern browser — Chrome 90+, Firefox 88+, Edge 90+, Safari 14+ |
| 📄 **File** | Just `resume-optimizer.html` — no install needed |
| 🔌 **Internet** | Only needed to load Google Fonts (works offline with system fonts as fallback) |

> **No Node.js, no Python, no server, no build step required.**

### To Develop / Extend

| Requirement | Version | Purpose |
|---|---|---|
| [Node.js](https://nodejs.org/) | v18+ | Only if you want a local dev server |
| [Git](https://git-scm.com/) | Any | Version control |
| A code editor | e.g. VS Code | Editing the HTML / CSS / JS |

#### Optional: Run with a local dev server

```bash
# Using Node.js
npx serve .

# Using Python
python -m http.server 8080

# Using VS Code — install the "Live Server" extension and click "Go Live"
```

---

## 🚀 Getting Started

### Option 1 — Run Directly (Simplest)

1. Download `resume-optimizer.html`
2. Double-click to open in your browser
3. Done ✅

### Option 2 — Clone the Repository

```bash
git clone https://github.com/your-username/resume-optimizer.git
cd resume-optimizer
open resume-optimizer.html      # macOS
start resume-optimizer.html     # Windows
xdg-open resume-optimizer.html  # Linux
```

### Option 3 — Deploy to GitHub Pages

1. Push this repository to your GitHub account
2. Go to **Settings → Pages**
3. Set source branch to `main`, folder to `/ (root)`
4. Your app will be live at:

```
https://your-username.github.io/resume-optimizer
```

---

## 📖 How to Use

1. Open `resume-optimizer.html` in your browser
2. Click **📋 Load Sample Data** to try it instantly, _or_ paste your own content:
   - **Left panel** → your resume
   - **Right panel** → the job description
3. Click **⚡ Analyze & Optimize**
4. Browse the result tabs:
   - **Gap Analysis** — see which skills you're missing
   - **Optimizations** — review STAR-rewritten bullets
   - **Summary** — copy the tailored professional summary
   - **Final Resume** — view and export the complete document
5. Use **📋 Copy Resume** or **🖨️ Print / Save PDF** to export

---

## 📁 Project Structure

```
resume-optimizer/
│
├── resume-optimizer.html    ← The entire application (HTML + CSS + JS)
└── README.md                ← This file
```

> The entire app lives in a single self-contained file — no external JS files, no CSS files, no frameworks.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Structure and markup |
| **CSS3** — Grid, Flexbox, Custom Properties | Layout and responsive styling |
| **Vanilla JavaScript (ES6+)** | Parsing, optimization logic, rendering |
| **Google Fonts** — DM Sans & DM Mono | Typography (loaded via CDN) |
| **Clipboard API** | One-click copy functionality |
| **Window.print()** | Print / Save as PDF |

---

## ⚠️ Disclaimer

This tool uses **heuristic-based optimization** — it does not connect to any AI API. All skill detection, bullet rewrites, and summaries are rule and pattern-based.

- Always review suggestions carefully before using them
- **Never include fabricated or inaccurate achievements on your resume**
- Treat all output as a starting point, not a final draft

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

## 🤝 Contributing

Pull requests are welcome! Ideas for contribution:

- Improve skill keyword detection patterns
- Add support for PDF resume uploads
- Integrate with an AI API for smarter rewrites
- Add more resume templates for the Final Resume view
- Multi-language support

```bash
# Fork, clone, then:
git checkout -b feature/your-feature-name
git commit -m "Add your feature"
git push origin feature/your-feature-name
# Open a Pull Request on GitHub
```

---

<div align="center">
  Made with ❤️ by <strong>Innoventures</strong> &nbsp;·&nbsp; GeekStrom Hackathon
</div>
"# Intelligent-Resume-Optimization-Platform-" 
