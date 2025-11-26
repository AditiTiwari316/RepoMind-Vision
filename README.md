# 👁️ RepoMind Vision
>**The World's First Multimodal Whole-Repository Debugger Powered by Gemini 2.5.**

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io)
[![Powered by Gemini](https://img.shields.io/badge/Powered%20by-Gemini%202.5%20Flash-4c8bf5)](https://ai.google.dev/)

## 🔥 The Problem — “The Blind AI Paradox”
Modern AI coding assistants (ChatGPT, GitHub Copilot, etc.) are powerful but '**blind**' :
* They cannot see UI/UX screens, so visual bugs go undetected.
* They fail to correlate UI screenshots with the underlying code.
* They struggle with large codebases (40–100+ files).
* Developers waste 50% of their time debugging UI issues manually.

## 🟢 RepoMind Vision — The Solution
RepoMind Vision solves this by acting as a '**multimodal debugger**' that ingests:

 📁 Your entire repository (.zip)
 🖼️ A screenshot of the visual bug

Using **Gemini 2.5 Flash’s** huge context window & vision abilities, it:
* Reads all code files
* Analyzes pixel-level UI issues
* Maps UI problems to the exact file, line number, and faulty code
* Suggests accurate fixes instantly

## ✨ Key Features
🔹 ***Whole-Repo Understanding***

Upload a full ZIP of your project — RepoMind Vision ingests 1M+ tokens instantly.

🔹 ***Multimodal Vision Debugging***

Upload screenshots of UI bugs — the AI interprets visual problems within the UI.

🔹 ***Gemini 2.5 Flash Engine***

Runs on Google’s latest fastest multimodal model, enabling real-time debugging.

🔹 ***Precise Error Localization***

Maps UI issues (e.g., button invisible) to the corresponding code (e.g., CSS opacity:0).

🔹 ***Instant Fix Suggestions***

Returns exact :

* File name
* Line number
* Problem explanation
* Corrected code

## 🛠️ How It Works
1️⃣ Upload Codebase

User uploads a **.zip** file of the entire project.

2️⃣ Upload UI Evidence

User uploads a screenshot of the bug.

3️⃣ AI Analysis

Gemini 2.5 Flash cross-references :

* Visual artifacts

* HTML/CSS/JS/Python/React/etc. files

* DOM interactions

* Layout inconsistencies

4️⃣ Auto-Fix Output

RepoMind Vision returns :

* Exact location of the bug

* Explanation

* Full patch/fix


## 🚀 Run Locally
# Clone the repository
git clone https://github.com/AditiTiwari316/RepoMind-Vision.git

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py


## 🧰 Tech Stack

* Google Gemini 2.5 Flash (Multimodal AI Engine)
* Streamlit (Frontend + App Interface)
* Python (Backend Logic)
* Zipfile / File Processing (Code ingestion)
* Vision + Code Embeddings


## 👥 Team & Contributors
**Project Owner**
* Aditi Tiwari — Developer & Repository Maintainer

**Collaborator**
* Chirag Sharma — Developer & Original Co-Creator

🏆 Built with ❤️ at CODESPIRE 3.0 (AITR Indore)

## ⭐ If You Like This Project

Consider ⭐ starring the repo — it motivates us to build more innovative AI tools!
