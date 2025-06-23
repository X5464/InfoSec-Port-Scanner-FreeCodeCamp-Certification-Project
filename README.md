# 🔍 InfoSec Port Scanner  
**FreeCodeCamp Information Security Certification Project**

This is a beginner-friendly, Python-based **Nmap automation tool**, created as part of the [FreeCodeCamp Information Security Certification](https://www.freecodecamp.org/learn/information-security/). It simplifies common Nmap scans with an interactive terminal interface.

---

## 📁 Project Overview
InfoSec-Port-Scanner/
├── Scanner.py         # Main Nmap automation script
├── README.md          # This file
└── .venv/             # Virtual environment (optional, not pushed to GitHub)

---

## 💡 Features

- Interactive CLI to choose scan type
- SYN ACK Scan (`-sS`)
- UDP Scan (`-sU`)
- Comprehensive Scan (`-sS -sV -sC -A -O`)
- Auto-detects if virtual environment is needed

---

## ⚙️ Requirements

### 🐍 Python 3 (Recommended: 3.8+)

- **macOS:**  
  Install using [Homebrew](https://brew.sh):
  ```bash
  brew install python


•	Windows:
Download from python.org
✅ Make sure to check “Add Python to PATH” during installation.

⸻

🌐 Nmap
•	macOS:
brew install nmap

•	Windows:
Download & install from: https://nmap.org/download.html
✅ Add Nmap to your PATH during installation.

🚀 Installation & Usage

1. Clone the Repository
2. git clone https://github.com/X5464/InfoSec-Port-Scanner-FreeCodeCamp-Certification-Project.git
cd InfoSec-Port-Scanner-FreeCodeCamp-Certification-Project

3. (Optional) Create a Virtual Environment
	•	macOS/Linux:
python3 -m venv .venv
source .venv/bin/activate

	•	Windows:
python -m venv .venv
.venv\Scripts\activate

4. Install Dependencies:
   pip install python-nmap


5.Run the Script
python Scanner.py

Choose a scan option:
1) SYN ACK Scan
2) UDP Scan
3) Comprehensive Scan

Example-
The IP address entered is: 192.168.1.1
You have selected the option: 1
Nmap Version: ('7.94',)
Ip Status: up
Protocols detected: ['tcp']
Open Ports: [22, 80, 443]


🔧 Troubleshooting
•	❌ ModuleNotFoundError: No module named 'nmap'
👉 Activate your virtual environment and run:
pip install python-nmap



•	❌ nmap not found
👉 Make sure Nmap is installed and added to your system PATH:
	•	On Windows: check the Environment Variables
	•	On macOS: which nmap should return a path

⸻

🧠 Future Plans
	•	Export scan results to file
	•	Add CLI flags for non-interactive use
	•	Detect multiple hosts or subnets

⸻

📜 License

This project is licensed under the MIT License.

⸻

👤 Author

Rajarshi Chakraborty
🎓 BCA Cybersecurity | FreeCodeCamp InfoSec Certification
📍 GitHub: @X5464

⸻

🎯 Project Purpose

This tool was developed as part of the FreeCodeCamp Information Security Certification project tasks. It demonstrates basic knowledge of network scanning, automation, and CLI interactivity using Python.
