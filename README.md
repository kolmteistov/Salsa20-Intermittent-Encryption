# Ultimate Hybrid MMF Encryption Engine (Salsa20)

![Status](https://img.shields.io/badge/Status-Coming_Soon-orange)
![License](https://img.shields.io/badge/License-Educational_Research-blue)

A high-performance Intermittent Encryption tool using **Salsa20 Cipher** and **Memory-Mapped Files (MMF)** for optimized large-file processing. Developed by **Arie Kolmteistov**.

## 🚀 Project Overview
This project implements the "Intermittent Encryption" technique—a method popularly used by modern ransomware for speed, but repurposed here for legitimate high-performance data protection. [span_0](start_span)[span_1](start_span)By encrypting strategic chunks of data instead of the whole file, it achieves **5-10x faster performance** while maintaining effective data locking[span_0](end_span)[span_1](end_span).

### Key Features:
* **[span_2](start_span)[span_3](start_span)Salsa20 Stream Cipher:** Fast and secure software-based encryption[span_2](end_span)[span_3](end_span).
* **[span_4](start_span)[span_5](start_span)Memory-Mapped Files:** Efficiently process 100GB+ files with minimal RAM usage[span_4](end_span)[span_5](end_span).
* **[span_6](start_span)[span_7](start_span)Adaptive Parameters:** Encryption patterns that adapt to file types (.txt, .mp4, .db)[span_6](end_span)[span_7](end_span).
* **[span_8](start_span)[span_9](start_span)Deterministic Jumps:** Using LCG for reproducible encryption patterns during decryption[span_8](end_span)[span_9](end_span).

## 📄 Documentation
While the source code is being finalized for public release, you can explore the technical depth of this project through the whitepaper and video demonstrations below:

> [!NOTE]
> The whitepaper is currently available in **Bahasa Indonesia**. An English version is in development and will be released soon.

* **[span_0](start_span)[Download Whitepaper PDF (Indonesian)](./Salsa20_Intermittent_Encryption_MMF_Whitepaper.pdf)**[span_0](end_span) - Full technical deep dive, entropy analysis, and bug reports.
* **[Watch Video Demonstration](https://youtu.be/Gyy9IY70Zr0)** - See the engine in action (Intermittent patterns & performance benchmarks).


## 🛠 Tech Stack
* **[span_12](start_span)Language:** C# (.NET Core 6.0+)[span_12](end_span)
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
