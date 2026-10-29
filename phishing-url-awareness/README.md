# EWB Phishing URL Awareness Checker

A simple Python-based mini project designed to inspect visible URL text for common warning signs associated with potential phishing attempts.

## Features
- Checks for `@` symbols in URLs.
- Detects unusually long URLs (over 100 characters).
- Identifies raw IP addresses used instead of domain names.
- Checks for excessive subdomains or segments.
- Flags punycode-style hostnames (`xn--`).
- Warns if the HTTP protocol is used.

## Project Structure
- `phishing_checker.py`: Main Python script.
- `requirements.txt`: Project dependencies note.
- `tests/test_samples.md`: Sample URLs tested and their findings.
- `screenshots/`: Folder for program run screenshots.

## How to Run
1. Ensure Python is installed on your system.
2. Run the script using the command:
   ```bash
   python phishing_checker.py
