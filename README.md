### vxkShelby

Solo dev building small, portable Windows tools — things that fix a root
cause instead of hiding a symptom, and that run from a USB stick without
installing anything.

**Currently building:** [PortableFix](https://github.com/vxkShelby/portableFixer)
— a portable Windows 10/11 diagnostic and repair tool (Python + PySide6,
PowerShell-driven actions, dry-run by default, full undo log and audit
trail). 22 modules covering diagnostics, cleanup, repair, security and
hardware sensors.

What I care about in my own projects:
- No installer, no background services, no telemetry — copy a folder, run it, done.
- Every destructive action is reversible or backed by a restore point.
- Dry-run first, confirm before anything MODERATE or worse.

**Stack:** Python · PySide6 · PowerShell · Windows internals (WMI, DISM,
registry, BCD)

---
📫 Reach me via GitHub issues on my repos.
