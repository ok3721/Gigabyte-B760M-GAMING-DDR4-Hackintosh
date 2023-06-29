# Gigabyte-B760M-GAMING-DDR4-Hackintosh
Hackintosh EFI for Gigabyte B760M GAMING DDR4
## Software
|  macOS     |Monterey 12.7   |
| ------------- |-------------| 
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
- [x] Sleep/Wake
- [x] USB Mapping
- [x] GPU temperature monitoring
- [x] NVMe drives
- [x] Audio

<summary><strong>What's not working ⚠️</strong></summary>



- [ ] Wifi/Bluetooth - get a Broadcom card for Wifi


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
