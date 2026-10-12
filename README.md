# 🛡️ FortifySec

> **Open-Source System Fortification & Vulnerability Hardening Script**

**FortifySec** is a lightweight, open-source bash utility designed to lock down unused ports, seal common security vulnerabilities, and harden device security across Unix-like systems. Built with transparency and simplicity in mind, FortifySec helps protect your system against unauthorized access and potential cyber threats.

---

## ✨ Features

* **🔒 Port Lockdown:** Automatically identifies and closes vulnerable or unnecessary open ports.
* **🛡️ Hardening Scripts:** Applies security best practices to safeguard against common system exploits.
* **⚡ Lightweight & Fast:** Written in pure Bash for minimal resource consumption and zero extra dependencies.
* **🌐 Open-Source Transparency:** Fully audited and open code—know exactly what runs on your device.

---

## 🚀 Getting Started

### Prerequisites

* Any Unix/Linux system or macOS device supporting **Bash v4.0+**
* `root` or `sudo` privileges to modify network and system security configurations

### Quick Installation

Clone the repository and navigate to the project directory:

```bash
git clone [https://github.com/mastercodibaby/FortifySec.git](https://github.com/mastercodibaby/FortifySec.git)
cd FortifySec
```

Make the script executable:

```bash
chmod +x fortifysec.sh
```

💻 Usage

Run FortifySec with root privileges to apply standard security hardening:

```bash
sudo ./fortifysec.sh
```

Options

| Flag | Description |
|---|---|
| -h, --help | Display help menu and command options |
| -c, --check | Run a dry-run diagnostic scan without making system changes |
| -a, --apply | Run full security hardening and close unused ports |

🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated!

 * Fork the Project
 * Create your Feature Branch (git checkout -b feature/AmazingFeature)
 * Commit your Changes (git commit -m 'Add some AmazingFeature')
 * Push to the Branch (git push origin feature/AmazingFeature)
 * Open a Pull Request

📜 License

Distributed under the MIT License. See LICENSE for more information.

🌐 Links

 * Website: [https://mastercodibaby.github.io/FortifySec](https://mastercodibaby.github.io/FortifySec/)
 * Report Issues: GitHub Issues
