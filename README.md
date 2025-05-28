# ptech

**ptech** is a lightweight, early-stage Windows command-line tool designed to analyze files and generate basic insights. It uses a plugin-style DLL system for modular functionality and is intended for internal use or controlled external distribution.

While minimal by design, the roadmap aims to make it a helpful utility for workflows such as basic malware triage.

> **Note:** This repository contains only documentation and release binaries. The source code is proprietary and not open-source at this time.

---

## ✨ Features

- Calculates and displays:
  - SHA-256 hash
  - SHA-512 hash
- Outputs results in a structured, integration-ready format
- Built as a C++ console application using modular C-based DLL callbacks

---

## 📦 Download

Visit the [Releases](#) section to download the latest version.

### Usage

```bash
# Extract the ZIP and run from the command line:
ptech --analyze <file>       # Analyze a file
ptech --help or -h           # Display help
ptech --license              # View license information
ptech --version              # Show version
```

> Requires **Windows 10 or newer**. No installation required.

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
