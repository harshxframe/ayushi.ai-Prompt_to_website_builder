# Ayushi.AI — Prompt to Website Generator
A hobby project that turns your prompt into a live editable website with instant preview and one-click publish.
Simple idea → Clean Code → Live Website 🚀

✨ Features
🎤 Voice-to-Text input for prompts

⚡ Prompt Enhance for better, structured generation

💻 Live Code Editor with real-time Preview

📱 Mobile/Desktop view toggle

📂 Download website as a single HTML file

🌍 Live Publish → instantly get a public link

🔄 Reset button to recover from mistakes

📑 Three built-in Prompt Templates to choose from

⚙️ Environment Setup
Before running, create .env files in both the server and client folders.

🔹 Server (server/.env)
Code snippet

# 🌐 Server
PORT=2000
FRONTEND_URL=yout url

# 🔑 API Keys
GEMINI_API_KEY=your-gemini-api-key-here

# 📦 Other Config
NODE_ENV=development

🔹 Client (client/.env)
Code snippet

# API base URL for local dev
VITE_API_BASE=http://localhost:2000
🚀 Quick Start
1️⃣ Clone the repo:

Bash

git clone https://github.com/harshxframe/ayushi.ai-web-builder
cd ayushi.ai-web-builder
2️⃣ Install dependencies:

Bash

# Install client dependencies
cd client && npm install

# Install server dependencies
cd ../server && npm install
3️⃣ Run locally:

Bash

# Terminal 1 → start backend
cd server && npm run dev

# Terminal 2 → start frontend
cd client && npm run dev
4️⃣ Open 👉 http://localhost:5173 in your browser.

📸 Preview
Here are some screenshots of Ayushi.AI in action:
<p style="text-align: center;">
  <img src="https://iili.io/KdHwRTB.md.png" style="width: 350px;" title="Home-Page">
  <img src="https://i.ibb.co/q3t2VP43/Screenshot-2025-08-24-at-6-04-11-PM.png" style="width: 350px;" alt="OutPut Page">
  <img src="https://iili.io/KdHw7Q1.md.png" style="width: 350px;" alt="Publish Website">
  <img src="https://iili.io/KdHwcEg.md.png" style="width: 350px;" alt="Mobile output">
</p>



🛠️ Tech Stack
Frontend: React + Vite + TailwindCSS

Backend: Node.js + Express

AI Integration: Gemini API

Hosting: Vercel (Frontend) + Local/Node Server (Backend)

💖 Credits
Project Name inspired by Ayushi ❤️

Developed with love & hustle by Harsh Verma ✨


