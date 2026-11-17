# Print Scout release notes

## 1.1.0 (2026-11-17)
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

## 1.0.0 (2026-11-17)
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
