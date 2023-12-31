# Gigabyte-B760M-GAMING-DDR4-Hackintosh
Hackintosh EFI for Gigabyte B760M GAMING DDR4
## Software
|  macOS     |Monterey 12.6.7   |
| :------------- |-------------| 
|OpenCore    |  0.9.2  | 



## Hardware
| Motherboard   |Gigabyte B760M GAMING DDR4  |
| ------------- |-------------| 
|CPU    | i5-13400  | 
|RAM    | 16G*2 DDR4 3200  | 
|GPU    | XFX RX5700  | 
|SSD    |   Sandisk 480G SATA SSD   |
|Ethernet    | RTL8125BG  | 
|Audio codec   | ALC897  | 


## Status

<summary><strong>What's working ✅</strong></summary>

- [x] OpenCore GUI
- [x] Window 10 dual boot
- [x] Ethernet
- [x] USB Mapping
- [x] GPU temperature monitoring
- [x] NVMe drives
- [x] Audio

<summary><strong>What's not working ⚠️</strong></summary>


- [ ] CPU temperature monitoring - works in Intel Power Gadget, but not in monitoring software like stats (works after upgraded to [lilu](https://github.com/acidanthera/Lilu) 1.6.7, due to my i5-13400 with C0 stepping)
- [ ] Wifi/Bluetooth - get a Broadcom card for Wifi (Caution: Wifi may not working with VT-d on)
- [ ] Sleep/Wake - sometimes not waking up from sleep

<summary><strong>Untested ❔</strong></summary>


- [ ] iMessage, FaceTime, App Store, iTunes Store
- [ ] CPU power management - TODO: try CpuFriend.kext


## BIOS setting
### Enable:
* Above 4G Decoding
* XHCI Hand-off
* VT-d


### Disable:
* Fast Boot
* Secure Boot
* Intel Platform Trust
* CFG Lock
* Serial Port
