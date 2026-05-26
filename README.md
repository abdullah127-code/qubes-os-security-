# 🛡️ Qubes OS Security Hardening Guide – English Version

**A comprehensive, interactive HTML guide for hardening Qubes OS 4.3 with Whonix 18 and Kicksecure**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Qubes OS](https://img.shields.io/badge/Qubes%20OS-4.3-blue)](https://www.qubes-os.org/)
[![Whonix](https://img.shields.io/badge/Whonix-18-green)](https://www.whonix.org/)

---

## 📖 About

This is a **single‑file interactive HTML guide** that covers everything from basic kernel hardening to advanced self‑destruct mechanisms. It is intended for **advanced users** with a medium to high threat model (journalists, researchers, activists, and privacy enthusiasts).

The guide is available in two languages:
- **English** (`q_en.html`)
- **Arabic** (`q.html`)

---

## ✨ Features

- 📋 **11 interactive tabs** – organised, in‑depth information
- ⚡ **Automated helper script** (`auto-script.sh`) – applies most settings with one click
- 🌓 **Dark / light modes** – easy on the eyes
- 📊 **Comprehensive comparison tables** – see all options side‑by‑side
- 📝 **One‑click copy** – all commands are copyable
- 🎯 **Threat matrix** – 35 threats explained with mitigations
- 💾 **Portable apps** – SimpleX, Cwtch, OnionShare, Gajim, Element, Signal, Session, Telegram (with Whonix‑compatible scripts)

---

## 📑 Table of Contents (Tabs)

| Tab | Title | Key Content |
|-----|-------|--------------|
| 0 | **Basics** | External HDD, Secure Boot, kernel parameters (dom0 and VMs), critical parameters table |
| 1 | **Network** | WISP router + Ethernet only, MAC randomisation, IPv6 disable, architecture diagrams, emergency plans |
| 2 | **Whonix Gateways** | Multiple gateways for identity separation, entry guards, bridges (obfs4, Snowflake), Tor circuit isolation |
| 3 | **Secure Storage** | LUKS2 + Argon2id, VeraCrypt, double encryption (VC+LUKS), SSD warnings, storage‑execution separation |
| 4 | **Threat Matrix** | 35 threats (timing attacks, Evil Maid, Cold Boot, fingerprinting, stylometry, etc.) with detailed mitigations |
| 5 | **Amnesic Tmpfs** | Make sensitive directories (logs, cache, /home) reside only in RAM |
| 6 | **RAM Pool** | Run entire VMs in RAM – complete deniability, all traces disappear on shutdown |
| 7 | **Advanced Security** | BadUSB, VPN+Tor, encrypted backups, dual boot warning, BusKill, self‑destruct tools, emergency plans, physical protection |
| 8 | **Kicksecure** | Browser fingerprint unification, system hardening, security‑misc, hide kernel/hardware info |
| 9 | **Live Script** | Live Mode (OverlayFS) + full comparison of all ephemeral/secure qube types (DVM, Ephemeral DVM, Amnesic Tmpfs, RAM Pool, Dom0 Live Boot, Live+RAM‑VM) |
| 10 | **Portable Apps** | SimpleX Chat (SOCKS proxy method), Cwtch, OnionShare, Gajim, Element, Signal (not recommended), Session, Telegram, metadata removal, torsocks |
| 11 | **Helper Script** | Central `auto-script.sh` that automates kernel parameters, MAC randomisation, Whonix gateways, Kicksecure, RAM Pool scripts, Amnesic Tmpfs, Live Mode, destruction tools, and LUKS hardening |

---

## 📥 Download & Usage

1. Download the HTML file:
   - English: [`q_en.html`](https://github.com/abdullah127-code/qubes-os-security-/blob/main/docs/q_en.html)
   - Arabic: [`q.html`](https://github.com/abdullah127-code/qubes-os-security-/blob/main/q.html)
2. Open it in any modern browser (Firefox, Chrome, Brave).
3. Use the tabs at the top to navigate.
4. Click on any command to copy it instantly.
5. For automation, go to **Tab 11** and use the **Helper Script**.

---

## 🌐 Live Preview

You can preview the guide directly via GitHub’s HTML Preview:

- 🔗 [**English version preview**](https://htmlpreview.github.io/?https://github.com/abdullah127-code/qubes-os-security-/blob/main/docs/q_en.html)
- 🔗 [**Arabic version preview**](https://htmlpreview.github.io/?https://github.com/abdullah127-code/qubes-os-security-/blob/main/q.html)

---

## 🔧 The Helper Script (`auto-script.sh`)

The script in **Tab 11** automates the following tasks:

- ✅ Kernel parameters for dom0 (GRUB + Secureblue sysctl)
- ✅ Kernel parameters for all VMs (kernelopts)
- ✅ MAC randomisation and IPv6 disable
- ✅ Creation of multiple Whonix gateways
- ✅ Kicksecure installation and user‑space hardening
- ✅ RAM Pool scripts (setup, single VM, multi‑VM, cleanup, status)
- ✅ Amnesic Tmpfs (apply / remove)
- ✅ Live Mode (OverlayFS) with ephemeral DVMs
- ✅ Destruction tools (BusKill, Dead Man’s Switch, immediate nuke)
- ✅ LUKS system disk hardening (PBKDF2 → Argon2id with custom memory/time)

**How to run the script after downloading:**

```bash
chmod +x auto-script.sh
./auto-script.sh
```

---

⚠️ Important Warnings

This guide is for advanced users only.

Some procedures – especially the destruction tools in Tab 7 – can cause permanent, irreversible data loss.
Always take full backups before applying any of the recommended settings.

---

🤝 Contributing

Contributions are welcome! If you find an error or have a suggestion:

· Open an Issue describing the problem.
· Submit a Pull Request with your proposed changes.
· Contact me directly via GitHub.

---

📜 License

This project is licensed under the MIT License – you are free to use, modify, and share it, provided you give appropriate credit.

See the LICENSE file for details.

---

📚 Sources & Further Reading

· Qubes OS Documentation
· Whonix Documentation
· Kicksecure Documentation
· Hitchhiker’s Guide to Online Anonymity

---

⭐ Support the Project

If you find this guide useful:

· ⭐ Star the repository
· 🔗 Share it with others
· 📢 Spread the word in privacy and security communities

---

<div align="center">

"Trust no one. Not your ISP, not your VPN provider, not the Tor network, not the operating system, not even your own computer. Trust, but verify."

</div>
