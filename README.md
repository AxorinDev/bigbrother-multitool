<div align="center">

# ❄️ POLARIS 🏔️

### *Cold sky. Sharp tools. Follow the light.*

**A modular terminal toolkit for Discord automation, OSINT research, and offensive security testing.**

*Private build - not for distribution. May be released publicly in the future.*

<br>

![status](https://img.shields.io/badge/status-private-374151?style=for-the-badge)
![version](https://img.shields.io/badge/version-2.7.1-0ea5e9?style=for-the-badge)
![modules](https://img.shields.io/badge/modules-130%2B-22d3ee?style=for-the-badge)
![themes](https://img.shields.io/badge/themes-13-6d28d9?style=for-the-badge)
![python](https://img.shields.io/badge/python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![platform](https://img.shields.io/badge/platform-win%20%7C%20mac%20%7C%20linux-22d3ee?style=for-the-badge)

<br>

## 🧭 Navigate

**[At a Glance](#s-glance)** &nbsp;·&nbsp; **[Overview](#s-overview)** &nbsp;·&nbsp; **[Use Cases](#s-use)** &nbsp;·&nbsp; **[Why Polaris](#s-why)** &nbsp;·&nbsp; **[Modules](#s-modules)**  
**[Themes](#s-themes)** &nbsp;·&nbsp; **[Tech Stack](#s-stack)** &nbsp;·&nbsp; **[Roadmap](#s-roadmap)** &nbsp;·&nbsp; **[What's New](#s-new)** &nbsp;·&nbsp; **[Release Plan](#s-release)**  
**[FAQ](#s-faq)** &nbsp;·&nbsp; **[Community](#s-comm)** &nbsp;·&nbsp; **[Support](#s-support)** &nbsp;·&nbsp; **[Credits](#s-credits)**

</div>

---

> [!TIP]
> **Just want a public, working tool?** Use **[Navi](https://github.com/glockinhand/navi-multitool)** - the original, stable, actively maintained version.

> [!WARNING]
> **Private use only.** Never target systems, accounts, or networks you don't own or have explicit written permission to test.

---

<a id="s-glance"></a>

<div align="center">

## 📌 At a Glance

| 130+ | 13 | 9 | 3 |
|:---:|:---:|:---:|:---:|
| **Modules** | **Themes** | **Categories** | **Platforms** |

`v2.7.1` · Python 3.9+ · Terminal-first · 🔒 Private build

</div>

---

<a id="s-overview"></a>

<div align="center">

## 💻 Overview

Polaris is a single-application toolkit that lives entirely in the terminal. Every module sits behind a **paginated dashboard** - open the tool, pick a number, get your result. No GUI clutter, no browser tabs, no background services, no config files to hand-edit.

Under the hood it runs a **plugin-style module loader** - drop a new file into `modules/` and it's live on the next launch. Dependencies **self-install on first run**, so the only setup step is `python main.py`.

The interface ships with **13 switchable themes**, hot-swappable from the config menu. Every module shares the same input grammar, output style, and error handling - one learning curve, one hundred and thirty tools.

**One command to launch. One dashboard to master.**

</div>

---

<a id="s-use"></a>

<div align="center">

## 🎯 Use Cases

| | |
|:---:|:---|
| **Payload Suite** | Authorized pentesting, lab work, and adversary simulation. |
| **OSINT Researchers** | Passive recon, public-record aggregation, metadata forensics. |
| **Server Admins** | Bulk Discord management from one place. |
| **Security Students** | Learn tooling patterns without setting up ten dependencies. |
| **Automation Nerds** | Chain modules into repeatable workflows. |

</div>

---

<a id="s-why"></a>

<div align="center">

## ⚡️ Why Polaris

Built on the [Navi](https://github.com/glockinhand/navi-multitool) foundation, extended for daily use.

| Feature | Polaris | Navi |
|:---|:---:|:---:|
| Modules | **130+** | ~40 |
| Themes | **13** | 9 |
| Dashboard | Paginated | Linear |
| Plugin Loader | ✅ | ❌ |
| Self-bootstrapping | ✅ | ❌ |
| Reworked RAT | ✅ | — |
| Networking Suite | ✅ | ❌ |
| Automation Suite | ✅ | ❌ |

</div>

---

<a id="s-modules"></a>

<div align="center">

## 🗂 Modules

### 🤖 Discord Automation

| Module | Description |
|:---|:---|
| **Webhook Manager** | Bulk-send, rotate, and clean up webhooks. |
| **Account Tools** | Token inspection and session management. |
| **Username Checker** | Multi-threaded handle availability sweeps. |
| **Server Auditor** | Structure export and permission mapping. |
| **Nitro Generator** | High-speed code generation and validation. |
| **Selfbot Utilities** | Presence automation and DM tooling. |
| **Bot Framework** | Configurable runner via `core/botcfg.json`. |
| **Nuke Bot** | `.kill`, `.massban`, `.erase` console bot. |
| **DM Logger** | Message logging from owned accounts. |
| **Reaction Roles** | Auto-role from message reactions. |
| **Auto-Responder** | Keyword-triggered replies. |
| **Guild Backup** | Server snapshot + restore. |
| **Server Joiner** | Bulk-join from invite list. |
| **Invite Tracker** | Per-code join tracking. |
| **Channel Cloner** | Replicate channel trees. |
| **Role Manager** | Bulk role create / edit / assign. |
| **Soundboard Manager** | Bulk soundboard upload. |
| **Emoji Stealer** | Rip emojis from any server. |
| **Sticker Downloader** | Bulk sticker grab. |
| **Server Statistics** | Member, message, and activity stats. |

### 🔎 OSINT & Research

| Module | Description |
|:---|:---|
| **Network Recon** | Port scanner, WHOIS, recursive DNS. |
| **Subdomain Enumerator** | Passive subdomain discovery. |
| **Person of Interest** | Public-record aggregation. |
| **Metadata Extraction** | EXIF, audio tags, doc properties. |
| **Email Header Analyzer** | SPF, DKIM, DMARC chain analysis. |
| **Favicon Hash Lookup** | Fingerprint origin infrastructure. |
| **Google Dork Builder** | Prebuilt query generator. |
| **IP Utilities** | Grabber + latency pinger. |
| **Reverse Image Lookup** | Multi-engine image tracing. |
| **Username Enumerator** | Handles across 40+ platforms. |
| **Breach Checker** | Public breach dataset cross-ref. |
| **ASN Lookup** | Autonomous system mapping. |
| **Social Scanner** | Public profile aggregation. |
| **Domain Age Checker** | Registration + WHOIS history. |
| **Cert Transparency** | CT log certificate search. |
| **GitHub Recon** | Public repo and contributor scan. |
| **Email Verifier** | SMTP-level address validation. |
| **Name Variant Generator** | Alternate handle combinations. |

### 👾 Exploitation Suite

| Module | Description |
|:---|:---|
| **Reworked Navi RAT** | Rebuilt from the original Navi Discord RAT — stability patches, cleaner PyQt5 GUI, reduced AV false positives. |
| **Recovery Tool** | Browser data and token extraction GUI. |
| **Crypto Clipper** | Cryptocurrency address redirection. |
| **Keylogger** | Background input recording. |
| **SQL Scanner** | Automated vulnerability detection. |
| **Email Bomber** | High-volume mail stress testing. |
| **Brute Forcer** | Credential attack automation. |
| **Website Cloner** | Local cloning of any site. |
| **Persistence Module** | Registry / scheduled task autostart. |
| **UAC Bypass** | Privilege escalation wrapper. |
| **Screen Capture** | Silent screen + webcam snapshot. |
| **Process Watcher** | Detects target application launches. |
| **DLL Injector** | Attach compiled DLL to a process. |
| **Shellcode Encoder** | Staged payload encoder. |
| **USB Dropper** | Payload trigger on USB insert. |
| **Reverse Shell Builder** | Listener + client pair generator. |
| **Wi-Fi Credential Reader** | Saved network password dump. |
| **Browser History Extractor** | Chromium / Firefox history pull. |
| **Scheduled Task Creator** | Silent scheduled execution setup. |
| **Token Grabber Builder** | Discord token capture stub. |

### 🔐 Security & Utilities

| Module | Description |
|:---|:---|
| **Obfuscator V2** | Python obfuscation with XOR + anti-print. |
| **Hash Verifier** | MD5, SHA1, SHA256 generation. |
| **Cryptography** | Base64 codec + password generator. |
| **Password Strength Analyzer** | Entropy scoring and feedback. |
| **Proxy Tools** | Scraper + concurrent validity checker. |
| **Wallet Scanner** | Crypto address detection. |
| **QR Generator** | Custom QR creation. |
| **Encoder Suite** | Base32 / Base64 / Hex / URL / HTML entities. |
| **Wordlist Generator** | Rule-based password list builder. |
| **SSL Inspector** | Certificate chain analysis. |
| **Subnet Calculator** | IPv4 / IPv6 range and mask. |
| **PE Inspector** | Executable header and section analysis. |
| **File Analyzer** | Type detection + magic bytes + entropy. |
| **Steganography Tool** | Hide / extract data in images and audio. |
| **JWT Decoder** | Decode and inspect JSON web tokens. |
| **UUID Generator** | Bulk v1 / v4 creation. |
| **Timestamp Converter** | Unix / ISO / local time conversion. |
| **Entropy Checker** | Randomness measurement. |
| **XOR Cipher** | Reversible byte-level XOR tool. |
| **ROT13 / Caesar** | Classic rotation ciphers. |
| **Unicode Inspector** | Codepoint and byte dump. |
| **Bcrypt Verifier** | Hash compare and cost inspection. |

### 📊 Roblox Analytics

| Module | Description |
|:---|:---|
| **Lookup** | User, group, cookie data. |
| **Account Tools** | Cookie refresh + login utilities. |
| **Asset Downloader** | Bulk public asset retrieval. |
| **Username History** | Name change tracking. |
| **Bulk Username Checker** | Availability at scale. |
| **Trade Scanner** | Public trade history aggregation. |
| **Limited Checker** | Limited item + resale monitoring. |
| **Group Joiner** | Bulk-join with rate limiting. |
| **Cookie Validator** | Batch cookie validity check. |
| **Server Locator** | Find game instances by ID. |

### 🌐 Networking

| Module | Description |
|:---|:---|
| **Port Scanner** | Multi-threaded TCP sweep + service detect. |
| **Network Mapper** | Local subnet discovery. |
| **ARP Scanner** | Identify local segment devices. |
| **Packet Sniffer** | Lightweight traffic capture. |
| **Speed Tester** | Upload / download benchmarking. |
| **Traceroute** | Hop-by-hop latency analysis. |
| **HTTP Header Viewer** | Full response header dump. |
| **Ping Sweeper** | Fast ICMP sweep across CIDR. |
| **Wi-Fi Scanner** | Nearby network enumeration. |
| **Route Table Viewer** | Local routing table dump. |

### ⚙️ Automation & Scripting

| Module | Description |
|:---|:---|
| **Macro Recorder** | Record and replay input sequences. |
| **Task Scheduler** | Cron-style local job runner. |
| **Hotkey Binder** | Bind global hotkeys to scripts. |
| **Clipboard Manager** | History + search for clipboard. |
| **File Watcher** | Trigger actions on file changes. |
| **Batch Renamer** | Rule-based bulk file rename. |
| **Text Transformer** | Regex pipelines on files. |
| **Script Runner** | Chain modules into sequences. |

### 🎭 Simulation Suite

| Scenario | Description |
|:---|:---|
| **Fake Ransomware** | Full-screen ransom note animation. |
| **Fake Miner** | Fake crypto mining screen. |
| **Fake DDoS** | Terminal-style attack simulation. |
| **Fake PayPal OTP** | Payment verification screen. |
| **Fake Hacker Typer** | Classic keyboard-mash typer. |
| **Fake System Wipe** | Progress-bar wipe animation. |
| **Fake Blue Screen** | Full-screen BSOD mock. |
| **Fake Update Loop** | Endless Windows update screen. |
| **Fake Error Wall** | Cascading system error windows. |
| **Fake Network Scan** | IP-by-IP scan animation. |
| **Fake Bitcoin Tracker** | Live wallet tracker prop. |
| **Fake Terminal Chat** | Scripted chat typer. |
| **Fake Password Crack** | Decrypt animation. |
| **Fake Antivirus Scan** | Scan progress with fake threats. |
| **Fake Bank Transfer** | Payment screen prop. |
| **Fake Crypto Transfer** | Wallet send-screen prop. |
| **Fake System Report** | Diagnostic report typer. |
| **Fake Data Leak** | Leaked file list animation. |
| **Fake Login Screen** | OS login overlay mock. |
| **Fake Camera Feed** | CCTV-style static loop. |
| **Fake GPS Tracker** | Moving map animation. |
| **Fake Chat Popup** | Rolling chat notification spam. |
| **Fake Driver Update** | Hardware driver install loop. |
| **Fake Network Warning** | Full-screen network error prop. |
| **Fake Disk Cleanup** | Windows cleanup animation. |
| **Fake Registry Edit** | Progress-bar registry tool. |
| **Fake BIOS Flash** | Firmware update prop. |
| **Fake Kernel Panic** | Linux-style panic screen. |

</div>

---

<a id="s-themes"></a>

<div align="center">

## 🎨 Themes

Thirteen palettes, switchable from the config menu with a single keystroke.

**Signature** — `Polaris`  
**Modern** — `Modern` · `Modern Red` · `Modern Purple`  
**Classic** — `Blue` · `Red` · `Purple` · `Green` · `Yellow` · `Pink` · `Cyan` · `Gray`  
**Experimental** — `Rainbow`

</div>

---

<a id="s-stack"></a>

<div align="center">

## 🛠 Tech Stack

| | |
|:---:|:---|
| **Language** | Python 3.9+ |
| **Interface** | Native terminal (ANSI + Unicode) |
| **GUI Modules** | PyQt5 (builders only) |
| **HTTP** | `requests` + `websocket-client` |
| **Browser Automation** | `selenium` |
| **Media Metadata** | `piexif`, `exifread`, `mutagen` |
| **Styling** | `pystyle` |
| **Dependencies** | Auto-installed on first run |

</div>

---

<a id="s-roadmap"></a>

<div align="center">

## 🗺 Roadmap

**Legend:** ✅ Done · 🚧 In Progress · 📅 Planned

✅ Paginated dashboard architecture  
✅ 13-theme engine  
✅ Discord automation suite  
✅ OSINT module set  
✅ Reworked Navi RAT + builders  
✅ Roblox toolkit  
✅ Networking suite  
✅ Automation suite  
✅ Simulation suite  
🚧 Plugin API for third-party modules  
📅 Web dashboard companion  
📅 Community release (TBD)

</div>

---

<a id="s-new"></a>

<div align="center">

## 🆕 What's New in v2.7.1

- **10 new modules** across Networking and Automation
- **Reworked Navi RAT** with reduced AV false positives
- **13-theme engine** — added Modern Red and Modern Purple
- **Self-bootstrapping dependencies**
- **Plugin-style loader**
- **Rebuilt config system** with safer defaults
- **Removed** 3 unstable legacy modules

</div>

---

<a id="s-release"></a>

<div align="center">

## 📢 Release Plan

Polaris is currently a **private build**. A public release is being considered but **no ETA is set**.

**If** it goes public:

- **Core framework** and most modules will be **free**
- **Advanced modules** (premium builders, extended OSINT, priority updates) will likely be **paid**
- Pricing tiers, licensing, and packaging are **not finalised**
- No official store, no pre-orders, no keys exist yet — anything claiming otherwise is fake

</div>

---

<a id="s-faq"></a>

<div align="center">

## ❓ FAQ

**Can I download Polaris?**  
Not yet. Private build, no release scheduled.

**Is it going to be free?**  
If released, core is free with some advanced modules paid.

**Where do I get the source?**  
You don't. For a public, working version of this kind of tool, use [Navi](https://github.com/glockinhand/navi-multitool).

**What's different from Navi?**  
See the [comparison table](#s-why) above.

**Is this legal?**  
For authorized testing and educational research only.

**Why "Polaris"?**  
The North Star. Guidance when the sky goes dark.

**Why "reworked" RAT?**  
The Discord RAT is a stability and UI rework of the original Navi RAT.

**Will there be a GUI?**  
No. Polaris is terminal-first. A web companion is on the roadmap.

**Apple Silicon?**  
Yes. Runs natively under Python 3.9+.

**Update cadence?**  
Internally, weekly. No public changelog cadence yet.

</div>

---

<a id="s-comm"></a>

<div align="center">

## 🌐 Community

Polaris doesn't have a public community yet. When the project moves toward release:

- A Discord server will be opened for updates and support
- A public issue tracker will be enabled
- Documentation site will be launched

Until then, this repo is the single source of truth.

</div>

---

<a id="s-support"></a>

<div align="center">

## 💖 Support

Polaris is a personal project. There's no monetisation, no sponsor page, and no donation link.

If you want to show support when it's public:

- ⭐ **Star the repo** — the only metric that matters to a solo dev
- 🐛 **Report bugs** — will open once a public tracker exists
- 📣 **Share it** — once there's something to share

</div>

---

<a id="s-credits"></a>

<div align="center">

## 💙 Credits

Built on the open-source **[Navi Multitool](https://github.com/glockinhand/navi-multitool)** by **[glockinhand](https://github.com/glockinhand)**.

The Polaris Discord RAT is a rework of the original Navi RAT — stability and UI improvements only, same foundation.

Big respect to the original author for open-sourcing the base.

---

### ❄️ 🏔️ ❄️

*Cold sky. Sharp tools. Follow the light.*

`Polaris v2.7.1 · Private Build`

</div>
