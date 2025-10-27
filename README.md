# ShortcutFactory

ShortcutFactory is an application for automatically generating shortcuts (.lnk files) through batch processing.

It’s a standalone .exe file that requires no installation and runs from any location.

## 🖥️ Features

- 🔍 Recursively scans source folders for `.vstpreset` files
- 🔗 Creates `.lnk` shortcuts with absolute paths
- 📁 Places all shortcuts flat in a single target folder
- 🧾 Generates a concise log file named `_LOGS.txt`
- 🛑 Includes a STOP button to cancel long operations
- 🪟 Simple graphical user interface (GUI)
- 🧵 Runs file operations in a background thread for responsiveness
- 🧠 Supports long Windows paths (`\\?\` prefix)

## 📦 Installation

**No installation required.**  
This is a single `.exe` file that runs independently.  

## 🚀 Usage

1. Download the .exe-file.
2. Double-click to launch the application.
3. In the GUI:
   - Select a ***Sample File*** to determine the filtetype you want to generate shortcuts for.
   - Select a **source folder** containing the source files.
   - Select or create a **target folder** where `.lnk` files will be placed.
   - Click **Generate** to start the process.
   - Use **STOP** to cancel at any time.

## 📄 Output

- All `.lnk` files are created in the target folder.

##

⚖️ License

This software is provided as Freeware.

    Free of charge for personal use
    non-commercial distribution is possible
    No warranty, no liability

See [Show License](LICENSE) for full details.
