# 🌱 Python Mini Labs

A collection of small, independent Python projects created for learning, experimenting, and exploring different programming concepts. ☕✨

Each project has its own purpose, ranging from automation scripts to simple graphical applications. A little space to experiment, build, break things, and learn along the way. 🤍

## 🗂️ Repository Structure

The top-level structure is intentionally simple. Each Python script is a standalone project, with no shared modules or centralized architecture.

```text
python-mini-labs/
├── dollar_auto_notification.py   # USD exchange rate monitoring and email notifications
├── email_sender.py               # Simple HTML email sender
└── tictactoe.py                  # Tic-tac-toe game with a Tkinter GUI
```

## 🌿 How It Works

This repository is a collection of independent Python mini-projects. Each script has its own functionality and can be executed separately.

* **💱 `dollar_auto_notification.py:`** Fetches the latest USD-to-BRL exchange rate from an external API and sends an email notification based on a predefined exchange rate threshold.
* **✉️ `email_sender.py`:** Sends emails using a simple HTML template.
* **🎮 `tictactoe.py`:** Implements a classic Tic-Tac-Toe game with a graphical interface built using Tkinter.

There are no shared modules or dependencies between the projects. Each one is self-contained and focuses on a different Python concept.

## ⚙️ Getting Started
### Prerequisites

Before running the scripts, make sure you have:

* 🐍 Python 3 installed.
* 🌐 An internet connection (required for the exchange rate notification script).
* 📦 Tkinter installed (usually included with standard desktop Python installations).

### Running the Projects

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/python-mini-labs.git
cd python-mini-labs
```

Run any project individually:

```bash
python tictactoe.py
```

```bash
python email_sender.py
```

```bash
python dollar_auto_notification.py
```

## 🕯️ Configuration & Notes

Some scripts require personal configuration before they can be used:

* **`email_sender.py`:** Update the sender's email address, recipient address, and app password.
* **`dollar_auto_notification.py`:** Configure the email credentials and adjust the exchange rate threshold (5.20) according to your preferences.
* **`tictactoe.py`:** Requires Tkinter to be available in your Python environment.

### 💱 Exchange Rate API

The dollar notification script uses the AwesomeAPI to retrieve the latest USD-to-BRL exchange rate:

```text
https://economia.awesomeapi.com.br/last/USD-BRL
```

An active internet connection is required for this functionality.

## 🍃 A Little More About This Repository

These mini labs are part of my journey through Python and software development.

The goal is simple: keep experimenting, practice new concepts, explore different tools, and turn small ideas into working projects.

One script at a time. 🌱

---
Made with Python and a little bit of curiosity👊😸
