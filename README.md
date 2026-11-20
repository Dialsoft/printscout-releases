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
- Test Pages: Print Scout's own test page, a color test pattern and a color calibration check page, plus Color Help for faded, missing or tinted colors
- Windows' own print logs, including the detailed log that records every job

## What it fixes

Restart Spooler, Clear Stuck Jobs, printers falsely shown Offline, Use Printer Offline, paused printers, Windows changing the default printer, a missing Microsoft Print to PDF. You are always asked first, and every change is recorded in History & Undo.

Read the [User Guide](USER-GUIDE.md). 

## What's new in 1.2.0

- New Test Pages window (Home tab, Test Pages): pick a printer and print Print Scout's own pages, with a preview of each.
- Print Scout test page (black and white): the printer, driver, language, port, network address and PC it came from, gray steps, line widths, text sizes and a 6-inch ruler to catch shrunk pages.
- Color test pattern: each toner on its own, two-toner mixes, 10%-100% steps of every toner, neutral grays, smooth blends, color boxes inside black outlines to check the colors line up, and everyday colors. Notes on the page say what each part should look like.
- Color calibration check page: 24 reference color patches, the lightest and darkest steps of every toner and a checklist of what each fault looks like. Print it before and after the printer's own Color Calibration.
- "Print in color" option prints the color pages in color even when the driver is set to grayscale.
- New Color Help: pick what you see (faded, a color missing, a tint, colored edges, black and white only, streaks, different from the screen, dark photos) and Print Scout explains the likely causes and what to do, with the exact Color Calibration steps for HP Color LaserJet printers.
- New check: a color printer whose driver is set to print in black and white. New note when a color toner the printer reports is low.

Full history: [CHANGELOG.md](CHANGELOG.md)

---
© 2026 Dialsoft LLC. All rights reserved. Built with Claude by Anthropic.
