# SURAJ — Digital Literacy & Engineering Portfolio

> **1st-Year B.Tech Computer Science & Engineering Portfolio**  
> **Institution:** JECRC University, Jaipur  
> **Course:** Digital Literacy & Applied Computing  
> **Author:** SURAJ ([soulcodesmith@gmail.com](mailto:soulcodesmith@gmail.com))

---

## 🌟 Overview & Design Philosophy

This repository contains a modern, responsive, single-page personal engineering portfolio created to fulfill the **Digital Literacy** course requirements at **JECRC University** and establish a professional presence for internships and technical collaborations.

### Design System (Inspired by Linear, Apple & Vercel):
- **Theme:** Sophisticated dark mode (`#09090b` / `zinc-950`) with crisp typography and subtle radial ambient lighting.
- **Glassmorphism:** Hairline translucent borders (`border-white/[0.08]`), backdrop blurs (`backdrop-blur-xl`), and rounded-2xl cards.
- **Micro-Interactions:** Smooth 200ms hover lifts, glowing card borders, and an interactive email one-click clipboard copy toast notification.
- **Zero Build Complexity:** Pure HTML5, modern Tailwind CSS (via CDN), and Lucide Icons (via CDN). No npm, node_modules, or webpack required to run or view.

---

## 🧱 Sections Included

1. **Floating Navigation Bar:** Glassmorphism sticky header with monogram logo, smooth scrolling anchor links, quick resume request trigger, and a mobile hamburger menu.
2. **Hero Section:** Live pulsing status pill badge (`● 1st Year B.Tech Student | JECRC University`), bold minimal headline, concise bio, primary/secondary call-to-actions, and social profile links.
3. **Digital Literacy & Core Skills (Bento Grid):**
   - **Programming & Scripting:** Python 3, C (ANSI/C99), C++ basics, HTML5, CSS3, JavaScript (ES6+).
   - **Digital Literacy & Workflow:** Git & GitHub, Linux/Bash, Markdown & Obsidian, LaTeX, Google Workspace & Excel.
   - **Foundational Computing:** Binary/hex data representation, internet architecture (DNS, HTTP/S, TCP/IP), digital ethics & cyber hygiene, algorithmic thinking.
   - **Lab & System Competency:** GCC compiler, VS Code, POSIX APIs, environment setup.
4. **Featured Projects & Coursework:**
   - **LexiCalc:** First-principles recursive-descent math expression tokenizer & AST parser in Python.
   - **NetByte:** Digital literacy & internet protocols peer learning web portal.
   - **SysProbe:** Minimalist POSIX Linux resource & `/proc` inspector in C.
5. **Academic Journey & Milestones:** Vertical timeline highlighting current semester courses (Digital Literacy, C/Python Programming, Engineering Mathematics, Digital Logic) and future roadmaps.
6. **Footer & Contact:** One-click copy email button with instant feedback toast (`soulcodesmith@gmail.com`), social links, and academic attribution.

---

## 🚀 How to Run Locally

### Option 1: Double-Click
Simply double-click `index.html` in your file explorer / Finder to open it immediately in Google Chrome, Safari, Firefox, or Microsoft Edge.

### Option 2: Local HTTP Server (Python)
Run the following command from this directory:
```bash
python3 -m http.server 8000
```
Then visit: [http://localhost:8000](http://localhost:8000)

---

## 🌐 Free 1-Minute Deployment Options

### Deploying to GitHub Pages:
1. Initialize git and commit:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Digital literacy portfolio for SURAJ (JECRC Uni)"
   ```
2. Create a new repository on [GitHub](https://github.com/new) called `portfolio` or `<your-username>.github.io`.
3. Push your code:
   ```bash
   git remote add origin https://github.com/<your-username>/portfolio.git
   git branch -M main
   git push -u origin main
   ```
4. In your GitHub repository, go to **Settings** > **Pages** > select **Deploy from a branch** > branch `main` / root > **Save**. Your site will be live at `https://<your-username>.github.io/portfolio/`!

### Deploying to Vercel:
1. Drag and drop the folder directly into the [Vercel Dashboard](https://vercel.com/new).
2. It will deploy instantly with a live `.vercel.app` URL and free SSL certificate.

---

## 📝 Personal Customization Guide

Look for the following commented sections inside `index.html` to customize with your personal links:
- `<!-- GitHub: Replace 'https://github.com' with your profile -->`
- `<!-- LinkedIn: Replace 'https://linkedin.com' with your profile -->`
- `<!-- X (Twitter): Replace 'https://x.com' with your profile -->`
- `<!-- Direct Email: Pre-configured to soulcodesmith@gmail.com -->`
- In the resume buttons: adjust the `mailto:` subject or replace with a direct PDF file link (e.g. `href="assets/resume.pdf"`).

---

*Created for B.Tech CSE Coursework Evaluation • JECRC University • 2026*
