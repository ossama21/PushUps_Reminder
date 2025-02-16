# Pushup Reminder Pro v1.4

Release Date: March 14, 2024

A modern desktop application to help you maintain a regular pushup routine with customizable reminders and statistics tracking.

## Features

- Customizable pushup reminder intervals
- Daily goals and progress tracking
- Statistics dashboard with streaks
- Multiple notification themes and sounds
- System tray support
- Modern UI with multiple themes
- Progress animations
- Custom sound support
- Daily statistics tracking
- Auto-start option

## Requirements

- Python 3.8+
- Windows 10/11 (for native notifications)

## Installation

1. Clone the repository or download the source code:
```bash
git clone https://github.com/yourusername/pushup-reminder.git
cd pushup-reminder
```

2. Create and activate a virtual environment (recommended):
```bash
python -m venv venv
venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Required Python Packages

```txt
tkinter
ttkbootstrap
pillow
psutil
win10toast
pystray
pygame
```

## Running the Application

```bash
python pushup_reminder.py
```

## Project Structure

```
pushup-reminder/
├── pushup_reminder.py
├── README.md
├── requirements.txt
└── assets/
    ├── icons/
    │   ├── logo.ico
    │   ├── logo.png
    │   ├── pushup.png
    │   ├── settings.png
    │   └── stats.png
    └── sounds/
        ├── default.wav
        ├── guitar_down.wav
        ├── guitar_up.wav
        └── rain.wav
```

## Configuration

The application automatically creates a configuration file at:
- Windows: `%USERPROFILE%\.pushup_reminder\config.json`

## Version History

- v1.5 (Current)
  - Fixed notification system reliability
  - Added COM initialization for Windows notifications
  - Added fallback notification method
  - Fixed completion dialog display issues
  - Added developer credits

- v1.4
  - Added custom sound support
  - Improved tray icon functionality
  - Added daily goals feature
  - Enhanced statistics tracking

- v1.3
  - Added multiple themes
  - Improved notifications
  - Added system tray support

- v1.2
  - Added statistics dashboard
  - Added streak tracking
  - Improved UI/UX

- v1.1
  - Added basic reminder functionality
  - Added pushup counter
  - Basic settings

## License

MIT License - Feel free to use and modify as needed.