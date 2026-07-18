# Tahoe-on-Elitebook-G6
Ready made [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/) EFI files for running macOS Tahoe on HP Elitebook G6.
# Tested and succeeded on an Elitebook 830 G6 with the following specs:
- **CPU:** Intel Core i5-8365u
- **GPU:** Intel UHD Graphics 620
- **Storage:** Intel 660p 512 GB NVMe SSD
- **Networking:** Intel AX200
- *RAM(irrelevant):* 2x8 GB 2400 MHz DDR4

# What works:
- Graphics acceleration
- CPU power management (via [CPUFriend](https://github.com/acidanthera/CPUFriend/tree/master))
- Internal speakers (via [AppleHDA-back-on-macOS-26-Tahoe](https://github.com/perez987/AppleHDA-back-on-macOS-26-Tahoe))
- Sleep/Wake
- Internal camera
- Hotkeys
- Touchpad/Gestures
- Trackpoint
- Digital audio
- Wi-Fi (via [itlwm](https://github.com/OpenIntelWireless/itlwm) and [HeliPort](https://github.com/OpenIntelWireless/heliport)) **(Requires ethernet during installation)**
# What doesn't work:
- Internal microphone (will not work due to Intel's SST)
