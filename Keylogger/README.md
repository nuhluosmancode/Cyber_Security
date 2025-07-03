# 🔑 Keylogger Script

This Python script is a simple keylogger designed to run on **Windows**. It captures all keystrokes typed by the user and saves the log to a file located on the **same flash drive** where the script is executed.

---

## ⚙️ How It Works

- When executed from a USB flash drive, the script **creates a log file on the flash drive**.
- It records every key pressed by the user.
- The log file updates in real-time as keys are typed.
- Designed to run on **Windows OS** with Python 3 installed.

---

## 🚀 Usage

1. Copy `keylogger.py` to your USB flash drive.
2. Run the script using:

   ```bash
   python keylogger.py


⚙️ Optional: Convert to Executable & Autorun

    You can convert the .py script into a standalone Windows executable (.exe) using tools like PyInstaller:

pyinstaller --onefile keylogger.py

The .exe file can be placed on the flash drive for easier execution without requiring Python to be installed on the target PC.

Using autorun software or scripting, the .exe can be configured to autorun automatically when the flash drive is plugged in, making execution seamless.

🛠️ Requirements

    Python 3.x installed on the Windows machine (if running .py directly)

    pynput Python library

Install dependencies via:

pip install pynput
