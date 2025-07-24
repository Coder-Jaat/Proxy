# 🛡️ Coder-Jaat Transparent Proxy Setup Tool

![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-blue?style=flat-square&logo=linux)
![License](https://img.shields.io/github/license/Coder-Jaat/Proxy?style=flat-square)
![Stars](https://img.shields.io/github/stars/Coder-Jaat/Proxy?style=flat-square)

A fully automated **Tor Transparent Proxy Tool** for **Kali Linux** – built with ❤️ by **JAAT CYBER NETWORK**.  
Routes **all system traffic via Tor**, enabling full anonymity using `iptables`, DNS redirection, and auto config healing.

---
## 📦 Requirements

- ✅ Kali Linux (Tested on latest Rolling release)
- ✅ `tor` package (auto-installed by script)
- ✅ `iptables-persistent`
- ✅ `sudo` privileges (required for firewall & DNS rules)

## 🔥 Features

- ✅ One-click Tor Transparent Proxy setup
- ✅ Fully flushes old config before applying new
- ✅ Auto-detect & fallback for Tor service
- ✅ DNS redirection via `resolv.conf` & `iptables`
- ✅ Auto-fix if Tor fails (self-healing)
- ✅ Clean shutdown & full restore of original network
- ✅ Built for real-world use on **Kali Linux**

---

## 🖥️ Screenshots

### 🔹 Proxy Start (Tool Activated)
![proxy start](screenshots/proxy_Start.jpg)

### 🔹 Proxy Stop (Network Restored)
![proxy stop](screenshots/proxy_stop.jpg)

---

## ⚙️ Setup & Run

### 🔹 Option 1: Rename as `Jaat_proxy` (Recommended)

# Full update&upgrade Kali Linux
```
sudo apt update && sudo apt full-upgrade -y && sudo apt autoremove -y && sudo apt clean
```
# Clone the tool
```
git clone https://github.com/Coder-Jaat/Proxy.git
```
# Enter directory
```
cd Proxy
```
# Rename script (optional)
```
mv Coder_Proxy.sh Jaat_proxy
```
# Make executable
```
chmod +x Jaat_proxy
```
# Run the tool
```
sudo ./Jaat_proxy
```
📝 𝑷𝒓𝒐 𝑻𝒊𝒑: Always use sudo while running this tool to allow firewall & DNS changes.
### 💡 Alternate Run Method
### 🔹 Option 2: Directly `Use Default Script Name`

# Full update&upgrade Kali Linux
```
sudo apt update && sudo apt full-upgrade -y && sudo apt autoremove -y && sudo apt clean
```

# Clone the tool
```
git clone https://github.com/Coder-Jaat/Proxy.git
```
# Enter directory
```
cd Proxy
```
# Make it executable
```
chmod +x Coder_Proxy.sh
```
# Run the tool
```
sudo ./Coder_Proxy.sh
```
---

## 🔐 Disclaimer

This tool is intended for **educational and research purposes** only.  
Using it for malicious activities is strictly prohibited.  
**JAAT CYBER NETWORK** is not responsible for any misuse.

---

## 🙋 Support & Credits

> Built by **Sagar Rana** (aka `coder-jaat`)  
> GitHub: [@coder-jaat](https://github.com/coder-jaat)  
> Telegram: [@iT_CoderX](https://t.me/iT_CoderX)  
> Community: [xAnonymous_Hacking](https://t.me/xAnonymous_Hacking)

---

💖 *If you like this project, give it a ⭐ star on GitHub and share with your hacker fam!*

---
© 2025 — Released under the [MIT License](LICENSE)
