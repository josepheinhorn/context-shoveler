# 🛠️ Context Shoveler (Day 1)

<p align="center">
  <img src="./header.gif" width="300" style="image-rendering: pixelated;" alt="Character Running">
</p>

> **The Problem:** Passing project context to LLMs like Claude or GPT is a manual, slow process.
> **The Solution:** A high-speed, local-first utility that "shovels" your entire directory into a single, perfectly formatted prompt.

### 🚀 Live Demo
**[→ Click Here to Launch Context Shoveler ←](https://josepheinhorn.github.io/context-shoveler/)**

---

### ⚡ Key Features
* **Private & Secure:** Runs 100% in your browser using the File System Access API. Your code never leaves your Mac.
* **Auto-Formatting:** Instantly generates structured headers (e.g., `--- FILE: path/to/file ---`) so AI agents understand your project structure.
* **Smart Filtering:** Pre-configured to grab `.js`, `.html`, `.css`, `.md`, and `.json` while automatically ignoring `node_modules` and `.git`.
* **Pixel-Art Interface:** Styled to match the aesthetic of our upcoming 2D side-scrolling project.

### 📖 How to Use
1. Open the [Live Demo](https://josepheinhorn.github.io/context-shoveler/).
2. Click **"Select Folder"** and choose your project directory.
3. Click **"Copy to Clipboard"**.
4. Paste the entire block into Claude or GPT to provide instant, full-codebase context.
