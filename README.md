# Keylogger
## 🚨 Disclaimer
This project is for **educational and ethical use only**. It is intended to demonstrate how keylogging works and should **never** be used to record keystrokes on any system without **explicit authorization** from the device owner. Unauthorized use of tools like this may violate privacy laws and terms of service agreements.

## 🧠 About
This Python script demonstrates:
- How to capture keyboard input using the `pynput` library.
- How to log keystrokes locally to a text file.
- How to send collected data via email using SMTP and TLS encryption.

## ⚙️ Configuration
Before running:
1. Replace `sender_mail` and `receiver_mail` with your own authorized email addresses.
2. Use **App Passwords** (not your main account password) if using Gmail.
3. Ensure you have **permission** to test the script on the system you use.

## 🚀 Usage
Run the script in a controlled environment only

The program will:
- Record keystrokes.
- Save them to a file named `keylogger.txt`.
- Email the file contents to the configured sender and receiver addresses.

## 🧩 Educational Purpose
This tool can help you learn about:
- Logging mechanisms in Python.
- Secure SMTP communication.
- How anti-virus tools detect similar behaviors.
