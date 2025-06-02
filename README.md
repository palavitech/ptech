# ptech

**ptech** is a lightweight, early-stage Windows command-line tool designed to analyze files and their executions.

While minimal by design, the roadmap aims to make it a helpful utility for workflows such as basic malware triage, specifically Windows-based malware.

> **Note:** This repository contains only documentation and release binaries. The source code is proprietary and not open-source at this time.

---

## ✨ Features

- Lists child processes spawn by the executable
- Lists TCP and UDP network connections (IP and Port)
- VirusTotal API Malware scan using file hash 
- Calculates and displays hashes (SHA-256 and SHA-512)
- Lists DLLs imported (import table)
- Lists basic PE-Headers 
- Outputs results in a structured, integration-ready format
- Built as a C++ console application using modular C-based DLL callbacks

---

## 📦 Download

Visit the [Releases](https://github.com/palavitech/ptech/releases/) section to download the latest version.

### Usage

```
Usage:
  ptech --analyze -p <File Path>
  ptech --virus-total -h <File Hash>
  ptech --child-processes -n <Process name>
  ptech --network-connections -n <Process name>

  ptech --help, -h
  ptech --license
  ptech --version

```

> Requires **Windows 10 or newer**. No installation required.
> For VirusTotal scans, ensure that you have obtained API key from VirusTotal. Check out the [VirusTotal documentation](https://docs.virustotal.com/reference/overview) for further details. Once you obtain the key, change the keys.txt that you see in the extracted folder and place your key there.

The placeholder looks like this. Replace this placeholder with the VirusTotal API key.
```
vt:ADD_YOUR_VIRUSTOTAL_API_KEY_HERE

```
---

## 🚧 Roadmap

- Additional features to aid malware analysis
- Structured reporting functionality

---

## 💬 A Note from the Author

This project is still in its early stages — it's intentionally minimal and will evolve over time.  
Feedback, bug reports, and use-case ideas are welcome via the Issues section or email.

---

## 🔒 License

All rights reserved. Redistribution of binaries is permitted, but modification or reverse engineering is strictly prohibited.


---

### ⚖️ Legal Disclaimer

Use this tool at your own risk. The authors and distributors of **ptech** are not liable for any damage, data loss, or consequences resulting from its use. It is intended for legitimate purposes only, such as research and internal tooling.

By using this software, you agree that you understand and accept all risks associated with its use.
