# Simple Borderless

**Version:** v1.0

A lightweight Python tool that lets you make any window (like LEGO Worlds) **borderless and fullscreen** on Windows. Built with Tkinter, PyGetWindow, and PyWin32.

## Features

- Lists all open windows.
- Make any window **borderless fullscreen** with a single click.
- Logs actions in a GUI console.
- Refresh window list dynamically.

## Requirements

- Python 3.x
- pywin32
- pygetwindow

Install dependencies via pip:

pip install pywin32 pygetwindow

## Usage

1. Run `simple_borderless.py`:

python simple_borderless.py
2. Select the window you want to make borderless from the dropdown.
3. Click **"🔄 Refresh List"** to update the window list.
4. Click **"🪟 Make Borderless"** to remove the window border and maximize.

## Notes

- Works best with games running in **windowed mode**.
- Compatible with most Windows applications.
- No modification of the target application is performed.
- Can be converted to an EXE using PyInstaller:

pyinstaller --onefile --windowed simple_borderless.py

## License

MIT License

3️⃣ .gitignore
__pycache__/
*.pyc
*.pyo
*.pyd
*.exe
dist/
build/
