---
title: 0xC1900101 – 0x20017 Windows 10 error
date: 2021-04-26 13:00:00 +0000
categories: [Windows Update]
tags: [windows update]   # TAG names should always be lowercase
---




This is about the infamous error you get when trying to install Windows updates or specifically to Win 10 20H2:


```
0xC1900101 – 0x20017 Windows 10 error

Installation failed in SAFE_OS phase with an error during BOOT operation, 0xC1900101 – 0x20017
```

You probably tried all kinds of things that didn’t work:

- DISm
- SFC
- Clean Boot
- Uninstalled anti virus
- Removed all peripheral devices
- Updated drivers
- chkdsk
- Disabled BIOS settings
- Ran troubleshooter for Windows Update
- Tried installing another version of Windows

The fix, especially if you’re on an older **AMD** motherboard (say around 2018), is likely:

# Outdated BIOS firmware

I know, it sounds crazy but give it a try. I couldn’t update Windows to version 20H2 but as soon as I updated my BIOS firmware, it worked.
