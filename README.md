# qubes-os-security - Advanced settings for Qubes OS

# 🛡︄1�7 Integrated Security Blueprint  1�7 Qubes OS + Kicksecure

<div align="center">

**The comprehensive Arabic/English guide for hardening Qubes OS for advanced users and those seeking maximum privacy**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Qubes OS](https://img.shields.io/badge/Qubes%20OS-4.3-blue)](https://www.qubes-os.org/)
[![Whonix](https://img.shields.io/badge/Whonix-18-green)](https://www.whonix.org/)

</div>

---

## 📖 About this guide

This file is a complete interactive guide (single HTML file) covering all aspects of hardening and securing **Qubes OS 4.3** with **Whonix 18** and **Kicksecure**. The guide is intended for users with medium to high threat models (journalists, researchers, activists, and digital privacy enthusiasts).

This is the **English version**  1�7 an Arabic version is also available in the repository.

---

## ✄1�7 Features

- 📋 **11 interactive tabs** covering everything from basic setup to self‑destruct mechanisms
- ⚄1�7 **Automated helper script** that applies most settings with one click (Tab 11)
- 🌓 **Dark / light modes** for comfortable reading
- 📊 **Comprehensive comparison tables** for all security options
- 📝 **One‑click copy** for all commands
- 🎯 **Threat matrix** with 35 threats and their mitigations

---

## 📑 Table of contents

| Tab | Content |
|---|---|
| **0. Basics** | Kernel parameters (dom0 vs VMs), external drive, Secure Boot, critical parameters |
| **1. Network** | WISP + Ethernet only, MAC randomization, IPv6, architecture diagrams, emergency plans |
| **2. Whonix Gateways** | Multiple gateways, stream isolation, bridges (obfs4, Snowflake), sdwdate, entry guards |
| **3. Secure Storage** | LUKS, VeraCrypt, double encryption (VC+LUKS), storage‑execution separation, SSD warnings |
| **4. Threat Matrix** | 35 threats (timing attacks, Evil Maid, Cold Boot, fingerprinting, stylometry, etc.) with solutions |
| **5. Amnesic Tmpfs** | Making directories ephemeral (logs, cache, /home) in RAM |
| **6. RAM Pool** | Running entire VMs in RAM (complete deniability) |
| **7. Advanced Security** | BadUSB, VPN+Tor, encrypted backups, dual boot warning, Evil Maid & Cold Boot, BusKill, self‑destruct tools, emergency plans, physical protection |
| **8. Kicksecure** | Browser fingerprint unification, system hardening, security‑misc, hiding kernel information |
| **9. Live Script** | Live Mode (OverlayFS) + full comparison of all ephemeral/secure qube types (DVM, Ephemeral DVM, Amnesic Tmpfs, RAM Pool, Dom0 Live Boot, Live+RAM‑VM) |
| **10. Portable Apps** | SimpleX, Cwtch, OnionShare, Gajim, Element, Signal (not recommended), Session, Telegram, metadata removal, torsocks |
| **11. Helper Script** | Central `auto-script.sh` to automate everything (kernel parameters, MAC, gateways, Kicksecure, RAM pool, Amnesic Tmpfs, Live Mode, destruction tools, LUKS hardening) |

---

## 📥 Download and usage

1. Download the file `q_en.html` (English) or `q.html` (Arabic) from [this repository](https://github.com/abdullah127-code/qubes-os-security-)
2. Open it in any modern browser (Firefox, Chrome, Brave)
3. Navigate through the tabs at the top
4. Click on any command to copy it automatically
5. Use the Helper Script in Tab 11 for automation

---

## 🌐 Live preview

You can preview the guide directly via HTML Preview:

🔗 [**Click here for English version preview**](https://htmlpreview.github.io/?https://github.com/abdullah127-code/qubes-os-security-/blob/docs/q_en.html)

🔗 [**Click here for Arabic version preview**](https://htmlpreview.github.io/?https://github.com/abdullah127-code/qubes-os-security-/blob/main/q.html)

---

## 🔧 The helper script (`auto-script.sh`)

The integrated script in Tab 11 automates:

- ✄1�7 Kernel parameters for dom0 and all VMs (GRUB + Secureblue sysctl)
- ✄1�7 MAC randomization and IPv6 disable
- ✄1�7 Creation of multiple Whonix gateways
- ✄1�7 Kicksecure installation and hardening (user‑space)
- ✄1�7 RAM Pool scripts (setup, single VM, multi‑VM, cleanup, status)
- ✄1�7 Amnesic Tmpfs (apply / remove)
- ✄1�7 Live Mode (OverlayFS) with ephemeral DVMs
- ✄1�7 Destruction tools (BusKill, Dead Man’s Switch, immediate nuke)
- ✄1�7 LUKS system disk hardening (PBKDF2 ↄ1�7 Argon2id with custom memory/time)

---

## ⚠️ Important warning

> **This guide is intended for advanced users only.**

Some procedures described (especially destruction tools in Tab 7) can lead to **permanent, irreversible data loss**. Use with extreme caution and always take backups before applying anything.

---

## 🤝 Contributing

This project is open for review and improvement. If you find any error or have a suggestion:

1. Open an **Issue** describing the problem or suggestion
2. Submit a **Pull Request** with your proposed changes
3. Contact me directly on GitHub

---

## 📜 License

This work is licensed under the **MIT License**  1�7 you may freely use, modify, and share it with attribution to the source.

See the [LICENSE](LICENSE) file for full details.

---

## 📚 Sources

- [Qubes OS Documentation](https://www.qubes-os.org/doc/)
- [Whonix Documentation](https://www.whonix.org/wiki/Documentation)
- [Kicksecure Documentation](https://www.kicksecure.com/wiki/Documentation)
- [Hitchhiker's Guide to Online Anonymity](https://anonymousplanet.org/)

---

## ⭄1�7 Support the project

If you found this guide useful, please:
- ⭄1�7 Star the project
- 🔗 Share it with those who might benefit
- 📢 Spread the word in privacy and digital security communities

---

<div align="center">

**"Trust no one. Not your ISP, not your VPN provider, not the Tor network, not the operating system, not even your own computer. Trust, but verify."**

</div>
