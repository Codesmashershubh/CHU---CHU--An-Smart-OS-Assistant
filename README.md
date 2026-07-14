# 🚀 CHU-CHU — AI Smart OS Assistant

<p align="center">
  <img src="docs/images/logo.png" alt="CHU-CHU Logo" width="180"/>
</p>

<p align="center">
  <b>An AI-powered desktop assistant capable of understanding natural language, automating desktop tasks, interacting with applications, and executing intelligent workflows.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue"/>
  <img src="https://img.shields.io/badge/Electron-Latest-47848F"/>
  <img src="https://img.shields.io/badge/FastAPI-009688"/>
  <img src="https://img.shields.io/badge/Python-3.10-yellow"/>
  <img src="https://img.shields.io/badge/Node.js-20+-green"/>
  <img src="https://img.shields.io/badge/License-MIT-success"/>
</p>

---

# 📸 Preview

> Replace these images with your screenshots.



## AI Assistant

<p align="center">
<img src="docs/images/chat.png" width="900">
</p>

## Automation Execution

<p align="center">
<img src="docs/images/automation.png" width="900">
</p>

---

# 📖 Overview

CHU-CHU is an AI-powered desktop operating system assistant designed to simplify human-computer interaction through natural language.

Instead of navigating multiple applications manually, users can simply describe what they want to do. CHU-CHU interprets the request, determines the appropriate action, and executes it securely through its automation engine.

The project combines AI reasoning, desktop automation, browser automation, and a modular plugin architecture into one intelligent desktop application.

---

# ✨ Features

- 🧠 Natural Language Understanding
- 🤖 AI-powered Task Execution
- 🖥 Desktop Application Automation
- 🌐 Browser Automation
- 📂 Intelligent File Operations
- 🔌 Plugin-based Skill System
- ⚡ FastAPI Backend
- 💬 Modern Electron Desktop UI
- 🔒 Confirmation Before Sensitive Operations
- 📈 Easily Extendable Architecture

---

# 🏗 Architecture

```
                    User
                      │
                      ▼
              Electron Desktop
                      │
                      ▼
               FastAPI Backend
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
   Intent Recognition      Automation Engine
          │                       │
          ▼                       ▼
     Skill Dispatcher      Browser/Desktop Skills
          │                       │
          └──────────────┬────────┘
                         ▼
                   Windows Operating System
```

---

# 🛠 Tech Stack

### Frontend

- Electron
- HTML
- CSS
- JavaScript

### Backend

- FastAPI
- Python
- Uvicorn

### AI

- Python
- Intent Recognition
- Modular Skill System

### Automation

- Desktop Automation
- Browser Automation
- Command Execution

---

# 📂 Project Structure

```
CHU-CHU
│
├── backend/
├── frontend/
├── plugins/
│   ├── automation-skills/
│   └── browser-skills/
├── docs/
├── docker-compose.yml
├── render.yaml
├── README.md
└── package.json
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/CHU-CHU.git

cd CHU-CHU
```

---

## Install Dependencies

### Backend

```bash
cd backend

pip install -r requirements.txt
```

### Frontend

```bash
cd ../frontend

npm install
```

---

## Configure Environment Variables

Create a `.env` file inside the `backend` directory and add all required API keys and configuration values.

---

# ▶ Running the Backend

```bash
cd backend

uvicorn app.main:app --reload
```

---

# ▶ Running the Desktop Application

Open a new terminal.

```bash
cd frontend

npm run electron:dev
```

---

# 📌 Current Capabilities

✅ Launch Applications

✅ Open Websites

✅ Desktop Automation

✅ Browser Automation

✅ Natural Language Commands

✅ Plugin-based Skills

✅ FastAPI API Layer

✅ Electron Desktop Client

---

# 🧩 Plugin System

CHU-CHU uses a modular plugin architecture.

Example:

```
plugins/
│
├── automation-skills/
├── browser-skills/
```

New skills can be added without modifying the core application.

---

# 📈 Roadmap

- Voice Commands
- Offline AI Support
- Local LLM Integration
- Multi-Agent Architecture
- Memory System
- Calendar Integration
- Email Automation
- Smart Workflow Builder
- Cross-platform Support

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Shubham**

If you found this project helpful, consider giving it a ⭐ on GitHub.
## License

MIT — see [LICENSE](LICENSE).
