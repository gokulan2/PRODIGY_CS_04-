Keylogger by Kalmux
Overview
This is a simple Python keylogger that records keystrokes into a log file. The keylogger captures each key pressed on the keyboard and writes it to a file named keylog.txt. This tool is intended for educational purposes only and should not be used for any malicious activities.

Features
Logs Keystrokes: Records all keys pressed on the keyboard.
Handles Special Keys: Spaces, Enter, and other special keys are handled appropriately for better readability in the log file.
Timestamps: Logs the start time of the keylogging session.
Error Handling: Captures and prints any exceptions that occur during file writing.
Requirements

Python 3.x
pynput library

Installation
Install dependencies:

You need to have pynput installed. You can install it via pip:

pip install pynput
Usage
Run the keylogger:

Simply execute the Python script:

python keylogger.py
Stop the keylogger:

To stop the keylogger, press Ctrl + C in the terminal where the script is running.

View logs:

The keystrokes will be recorded in a file named keylog.txt located in the same directory as the script. You can open this file to view the logged keystrokes.

Code Explanation
write_log(data): Writes the captured keystrokes to keylog.txt.
keylog(key): Processes each key press, formatting special keys like Space and Enter, then logs the key.
listen(): Initializes the keylogger, starts recording keystrokes, and logs the start time of the session.
