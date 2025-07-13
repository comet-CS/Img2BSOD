# ⚠️ WARNING: I AM NOT RESPONSIBLE FOR ANY DAMAGES THAT MAY BE CAUSED BY THIS, USE AT YOUR OWN RISK! ⚠️

# Img2BSOD

**Img2BSOD** is a Python tool that displays a fullscreen image on all monitors for 5 seconds at system startup and then rises a BSOD, without prompting for admin on every boot.

---

## ⚠️ Disclaimer

This tool has the potential to be used maliciously. Use it **only on systems you own or have explicit permission to test**. The author is **not responsible for misuse**.

---

## 💡 Features

- Displays an embedded image fullscreen on all monitors for 5 seconds
- Executes a specified CMD command with admin rights **after the image**
- Automatically runs at every boot using Windows Task Scheduler
- No UAC prompts after initial setup
- Entire image is packed into the Python file (no external files needed)
- Scheduled task uses an official-looking name to blend in

---

## 🖥️ Requirements

- Windows 10/11
- Python 3.10 or newer
- Admin rights (only needed once during initial setup)

---

## 📦 Python Packages Required

Before running the script, install the following Python packages:

```bash
pip install pillow screeninfo
