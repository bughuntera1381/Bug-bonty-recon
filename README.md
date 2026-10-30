

```markdown
# 🎯 Bounty Hunter - Advanced Reconnaissance Center

A local, browser-based bug bounty reconnaissance dashboard for Linux. 
This tool runs real reconnaissance tools (`subfinder`, `httpx`, `nuclei`) and streams their output live to a modern web UI.

## ✨ Features
- **Live Console**: Watch the output of your scans in real-time.
- **Modern UI**: A sleek, dark-themed dashboard.
- **Scope Enforcement**: Filters out-of-scope hosts before running `nuclei`.
- **Export Results**: Save your findings as TXT, JSON, or CSV.

---

## 🚀 Quick Start Guide

Follow these simple steps to run the tool on your Linux machine:

### Step 1: Download the Project
Click the green **Code** button at the top of this page and select **Download ZIP**. 
Extract the downloaded ZIP file into a folder.

### Step 2: Open Terminal
Open your terminal and navigate to the folder where you extracted the project:
```bash
cd path/to/extracted/folder
```

Step 3: Install Requirements

Install the necessary Python packages:

```bash
pip3 install -r requirements.txt
```

(If you get an error about externally-managed-environment, run: pip3 install -r requirements.txt --break-system-packages)

Step 4: Run the Application

Start the dashboard:

```bash
python3 main.py
```

Step 5: Start Scanning

Your browser should open automatically. If not, go to: http://127.0.0.1:8080

· Enter your target domain.
· Check the authorization box.
· Click Start Scan.

---

⚠️ Troubleshooting

1. Nuclei Error (no templates provided for scan):
If Nuclei fails, you need to download its templates. Run this command in your terminal:

```bash
nuclei -update-templates
```

2. Tools are Missing:
Make sure subfinder, httpx (Go version, not Python), and nuclei are installed and in your system PATH.

---

⚖️ Legal Disclaimer

This tool is created for educational purposes and authorized bug bounty testing only. You must have explicit permission to scan any target. The developer is not responsible for any misuse or illegal activities.

```

