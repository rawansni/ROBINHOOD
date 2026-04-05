<h1 align="center">
  <br>
  <a href="https://github.com/rawansni/ROBINHOOD"><img src="https://img.shields.io/badge/ROBINHOOD-blue?style=for-the-badge&logo=github" alt="ROBINHOOD"></a>
  <br>
 GAURAV ROCK 
  <br>
</h1>

<h4 align="center">A comprehensive next-gen network scanning and subdomain discovery suite.</h4>

<p align="center">
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#features">Features</a> •
  <a href="#credits">Credits</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-yellow?style=flat-square">
  <img src="https://img.shields.io/badge/Go-1.20+-cyan?style=flat-square">
  <img src="https://img.shields.io/badge/Platform-Termux%20|%20Linux-green?style=flat-square">
  <img src="https://img.shields.io/badge/Version-2.0.4-red?style=flat-square">
</p>

---

## 🚀 Overview

**ROBINHOOD 2.0** is the enhanced evolution of the original ROBINHOOD framework. It integrates powerful prebuilt engines and advanced API-based subdomain discovery to provide a seamless Bug Bounty and Network Security experience.

## ✨ Features

- **⚡ Fast Subdomain Discovery**: Hybrid approach using APIs and Subfinder.
- **🛡️ Host Scanning**: Deep scanning with core modules.
- **🔧 Utility Suite**:
  - IP/Domain Extraction & Cleaning
  - IP Range Generation
  - File Splitting for large datasets
- **📱 Cross-Platform**: Optimized for Termux and Linux environments.

---

<h2 id="installation">📦 Installation</h2>

### 1. Essentials & Languages
```bash
pkg update && pkg upgrade -y
pkg install git python golang zlib -y
```

### 2. Setup Go & Tools
*Run these commands one by one:*

```bash
echo 'export PATH="$PATH:$HOME/go/bin"' >> $HOME/.bashrc
```
```bash
source $HOME/.bashrc
```
```bash
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
```
```bash
go install github.com/rawansni/flashscan-go@latest
```

### 3. Install ROBINHOOD
```bash
git clone https://github.com/rawansni/ROBINHOOD
cd ROBINHOOD
bash install.sh
```

---

<h2 id="usage">🔥 Usage</h2>

### ONE-CLICK RUN (Shortcut)
After installation, simply type `adwance` anywhere in your terminal to start the tool!
```bash
adwance
```

### Manual Run
```bash
cd ROBINHOOD
bash run.sh
```

---

<h2 id="credits">👥 Authors & Credits</h2>

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>👑 Main Author</strong></td>
      <td align="center"><strong>🤝 Contributor</strong></td>
      <td align="center"><strong>🎨 Design</strong></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/rawansni"><strong>MAURYA</strong></a><br>
        (Core Logic, Coding, Integration)
      </td>
      <td align="center">
        <strong>Sanki</strong><br>
        (Normal Scanner, Subdomain CMS API)
      </td>
      <td align="center">
        <strong>KAAL</strong><br>
        (UI/UX Concepts)
      </td>
    </tr>
  </table>
  
  <br>
  
  <p><strong>Contact:</strong> <a href="mailto: ROBINHOOD_SD">ROBINHOOD PAPA/a></p>
  <p><strong>Telegram:</strong> <a href="https://t.me/ROBINHOOD_SD">@SirYadav</a></p>

  <img src ="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20in-India-orange?style=for-the-badge">
</div>
