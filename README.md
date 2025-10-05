# SilverwolF
# 🐺 SilverWolf C2 Framework/ToolKit
# By: Scav-engeR
> **Advanced, modular, and evasion-aware Command & Control (C2) framework for offensive security research and authorized red team operations.**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![License](https://img.shields.io/badge/License-GPLv3-red)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20macOS-lightgrey)

---

## ⚠️ Legal Disclaimer

**This tool is for authorized penetration testing and educational purposes only.**  
Unauthorized use against systems you do not own or have explicit written permission to test is **illegal** and may result in severe civil and criminal penalties. The author assumes **no liability** for misuse.

> 🔒 **Use responsibly. Know your laws. Get written authorization.**

---

## 🌟 Features

### 🧟 Zombie Network
- **Dork-based scanning** across 6 search engines (DDG, Bing, Yandex, Startpage, Kagi, Yahoo)
- **Multi-type zombie support**:
  - XML-RPC Pingback Abuse
  - Open Redirect Exploitation
  - Web Endpoint Flooding
- **Zombie validation & reliability scoring**
- **Chained proxy → redirect attacks**

### 💥 Multi-Vector DDoS
- **Layer 3/4 Attacks** (with optional IP spoofing):
  - TCP SYN Flood
  - UDP Flood
  - ICMP Flood
- **Amplification Attacks**:
  - DNS, NTP, SNMP, SSDP
  - **NEW**: Memcached, CLDAP, Chargen
- **Layer 7 HTTP Flood** (async, with header spoofing)

### 🛡️ Evasion & OPSEC
- **IP spoofing** for L3/L4 attacks (via Scapy)
- **Header spoofing**: `X-Forwarded-For`, `Via`, fake Host
- **User-Agent rotation**
- **Proxy rotation** (SOCKS/HTTP)
- **Rate-limiting & random delays**

### 🧠 Intelligence & Automation
- **Dynamic dork mutation**
- **Shodan enrichment** (optional)
- **Telegram C2 bot** (remote command)
- **Export to JSON/CSV** (MISP/STIX-ready)
- **SQLite database** for attack/zombie history

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- `pip` package manager
- **Root/Admin privileges** (required for raw socket attacks)
- uv tool for ease of use
Install uv with [ curl -LsSf https://astral.sh/uv/install.sh | sh ]

### Installation
```bash
git clone https://github.com/Scav-engeR/SilverwolF.git
cd SilverWolF
uv venv -p 3.10 --allow-existing --system-site-packages -v
source .venv/bin/activate.fish
pip install -r requirements.txt
```
### Last Reminder!
- You know the rules~
- Don't be an idiot

