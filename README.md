# ![](./Images/Github.png) &nbsp;&nbsp;   WEBSERVER

## Simple file-sharing  `Webserver` for `Windows` or `Linux`

# Quick Overview

This application creates a local HTTP server with a sleek, modern GUI, allowing instant browser access to the folder where the script is run. Share files effortlessly across your local network—no setup, no installation, just run and go.

# Repository Contents

    📦 WebServer.py: - Main Python script (fully in English)
    📦 WebServer - Spanish.py: - Python script (translate to Spanish)
    📦 Readme.md: - This documentation file.
    📁 Images/ - This documentation file

# Features

- Local file sharing via web browser (view, download, run HTML/JS/CSS, etc.)
- **Cross-platform:** Works on Windows and Linux.
- **Multi-IP aware:** Automatically detects and displays all local IPv4 addresses
- **User-friendly & Moderm GUI**, no more "Windows95's style" programs 😊.
- No admin rights needed – runs entirely in user space.
- **Can change the target folder and port**.
- Live activity log with export to CSV
- Tested on: Gnu-Linux & Windows.
- Supports real-time log monitoring and CSV export for auditing.

# Requirements

This script uses only two external packages (not part of Python’s standard library):
    BASH:
    pip install customtkinter Pillow

- ✅ Tested on Python 3.9+
- ❌ No additional modules like Flask, Django, or Node.js are required.

# Quick Start

1. Download WebServer.py

2. Put the file in the folder you want to share or other you like.

3. Run the script:
   
   - *python WebServer.py*

4. A window will appear showing:
   
   - Your local IP addresses (e.g., 192.168.1.25)
   - The active port (default: 8000, you can change)
   - Full path to the shared folder (default: current, you can change.)

5. Open your browser and navigate to:
   http://192.168.1.25:8000 (replace with your actual IP)

6. Just press `▶ Start Server` button and share files instantly with any device on the same network!
   
        🔒 The server only binds to your local network interfaces — it is not publicly accessible from the internet.

# Screenshots

![](./Images/Screenshot.png)
(*Ip Adresses hidden in the capture*)

# Stopping the Server

- Click the `⏹ Stop Server` button in the GUI, or
- Close the application window
  (The server shuts down cleanly in both cases)

# ✨ Use Cases

- Share documents/media with colleagues on a local network.
- Preview web projects without deploying.
- Transfer files between devices without USB or cloud.
- Demonstrate local apps during development.

# How It Works

- Uses Python’s built-in `http.server` module as the backend.
- Wraps it in a custom handler to log requests to the GUI.
- Serves files from the current working directory.
- Dynamically updates the list of accessible URLs as network interfaces change.
- Supports real-time log monitoring and CSV export for auditing.

# License

MIT License — free to use, modify, and distribute.

See [LICENSE](https://opensource.org/license/mit) for details.

# 💬 Feedback & Contributions
Found a bug? Have a feature idea?

👉 Open an [Issue](https://github.com/MiguelAdePablo/Webserver/issues) or submit a PR!

# 🌐 Useful Links

- [Apps Index (under construction)](https://github.com/MiguelAdePablo/apps)
- [General Index (under construcion)](https://github.com/MiguelAdePablo/Index)



        Developed with ❤️ using Python and customtkinter
        By Miguel Ángel de Pablo
