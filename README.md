# ptech

ptech is a lightweight, early-stage Windows command-line tool designed to analyze files and generate basic insights. It uses a plugin-style DLL system to support modular functionality and is intended for internal or controlled external use. While still minimal, roadmap is to make it useful as a supporting utility in workflows such as basic malware triage.


> This repository hosts only the documentation and release binaries. The source code is proprietary and not open-source at this time.

## Features

- Calculates and reports:
  - SHA-256 hash
  - SHA-512 hash

- Outputs data in a structured format for integration or inspection
- Built as a C++ console application with modular C-based DLL callbacks

## Download

Visit the Releases section to download the latest version.
```
- Extract the ZIP
- Run from the command line:
  Usage:
    ptech --analyze <file>        Run analyze module
    ptech --help, -h              Show this help message
    ptech --license               Show license information
    ptech --version               Show version information
```
Requires Windows 10 or newer. No installation needed.


## Roadmap

- More functions that will help Malware Analysis
- Reporting

## A Note from the Author

This project is still in its early stages — it's minimal by design, and development will evolve gradually. Feedback, bug reports, and use-case ideas are always welcome through the issues section or email.

## License

All rights reserved. Redistribution of binaries is allowed, but modification or reverse engineering is not permitted.
