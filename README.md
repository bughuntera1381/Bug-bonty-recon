🎯 Bounty Hunter - Recon Dashboard

A sleek, local web dashboard for automating Bug Bounty reconnaissance. It runs real security tools and streams their output live to your browser.

---

🚀 How to Run (Quick Start)

1. Extract the Project

Download the ZIP file and extract it to a folder.

2. Open Terminal

Open your terminal and navigate into the project folder:

cd bounty-hunter

3. Install Requirements

Install the required Python packages:

pip3 install -r requirements.txt

4. Launch the Dashboard

Start the application:

python3 main.py

5. Start Scanning

The dashboard will automatically open in your browser at:

"http://127.0.0.1:8080"

Enter your target domain and click Start Scan!

---

🛠️ Requirements

Before running the application, make sure the following tools are installed and available in your system PATH:

- Subfinder — Subdomain enumeration
- HTTPX — ProjectDiscovery version (Go binary, not Python package)
- Nuclei — Vulnerability scanning

Note: If Nuclei reports a template-related error, update its templates:

nuclei -update-templates

---

⚖️ Disclaimer

This tool is developed for educational purposes and authorized Bug Bounty reconnaissance and security testing only.

Only scan domains and assets for which you have explicit permission.

The developer is not responsible for any misuse or unauthorized activity involving this tool.

---

Built for Bug Bounty Hunters. 🎯
