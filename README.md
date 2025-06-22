Advanced File Organizer Bot

> Description
An intelligent file organization bot with a GUI that monitors a selected folder and organizes files in real-time based on extension,
type, or size. Ideal for automating cleanup in Downloads or Desktop folders.

> Features
•	GUI for selecting folder and sorting options
•	Organizes files by extension/type/size
•	Real-time monitoring using Watchdog
•	Auto-creates categorized folders

> Technologies
•	Python 3.x
•	Tkinter
•	Watchdog
•	OS / shutil

> Getting Started
Create and activate a virtual environment
python -m venv .venv

# Windows
.\.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

# Install dependencies
pip install watchdog
Run the app
python file_organizer.py

> Requirements
watchdog
