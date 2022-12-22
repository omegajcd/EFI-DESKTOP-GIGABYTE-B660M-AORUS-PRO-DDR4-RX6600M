# EFI-DESKTOP-GIGABYTE-B660M-AORUS-PRO-DDR4-RX6600M

## Gigabyte Aorus PRO DDR4 i5 12600K + RX6600M + Fenvi T919 bcm94360

**Latest working macOS**: 13.1
<br>

**Current OpenCore**: 0.8.7

## Complete hardware specs
- Intel i5 12600K
- Gigabyte B660M Aorus Pro DDR4 (https://www.gigabyte.com/br/Motherboard/B660M-AORUS-PRO-rev-10#kf)
- RX 6600M 
- 2x 16Gb DDR4 3200Mhz Kingston Fury Beast with XMP Enabled
- Wifi/BT replaced by FFenvi T919 bcm94360

## What works
- macOS Monterey and Ventura
- Audio
- HDMI/DP (in dGPU)
- All USB ports
- Shutdown/Reboot/Update to newer macOS builds over time
- Ethernet: Intel I225-LM (Work) + AppleIntelI210Ethernet.kext) + Add boot-args e1000=0 (avoid KP)

## Kexts used:
- AppleALC.kext
- Lilu.kext
- AppleIntelI210Ethernet.kext
- SMCSuperIO.kext
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext
- RestrictEvents.kext
- NVMeFix.kext

## Thanks/Credits
- [BASE EFI - for 12th Intel Gen - Alder Lake](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-12THGEN-ALDER-LAKE)