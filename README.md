# Wireless-Hacking-Dr.Dabash
The Ultimate Wireless Penetration Testing Compendium by Dr. Dabash — Interactive Dark-Neon HTML Command Cheat Sheet &amp; Condensed PDF Playbooks covering WEP, WPA2/WPA3 (SAE/OWE), WPS, 802.1X Enterprise, and Rogue AP (Evil Twin) operations.
<div align="center">
  
# 📡 Wireless Hacking Compendium | عصارة اختراق الشبكات اللاسلكية
### **By Dr. Dabash (دكتور ضبش)**

[![Red Teaming](https://img.shields.io/badge/Focus-Wireless%20Pentesting%20%26%20Red%20Teaming-red?style=for-the-badge)](#)
[![Interactive HTML](https://img.shields.io/badge/Artifact-Interactive%20HTML%20Cheat%20Sheet-00ffff?style=for-the-badge)](#)
[![PDF Playbook](https://img.shields.io/badge/Guide-Condensed%20PDF%20Summary-ff0055?style=for-the-badge)](#)

> **"No fluff, no filler—just pure offensive wireless tradecraft, ready-to-fire commands, and battle-tested attack methodologies."**

</div>

---

## 🎯 Overview | نبذة عن المستودع
Welcome to the **Wireless Hacking Compendium** by **Dr. Dabash**. This repository is the distilled essence (الخلاصة والعصارة) of modern Wi-Fi Penetration Testing and Wireless Red Teaming. It is engineered for penetration testers, Red Team operators, and certification candidates (**OSWP, HTB CWPE, CWP**) who need instant access to structured workflows, exact CLI syntax, and deep protocol exploitation steps without digging through hundreds of pages.

يجمع هذا المستودع خلاصة وتجارب اختراق الشبكات اللاسلكية من الصفر وحتى بيئات الشركات المتقدمة (Enterprise)، مصممة في شكل **أداة HTML تفاعلية** سريعة للنسخ الفوري أثناء العمليات، مع **ملخصات PDF مركزة** تشرح المنهجية والسيناريوهات خطوة بخطوة.

---

## 📦 What's Inside? | محتويات المستودع

### 1. ⚡ Interactive HTML Command Cheat Sheet (`index.html`)
A custom-built, dark-themed, neon-styled interactive web utility designed for offensive operations:
* **One-Click Copy-to-Clipboard:** Instant command execution readiness during live engagements and timed exams.
* **Collapsible Technical Breakdowns:** Expandable notes explaining flags, edge cases, and troubleshooting tips.
* **Categorized Attack Phases:** Structured linearly from Adapter Prep & Recon to Post-Connection Pivoting.

### 2. 📄 The Wireless Hacking PDF Playbooks (`/PDFs`)
Condensed, visual field manuals summarizing the core 20% of techniques that yield 80% of wireless compromises:
* Protocol mechanics, frame structures (Management, Control, Data), and 4-Way Handshake internals.
* Mind maps and decision trees for choosing the right attack vector based on target AP security posture.

---

## 🛡️ Covered Attack Vectors | مسارات الهجوم المغطاة

* **🔧 Wireless Interface & Recon Mastery**
  * Monitor Mode configuration, MAC spoofing, channel hopping, and hidden SSID decloaking (`airmon-ng`, `iw`, `airodump-ng`, `kismet`).
* **🔓 Legacy & Protocol Flaws (WEP & WPS)**
  * WEP Shared Key/Open System exploitation, ARP Replay, ChopChop, and Fragmentation attacks.
  * WPS Pixie-Dust offline cracking and PIN brute-forcing (`reaver`, `bully`, `oneshot`).
* **🔑 WPA / WPA2-Personal (PSK) Auditing**
  * Targeted Deauthentication & Disassociation (`aireplay-ng`, `mdk4`).
  * Client-less **PMKID** harvesting (`hcxdumptool`, `hcxpcapngtool`).
  * High-speed GPU offline cracking workflows, custom rulesets, and mask attacks (`hashcat`, `aircrack-ng`).
* **🌐 Modern WPA3 (SAE & OWE) Exploitation**
  * Simultaneous Authentication of Equals (SAE) transition mode downgrade attacks.
  * Dragonblood concepts, timing/dictionary constraints, and Opportunistic Wireless Encryption (OWE) auditing.
* **🏢 WPA2 / WPA3-Enterprise (802.1X / MGT)**
  * Auditing EAP-PEAP, EAP-TTLS, and EAP-TLS infrastructures.
  * Certificate validation bypass, radius relay, and capturing **MSCHAPv2 / NetNTLMv2** challenges (`hostapd-wpe`, `eaphammer`, `asleap`).
* **🎭 Advanced Rogue AP, Evil Twin & Captive Portals**
  * Automated & manual Evil Twin deployment (`airgeddon`, `wifiphisher`, custom `dnsmasq` + `hostapd` setups).
  * Captive Portal credential harvesting and client hijacking (MAC/IP spoofing to bypass portal authentication).

---

## 🛠️ Core Arsenal | الأدوات المستخدمة
`Aircrack-ng Suite` • `Airgeddon` • `Hashcat` • `hcxdumptool` • `Hostapd-wpe` • `Eaphammer` • `Reaver` • `mdk4` • `wpa_supplicant` • `Bettercap` • `Wireshark`

---

## 🚀 Quick Usage | طريقة التشغيل

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/Wireless-Hacking-Compendium.git
   cd Wireless-Hacking-Compendium
