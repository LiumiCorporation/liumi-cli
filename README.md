<div align="center">

# ⚡ LIU - Liumi Interface Utility

[![PyPI Version](https://img.shields.io/pypi/v/liumi-cli?color=00F0FF&label=Liumi%20CLI&logo=python&logoColor=white)](https://pypi.org/project/liumi-cli/)
[![Downloads](https://img.shields.io/pypi/dm/liumi-cli?color=blueviolet)](https://pypi.org/project/liumi-cli/)
[![Powered By](https://img.shields.io/badge/AI-Gemini%20%7C%20OpenAI%20%7C%20Liumi-00F0FF)](https://liumi.cloud)

**The Autonomous DevOps Agent for the Modern Developer.**

[Installation](#-installation) • [Features](#-killer-features) • [Documentation](#-command-reference) • [Liumi Cloud](https://liumi.cloud)

</div>

---

## 💡 What is LIU?

**LIU (Liumi Interface Utility)** is a terminal-based AI agent designed to eliminate "Developer Friction."

It lives in your CLI, understands your project context, automates Git workflows, secures your code, and executes complex file operations—all through natural language.

> **"Stop writing commit messages. Stop fearing code changes. Flow with Intelligence."**

---

## 🚀 Installation

Requires **Python 3.8+** and **Git**.

### Install via PyPI
```bash
pip install liumi-cli
```
### Upgrade to Latest Version
```bash
pip install --upgrade liumi-cli
```
### ⚡ Quick Start
1. Initialize the Neural Link
LIU supports Bring Your Own Key (BYOK). You can use <a href="https://dev.liumi.cloud">Liumi AI Studio (Free 1M Credits)</a>, Google Gemini (Free Tier), OpenAI, Groq, or OpenRouter.
```bash
liu setup
```
2. Run the CLI
Navigate to any project folder and type:
```bash
liu
```
LIU will scan your project, detect the stack (Python, Node, Rust, etc.), and summarize exactly where you left off.
### 🔥 Killer Features
1. 🚢 liu ship (The Magic Button)
Stop manually staging, committing, and pushing.
LIU stages your changes.
AI analyzes the git diff and writes a professional, semantic commit message.
LIU pushes to GitHub automatically.
```bash
liu ship
```
2. 👻 liu ghost (Fearless Coding)
About to refactor a core function? Create a "Reality Snapshot" first.
Start: Saves a lightweight snapshot of your project state.
Revert: Instantly undoes everything (deleted files, bad code) to the snapshot state.
```bash
liu ghost start
# ... break your code ...
liu ghost revert
```
3. 🤖 liu do (Agent Mode)
Instruct LIU to build software for you. It can create files, edit logic, and delete trash based on natural language prompts.
```bash
liu do "Create a Flask server with a dark mode HTML template"
liu do "Refactor main.py to use async/await"
```
4. 🛡 liu audit (Security Engineer)
LIU acts as a local security auditor. It scans your code for:
🔑 Leaked API Keys
🐛 Security Vulnerabilities
📉 Performance Bottlenecks
Output: A detailed report card with a Letter Grade (A-F).
```bash
liu audit
```
5. 🔥 liu ignite
Forgot the startup command? Is it npm run dev? python3 main.py? cargo run?
LIU figures it out and launches your project.
```bash
liu ignite
```
🐙 GitHub Integration
LIU connects directly to your GitHub account via Secure OAuth.
1. Connect Account
Opens your browser to authorize LIU.
```bash
liu gh-connect
```
2. Create & Link Repo
Creates a remote repo and pushes your local code instantly.
```bash
liu create-repo my-new-project
```
## 📚 Command Reference

| Command | Description |
| :--- | :--- |
| `liu` | **Resume**: Scans project context & provides a summary. |
| `liu setup` | Configure AI Provider (Liumi, Google, OpenAI, etc). |
| `liu ship` | **DevOps**: Auto-writes commit message and pushes to GitHub. |
| `liu ghost start` | **Safety**: Creates a snapshot of your files. |
| `liu ghost revert` | **Undo**: Restores files to the snapshot state. |
| `liu do "<task>"` | **Agent**: Creates, edits, or deletes files based on prompt. |
| `liu audit` | **Security**: Scans code for bugs and vulnerabilities. |
| `liu ignite` | Auto-detects and runs the project (e.g., `npm start`). |
| `liu gh-connect` | Authenticate with GitHub via Browser (OAuth). |
| `liu create-repo` | Creates a new GitHub repository and uploads code. |

## 📄 License

**Copyright © 2026 Liumi Corporation.**

This software is **Proprietary**.
Unauthorized copying, modification, distribution, or use of this source code is strictly prohibited.
All Rights Reserved.

<i>Built with 💙 by Liumi Corporation</i>
<br>
<a href="https://liumi.cloud">liumi.cloud</a>
</div>
