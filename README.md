# 4N4M DDOS - Stress Testing Tool

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Purpose-Educational-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Kali%20%7C%20Linux-black?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/TulungagungBlackHat/4N4M_ddos?style=social">
</p>

> **⚠️ DISCLAIMER: FOR EDUCATIONAL PURPOSE ONLY**
> Tool ini dibuat untuk **Stress Testing server milik sendiri** dan pembelajaran Cyber Security. Penyalahgunaan terhadap server orang lain tanpa izin adalah **ilegal**. Developer tidak bertanggung jawab atas penyalahgunaan.

Recode dari Hammer - Dioptimalkan oleh **4N4M F4K3 SM1L3** | **TULUNGAGUNG BLACK HAT**

---

### ✨ Features
- 🚀 Multi-thread DDoS simulation (Socket & HTTP Flood)
- 🕵️ Random User-Agent rotation
- 🤖 Bot hammering via validator & share endpoints
- ⚡ Lightweight, support Termux & Kali Linux
- 📊 Real-time attack status

### 📦 Installation

**Termux / Kali Linux:**
```bash
pkg update && pkg upgrade
pkg install python git
git clone https://github.com/TulungagungBlackHat/4N4M_ddos
cd 4N4M_ddos
python3 4N4MDDOS.py
```

**Linux:**
```bash
git clone https://github.com/TulungagungBlackHat/4N4M_ddos
cd 4N4M_ddos
python3 4N4MDDOS.py -s [IP_TARGET] -p [PORT] -t 135
```

### 🚀 Usage
```bash
python3 4N4MDDOS.py --help

Options:
  -s, --server   Target IP / Domain
  -p, --port     Target Port (default 80)
  -t, --turbo    Threads (default 135)
  -h, --help     Show help

Contoh (test ke server sendiri):
python3 4N4MDDOS.py -s 127.0.0.1 -p 80 -t 100
```

### 🛡️ Legal Notice
Gunakan hanya pada:
- ✅ Server / VPS milik sendiri
- ✅ Lab environment (localhost)
- ✅ Dengan izin tertulis pemilik server

Dilarang keras untuk menyerang infrastruktur publik, pemerintahan, atau pihak ketiga tanpa izin.

### 👥 Credits
- Original: Hammer
- Recode: 4N4M F4K3 SM1L3
- Team: [Tulungagung Black Hat](https://github.com/TulungagungBlackHat)

<p align="center"><b>Always Smile :)</b> | Tulungagung, Jawa Timur</p>
