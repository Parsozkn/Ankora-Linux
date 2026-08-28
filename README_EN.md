# 💎 Ankora OS 1.0 (Emerald)

[![Base](https://img.shields.io/badge/Base-Debian%2012%20(Bookworm)-A80030?logo=debian&logoColor=white)](#)
[![Desktop](https://img.shields.io/badge/Desktop-XFCE-2284F2?logo=xfce&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Status-Stable-10B981)](#)

> **A Debian-based Linux distribution tailored for gamers and developers, ready out-of-the-box.**

[🇹🇷 Türkçe README için tıklayın (Click here for Turkish)](README.md) 
## 📖 About Ankora OS
Ankora OS is not about reinventing the wheel. It is built on the rock-solid foundation of **Debian 12 (Bookworm)** but eliminates the tedious post-installation setup. Designed for developers and gamers, Ankora OS comes pre-configured with essential performance tweaks, modern command-line tools, and a beautifully customized lightweight XFCE desktop environment. 

Whether you want to compile code without running out of memory or jump straight into gaming, Ankora OS respects your time by providing a ready-to-use environment.

## ✨ Key Features

### 🚀 Performance & System
* **Optimized Memory Management:** Pre-configured **ZRAM** (zstd algorithm at 100% capacity) and **EarlyOOM** to prevent system freezes during heavy workloads or gaming.
* **Hardware Efficiency:** `irqbalance` and `NetworkManager` are enabled by default for optimal CPU and network routing.
* **Bloat-Free Desktop:** A deeply customized, lightweight XFCE desktop featuring a modern Dark & Emerald Green aesthetic (`#1e1e2e` / `#10B981`).

### 🛠️ Developer & Gamer Ready
* **Containers & Packages:** **Docker** and **Flatpak** (with Flathub repo) are integrated and ready to use.
* **Gaming:** **GameMode** is pre-installed for instant FPS boosts and system optimization during gameplay.
* **Modern CLI Experience:** Legacy tools are symlinked to their modern, Rust-based alternatives out of the box:
  * `eza` (replaces `ls`)
  * `bat` (replaces `cat`)
  * `fd` (replaces `find`)
* **Customized Terminal:** A pre-configured `.bashrc` loaded with useful aliases and a beautiful boot ASCII art.

### 💿 Seamless Installation
* Replaced the standard Debian installer with the user-friendly **Calamares Installer**, fully branded with Ankora OS assets for a smooth setup experience.

## 📸 Screenshots

<img width="1366" height="768" alt="Screenshot_20260822_124753" src="https://github.com/user-attachments/assets/0949fcdc-31d4-4eb2-beaf-f1b1eb99a975" />
(It was run from a live ISO on an old computer.)
## 📥 Download & Installation

1. Go to the [Releases](../../releases) page and download the latest `Ankora-OS-1.0-amd64.iso` file.
2. Flash the ISO to a USB drive using [Ventoy](https://www.ventoy.net/), [Rufus](https://rufus.ie/), or [BalenaEtcher](https://balena.io/etcher/).
3. Boot your PC from the USB drive.
4. You can test the system in **Live Mode** or click the **"Install Ankora OS"** icon on the desktop to start the Calamares installer.

## 🤝 Contributing
Feedback, bug reports, and pull requests are always welcome! If you are a distro-hopper or a developer, feel free to test the ISO and open an issue if you encounter any bugs.

## 📝 License
Ankora OS is an open-source project and follows the free software guidelines. The base system is Debian, and all respective licenses of the pre-installed open-source software apply.
