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
- Every printer's IP address, MAC address, host name, model, driver language, date and version
- Find Printers: every printer on the network, installed or not, and printers that moved to a new address
- Windows' own print logs, including the detailed log that records every job

## What it fixes

Restart Spooler, Clear Stuck Jobs, printers falsely shown Offline, Use Printer Offline, paused printers, Windows changing the default printer, a missing Microsoft Print to PDF. You are always asked first, and every change is recorded in History & Undo.

Read the [User Guide](USER-GUIDE.md). 

## What's new in 1.1.0

- Every printer now shows its IP address, MAC address and host name, its model, and its driver's printer language (PCL 6, PostScript and so on), date and version.
- New Find Printers (Home tab): searches the network for every printer, installed on this PC or not, and lists each one's IP address, MAC address, host name, model, serial number and print ports in the new Network Printers view.
- Moved printers: when a network printer stops answering, Print Scout searches the network and recognizes it at its new address by its MAC address or serial number. Fix This points Windows at the new address (undo from History & Undo).
- "Driver is unavailable": spots printers whose driver files are missing.
- New Find Driver (Tools tab, and Fix This for driver problems): works out the maker and model and searches the maker's own website for the driver.
- New Driver Types guide (Help tab): PCL 6, PCL 5, PostScript, XPS/v4, UFR II, host-based, dot matrix and label printers explained in plain English, plus Type 3 vs Type 4 and universal drivers.
- Windows' detailed print log (PrintService/Operational): Print Scout tells you when it is off, switches it on with one click, and shows every job from it in the Windows Log view next to the errors.
- Warns when Print Scout runs as SYSTEM (for example from ScreenConnect Backstage or an RMM script) or as a different user than the person signed in, because their own printers are invisible to other accounts.
- After Restart Spooler or Clear Stuck Jobs, offers a test page to prove printing works.
- Tools tab: new Devices & Printers and Add a Printer buttons. Open Log File moved to the Home tab.

Full history: [CHANGELOG.md](CHANGELOG.md)

---
© 2026 Dialsoft LLC. All rights reserved. Built with Claude by Anthropic.
