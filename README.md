# Auto-Messenger-m-I

This repository contains a Python script that automates the process of sending messages in various applications. The script reads the contents of a text file and sends it as a message.

## Features

- Automates the process of sending messages in various applications.
- Reads the contents of a text file and sends it as a message.
- Allows you to set a delay before starting.
- Allows you to set the typing speed (words per minute).

## Requirements

- Python
- PyAutoGUI

## Usage

1. Ensure that the application is already open and visible on your screen.
2. Replace the (x, y) values in the script with the appropriate coordinates of your application window. These coordinates can be determined by using the `pyautogui.position()` function.
3. Replace the `file_path` in the script with the path to your text file.
4. Run the script.

Please note that this script simulates keyboard typing, so it will take control of your keyboard while it's running. Make sure not to use your computer while the script is running or it may interrupt the process.

## Disclaimer

This script is for educational purposes only. Please use responsibly and ensure that you comply with all relevant terms of service and privacy policies when using this script.
