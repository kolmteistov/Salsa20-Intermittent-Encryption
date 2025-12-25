# Ultimate Hybrid MMF Encryption Engine (Salsa20)

![Status](https://img.shields.io/badge/Status-Coming_Soon-orange)
![License](https://img.shields.io/badge/License-Educational_Research-blue)

A high-performance Intermittent Encryption tool using **Salsa20 Cipher** and **Memory-Mapped Files (MMF)** for optimized large-file processing. **Developed by Arie Kolmteistov & Independent Research Team.**

## 🚀 Project Overview
This project implements the "Intermittent Encryption" technique—a method popularly used by modern ransomware for speed, but repurposed here for legitimate high-performance data protection. By encrypting strategic chunks of data instead of the whole file, it achieves **5-10x faster performance** while maintaining effective data locking.

Author's Note:
Since my Old PC broke down a few months ago, I had to complete this entire project and documentation using only my smartphone (via Termux/Android environment). I apologize for any shortcomings in the documentation, formatting, or writing quality. I'm doing my best with the limited resources I have.

Security Background & Account History:
You might notice this GitHub account is relatively new. In January 2024, my previous workstation was compromised by an Infostealer malware, which led to the loss of my original credentials and forced me to migrate my research to this new environment. This incident, combined with my old primary PC failure, is why I am currently finalizing and documenting this long-term research from a mobile device.

## 🛠 Key Features
* **Salsa20 Stream Cipher:** Fast and secure software-based encryption.
* **Memory-Mapped Files:** Efficiently process large files with minimal RAM usage.
* **Adaptive Parameters:** Encryption patterns that adapt to file types (.txt, .mp4, .db).
* **Deterministic Jumps:** Using LCG for reproducible encryption patterns during decryption.

## 📄 Documentation
While the source code is being finalized for public release, you can explore the technical depth of this project through the whitepaper and video demonstrations below:

> [!NOTE]
> The whitepaper is currently available in **Bahasa Indonesia**. An English version is in development and will be released soon.

* **[Download Whitepaper PDF (Indonesian)](./Salsa20_Intermittent_Encryption_MMF_Whitepaper.pdf)** - Full technical deep dive, entropy analysis, and bug reports.
* **[Watch Video Demonstration](https://youtu.be/Gyy9IY70Zr0)** - See the engine in action.

## ⚙️ Tech Stack
* **Language:** C# (.NET Core 6.0+)
* **Environment:** Developed & Tested on Android (Termux/Ubuntu PRoot) & Linux.

## 📅 Release Roadmap
- [x] Research & Algorithm Implementation (Salsa20)
- [x] Intermittent Pattern Logic (LCG)
- [x] Memory-Mapped Files Integration
- [x] Whitepaper & Documentation
- [ ] Windows Compatibility Testing (In Progress)
- [ ] Public Source Code Release

---
*Disclaimer: This project is for educational and research purposes only.*
© 2016-2025 Arie Kolmteistov.
