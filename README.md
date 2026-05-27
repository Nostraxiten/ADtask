# ADTask — Intelligent Process Manager for Windows
 
> Kill what's wasting resources. Keep what matters.
 
---
 
## What is this?

<img width="700" height="529" alt="Captura de pantalla 2026-05-27 165530" src="https://github.com/user-attachments/assets/5065b3b4-a572-4b07-855f-2b51c9dc81d9" />
 
**ADTask** is a Windows executable (.exe) designed to free up CPU and RAM quickly and safely. Built for users who want full control over their system processes, either manually with detailed information, or by letting the smart cleanup engine handle everything automatically.
 
No installation. No dependencies. Just double-click and run.
 
---
 
## Features
 
### Mode 1 — Manual Termination with Explanation
- Lists all active system processes in real time.
- Displays for each process:
  - Executable name
  - Human-readable description (what it is and what it does)
  - Current CPU and RAM usage
  - Status: active / suspended / background
- The user decides which processes to kill individually and with full knowledge.
- Perfect for users who want to know exactly what they are terminating.
---
 
### Mode 2 — Smart Cleanup (Smart Kill)
- Automatically analyzes all running processes.
- Classifies and terminates processes based on safety and efficiency criteria:
  - Malicious or suspicious processes detected by known patterns.
  - Idle processes consuming resources without active use.
  - Non-critical processes such as browsers, secondary applications, and optional services.
- Never touches essential operating system processes:
  - `explorer.exe`, `svchost.exe`, `lsass.exe`, `winlogon.exe`, and similar.
- Result: significant reduction in CPU and RAM usage within seconds.
---
 
## Security
 
- The program does not modify any system files — it only manages running processes.
- The protected process list is built directly into the executable.
- Smart Kill applies a whitelist logic: everything critical is excluded by default.
- Running as **Administrator** is recommended for full access to all processes.
---
 
## Requirements
 
| Component | Minimum Requirement |
|---|---|
| Operating System | Windows 10 / 11 |
| Permissions | Administrator (recommended) |
| Installation | None |
| Dependencies | None |
 
---
 
## Usage
 
1. Download the `.exe` file from the [Releases](../../releases) section.
2. Right-click and select **Run as administrator**.
3. Choose your mode:
   - `[1]` Manual termination with explanation
   - `[2]` Smart automatic cleanup
4. Follow the on-screen instructions.
---
 
## Author
 
**Nox** · [@nostraxiten](https://github.com/nostraxiten)
