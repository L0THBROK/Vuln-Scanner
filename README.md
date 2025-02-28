# Vuln-Scanner 🔍

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Overview 📋

Vuln-Scanner is an open-source security testing tool designed to help testers identify common vulnerabilities in web applications. The tool scans websites for issues such as SQL Injection, Cross-Site Scripting (XSS), server errors, File Inclusion, CSRF, insecure HTTP headers, and Directory Traversal. It also checks for the presence of login panels and scans for open ports on the target domain.

**Repository:** [https://github.com/L0THBROK/Vuln-Scanner](https://github.com/L0THBROK/Vuln-Scanner)

---

## Features 🚀

- **Comprehensive Web Scanning:** Detects common web vulnerabilities.
- **Intelligent Crawling:** Automatically gathers internal links for thorough scanning.
- **Port Scanning:** Identifies open ports on the target domain.
- **User-Friendly Output:** Provides colored messages with a typewriter effect for an engaging experience.
- **Modular Design:** Easily extendable to include additional security tests.

---

## Installation & Setup 🛠️

### Clone the Repository

```bash
git clone https://github.com/L0THBROK/Vuln-Scanner.git
cd Vuln-Scanner

Install Dependencies

Install the required Python packages using the provided requirements.txt file:

pip install -r requirements.txt

Make the Script Executable

chmod +x VulnScan.py

Usage ▶️

To start the scanner, run:

./VulnScan.py

Follow the on-screen instructions to enter the target domain and begin the scan.

Contributing 🤝

Contributions are welcome! Please follow these steps:
	1.	Fork the Repository.
	2.	Create a New Branch:

git checkout -b feature/YourFeature


	3.	Commit Your Changes:

git commit -m "Add new feature"


	4.	Push Your Branch:

git push origin feature/YourFeature


	5.	Open a Pull Request on the original repository.

Disclaimer ⚠️

Important Notice:
This tool is intended for educational purposes and authorized security testing only. Unauthorized use on systems without explicit permission is illegal and unethical. Please use this tool responsibly.

License 📄

This project is licensed under the MIT License. See the LICENSE file for details.
