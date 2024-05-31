# T480s-hackintosh-monterey
Prebuilt OpenCore v1.0 EFI files & configuration for Thinkpad T480s to run macOS Monterey

## My Hardware Info
| Name                | Specifications                             |
| ------------------- | -------------------------------------------|
| Processor           | Intel Core i5-8350U Processor              |
| Memory              | 8GB soldered + 8GB on the slot             |
| Storage             | VR M.2 NVME 512GB                          |
| Graphics            | Intel UHD Graphics 620                     |
| Display             | 14.0" FHD 1920x1080 LED IPS                |
| Audio               | Realtek ALC257                             |
| Ethernet            | Intel I219LM4 PCI Express Gigabit Ethernet |
| WLAN & Bluetooth    | Intel Dual Band Wireless-AC 8265           |
| Touchpad            | Elan SMBus                                 |

## BIOS Setting
- Config
  - Network
      - Wake On LAN -> Disabled
      - Wake On LAN from Dock -> Disabled
  - CPU
    - Intel (R) Hyper-Threading Technology -> Enabled
- Security
  - Security Chip
    - Security Chip -> Disabled
  - Virtualization
    - Intel (R) Virtualization Technology -> Enabled
    - Intel (R) VT-d Features -> Disabled
  - Secure Boot ->
    - Secure Boot -> Disabled
  - Intel(R) SGX
    - Intel (R) SGX Control -> Disabled
- Startup
  - UEFI/Legacy Boot -> UEFI Only
  - CSM Support -> No
