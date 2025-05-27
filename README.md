# ptech

**ptech** is a lightweight, early-stage Windows command-line tool designed to analyze files and generate basic insights such as cryptographic hashes. It uses a plugin-style DLL system to support modular functionality and is intended for internal or controlled external use.

> 🔒 This repository hosts only the **documentation** and **release binaries**. The source code is proprietary and not open-source at this time.

---

## ⚙️ Features

- Calculates and reports:
  - SHA-256 hash
  - SHA-512 hash
- Uses `Analyze.dll` to decouple logic from the main executable
- Outputs data in a structured format for integration or inspection
- Built as a C++ console application with modular C-based DLL callbacks

---

## 📦 Download

Visit the [**Releases**](https://github.com/your-username/your-public-repo/releases) section to download the latest version.

- Extract the ZIP
- Run from the command line:
  ```cmd
  ptech.exe <path-to-file>
