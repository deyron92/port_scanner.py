# 🔍 Python TCP Port Scanner

A lightweight, professional-grade TCP Port Scanner written in Python. Built for real-world demonstrations of network diagnostics, automation readiness, and cybersecurity fundamentals. Supports both interactive and command-line execution with optional JSON output for integrations and toolchain pipelines.

---

## 📂 Project Structure
```
port-scanner.py/
├── core_script                 # Main script (handles scan, CLI, JSON)
├── README.md                   # Project overview and usage instructions
├── CONTRIBUTING.md             # Guidelines for contributors
├── LICENSE                     # MIT License
└── docs/
    ├── overview.md             # Technical explanation of scanner logic
    └── developer_notes.md      # Author's motivation and learning process
```

---

## ⚙️ Features
- TCP port scanning with adjustable port range
- Fully supports CLI automation or manual use
- Outputs scan results to human-readable or JSON format
- Designed for clean extensibility (multithreading, export, GUI, etc.)
- Zero external dependencies (built-in libraries only)

---

## 🚀 Quick Start
### ✅ Requirements
- Python 3.7 or higher

### 💻 Interactive Mode
```bash
python3 port_scanner.py
```
Follow prompts for target, start port, and end port.

### 🧪 Command-Line Mode
```bash
python3 port_scanner.py --host 192.168.1.1 --start 20 --end 1024
```

### 📤 Command-Line with JSON Output
```bash
python3 port_scanner.py --host scanme.nmap.org --start 22 --end 80 --json
```

---

## 🧠 Sample JSON Output
```json
{
  "target": "192.168.1.1",
  "open_ports": [22, 80, 443],
  "scan_duration": "0:00:01.547"
}
```

---

## 📘 Documentation
Full documentation is available in the `docs/` folder:
- [docs/overview.md](docs/overview.md) — Technical scanner logic
- [docs/developer_notes.md](docs/developer_notes.md) — Project background, learning process, and future plans

---

## 🤝 Contributing
Interested in contributing? See [CONTRIBUTING.md](CONTRIBUTING.md) for code standards, ideas, and testing guidance.

---

## ⚖️ License
This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute under the terms specified.

---

## 👨‍💻 Author
**Deyron**  
Network Technician & Automation Strategist  
Focused on delivering real-world solutions in IT infrastructure, security automation, and network scripting.
