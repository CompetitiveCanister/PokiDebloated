# 🕹️ How to Play Offline

To play offline, the game must be opened through a **local web server**. Choose the method below that best fits your system:

## Method 1: Windows Only

Run `launch.bat` located within this folder.

## ⚡ Method 2: Python
*Works on Windows, macOS, and Linux.*

Most computers already have Python installed.

1. Open your **Terminal** (macOS/Linux) or **Command Prompt / PowerShell** (Windows).
2. Navigate to this unzipped game folder:
   ```bash
   cd path/to/this-folder
   ```
3. Run the server command:
   * **Python 3:**
     ```bash
     python -m http.server 8000
     ```
   * **If `python` doesn't work, try:**
     ```bash
     python3 -m http.server 8000
     ```
4. Open your web browser and go to:  
   👉 **[http://localhost:8000](http://localhost:8000)**
