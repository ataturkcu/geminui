# Geminui

**A simple GUI for `gemini-cli` — inspired by Claudia, built for developers who prefer visuals.**

## 🌟 What is Geminui?

Geminui is a lightweight graphical interface built on top of [`gemini-cli`](https://github.com/moyix/gemini-cli). While `gemini-cli` is powerful, it can be intimidating for users who are not comfortable with command-line tools. Geminui solves this by providing a clean and simple desktop GUI — so you get all the power of Gemini, but with none of the terminal stress.

This project was inspired by [Claudia](https://github.com/l-quebec/claudia), which offers a GUI for Claude-based workflows. Geminui brings the same philosophy to the world of open-source Gemini agents.

## ⚙️ How It Works

- Geminui connects directly to `gemini-cli` in the background.
- Any action you perform via the GUI is translated into CLI commands.
- You still use `gemini-cli` — just with buttons, not Bash.

## 🖼️ Features

- 🧠 View and resume old chats.
- ✍️ See edited code results in real time.
- 📋 One-click copy/paste of outputs.
- ↩️ Undo and re-send prompts.
- 💡 Lightweight interface, written in Python.

## 🚀 Why Geminui?

Many tools like `gemini-cli` are powerful, but not everyone likes using the terminal. Some users find the CLI experience difficult or unfriendly — especially beginners or visual thinkers. Geminui lowers that barrier and improves accessibility without sacrificing control.

## 📦 Installation

> ⚠️ You'll need `gemini-cli` already installed and configured.

```bash
git clone https://github.com/ataturkcu/geminui.git
cd geminui
pip install -r requirements.txt
python main.py
```

## 🧪 Status
Early prototype — functional, but evolving. Contributions welcome.

## 🧠 Inspiration
Built after seeing the awesome Claudia project for Claude Code. I thought: “Why not do the same for Gemini... before anyone else does?”

## 📝 License
Apache 2.0 License

Made with ❤️ by ataturkcu
