# Bash Automation Toolkit

A personal collection of Bash scripts focused on Linux automation, system administration, and scripting practice.

This project serves as:
- A reusable script library
- A Bash learning environment
- A toolkit for daily Linux tasks

## 1. Structure

```
bash-automation-toolkit/
│
├── basics/ # Basic Bash scripts
├── system/ # System administration utilities
├── network/ # Networking and diagnostics tools
├── automation/ # Task automation scripts
├── utils/ # Miscellaneous utilities
└── README.md
```

## 2. Usage

Make a script executable:

```bash
chmod +x script.sh
```
Run it:
```
./script.sh
```
## 3. Purpose

To improve Bash scripting skills while building a practical set of reusable tools for Linux environments.

Example Script
```
#!/bin/bash

echo "System: $(uname -a)"
echo "User: $USER"
echo "Date: $(date)"
```
## 4. Notes
Scripts are kept simple and well-documented.
Focus on learning and practical automation.
The repository will grow over time with new utilities.
