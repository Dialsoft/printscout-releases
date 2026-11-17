# Print Scout

**Why won't it print?** Print Scout checks everything between the Print button and the paper on a Windows PC, explains what is wrong in plain English, and fixes the common causes with one click.

## Download

**[Download PrintScout.exe](https://raw.githubusercontent.com/Dialsoft/printscout-releases/main/PrintScout.exe)** (Windows 10 and 11, 64-bit)

One file. Nothing to install: double-click it. It keeps itself up to date.

## What it checks

- The Print Spooler service
- Every printer: paused, offline, error, driver, connection type
- Every print queue: stuck jobs
- Network printers: ping, print ports, and what the printer itself reports (paper jam, empty tray, open door, toner levels)
- Windows' own print error log

## What it fixes

Restart Spooler, Clear Stuck Jobs, printers falsely shown Offline, Use Printer Offline, paused printers, Windows changing the default printer, a missing Microsoft Print to PDF. You are always asked first, and every change is recorded in History & Undo.

Read the [User Guide](USER-GUIDE.md). 

## What's new in 1.0.0

- First release. Checks the whole printing chain on a Windows PC and explains what is wrong in plain English.
- Print Spooler check: is the service running, set to start automatically, and free of leftover job files?
- Every printer: paused, Use Printer Offline, error states, missing or generic driver, duplicate "Copy 1" printers, and the kind of connection (network address, WSD, USB, shared from another PC).
- Every print queue: finds jobs stuck on Error or Deleting, and jobs that have been waiting too long.
- Network test for network printers: name lookup, ping, print ports (9100, 515, 631) and web ports, then asks the printer itself (SNMP) about paper jams, empty trays, open doors, toner levels and page count.
- Spots the classic "shows Offline but is switched on" cause (SNMP status on the port) and fixes it with one click.
- Fix This: explains the selected problem and offers a safe one-click fix. Quick fixes for Restart Spooler, Clear Stuck Jobs and Test Page.
- Print Queue, Windows Log (Windows' own print errors) and Drivers views in the bottom list.
- History & Undo: every change Print Scout makes is recorded, and the switches it flips can be put back.
- Save Report and Copy Summary for tickets, a log file, Tools tab with shortcuts to Windows' own printer windows, expert tools (off by default), automatic updates, Share tab, and detailed tooltips on every control.

Full history: [CHANGELOG.md](CHANGELOG.md)

---
© 2026 Dialsoft LLC. All rights reserved. Built with Claude by Anthropic.
