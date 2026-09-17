# Akshay R Bhat — AI Resume & Portfolio

A modern, high-tech, responsive **AI Resume Portfolio** and **ATS-Friendly Resume** showcasing projects at the intersection of **Generative AI** and **Mobile Engineering (Android / Kotlin / React Native)**.

---

## 🌟 What's Included

- **`index.html`** — The Interactive Web Portfolio:
  - High-tech dark obsidian cyberpunk aesthetic with glowing cyan and purple accents.
  - **Flagship Project Spotlight: DO — AI Life Operating System** with full architecture breakdown (3-Tier Intent Engine: Tier 0 Regex <5ms, Tier 1 Semantic <30ms, Tier 2 LLM <250ms) and live demo link.
  - **AksharaDeepaTutor** showcase (Kotlin, Jetpack Compose, MVVM, Text-to-Speech API).
  - **AI Code Reviewer** showcase (MERN Stack + Google Gemini API).
  - **Interactive Recruiter Copilot (AI Terminal)** allowing visitors to simulate querying Akshay's portfolio with pre-configured prompts.
  - **Work Experience Timeline** covering the Generative AI Android Internship at **MindMatrix.io**.
  - **Technical Skills Matrix** with badges for AI/LLMs, Mobile, Languages, Full Stack, and Developer Tools.
  - 1-click **Copy to Clipboard** for Email and Phone.
  - Links to GitHub, LinkedIn, and live project demos.

- **`resume.html`** — ATS-Friendly Printable Resume:
  - Clean, professional typography structured for both human recruiters and automated ATS resume parsers.
  - Dedicated print styles (`@media print`) that remove web bars and format cleanly to a single page (A4 / Letter).
  - Built-in "Print / Save to PDF" button (`Ctrl + P`).

- **`resume.md`** — Clean Markdown version of the updated resume for quick copy-pasting into job portals or markdown viewers.

---

## 🚀 How to View Locally

You can open the files directly in any web browser:
1. Double-click **`index.html`** to view the interactive portfolio.
2. Double-click **`resume.html`** to view or print the ATS resume.

Alternatively, you can run a lightweight local server:
```bash
# Using Python
python -m http.server 8000

# Or using Node.js / npx
npx serve .
```
Then open `http://localhost:8000` in your browser.

---

## 📄 How to Export Clean PDF Resume

1. Open `resume.html` in Chrome, Edge, or Firefox.
2. Click the **"🖨️ Print / Save to PDF (Ctrl+P)"** button at the top right.
3. In the print dialog:
   - Destination: **Save as PDF**
   - Layout: **Portrait**
   - Margins: **Default** or **Minimum**
   - Options: Check **"Background graphics"** (optional)
4. Click **Save** to get a clean PDF.

---

## 🌐 How to Publish to GitHub Pages for Free (2 Minutes)

1. Create a new repository on your GitHub named `portfolio` (or `akshayrbhat-2004.github.io`).
2. Push all the files (`index.html`, `resume.html`, `resume.md`, `README.md`) to the repository:
   ```bash
   git init
   git add .
   git commit -m "Launch AI Resume Portfolio"
   git branch -M main
   git remote add origin https://github.com/AKSHAYRBHAT-2004/portfolio.git
   git push -u origin main
   ```
3. In your GitHub repo:
   - Go to **Settings** &rarr; **Pages**.
   - Under **Build and deployment** &rarr; **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Within 60 seconds, your portfolio will be live at:
   `https://akshayrbhat-2004.github.io/portfolio/`
