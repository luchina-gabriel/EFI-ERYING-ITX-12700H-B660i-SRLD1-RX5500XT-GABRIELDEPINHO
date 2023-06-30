# Perfect ITX Hackintosh - KIT ERYING ITX Intel Core i7 12700H + RX 5500 XT

# Basic Information

**Latest working macOS**: macOS Ventura (13.4.1)
<br>
**Current OpenCore**: 0.9.3
<br>
**Release date**: 30/06/2023

# Hackintosh Specifications
|Item|Description|
|-|:-------:|
|CPU|Intel Core i7 12700H|
|Memory|32GB DDR4 3200Mhz (16Gx2)|
|Storage|NVMe Gen4 Erying 1Tb|
|GPU|AMD Radeon RX 5500 XT 8Gb|
|Ethernet|Realtek 2,5Gbps RTL8125B|
|Ethernet|Realtek 1,0Gbps RTL8111|
|WLAN+Bluetooth|BCM94360CS with NVME Adapter|
|Audio|Realtek ALC897 Audio Controller|

### Working features
- All features

### Don't work
- Nothing

### Generate your SMBIOS [Important]

1. Open Apps > GenSMBIOS > GenSMBIOS.command
2. Select Option #3 [Generate SMBIOS]
3. Fill with iMacPro1,1
4. Replace Serial Numbers in config.plist of EFI [PlatformInfo > Generic]

|GenSMBIOS App|config.plist|
|-|:-------:|
|Type:|SystemProductName|
|Serial:|SystemSerialNumber|
|Board Serial:|MLB|
|SmUUID|SystemUUID|
|Apple ROM:|ROM|

## BIOS Settings

BIOS [E1.0G|2023-03-07]

[Press DEL for ENTER BIOS]

- Exit > Load Optimal Defaults [YES]
- Advanced > CPU Configuration > Intel (VMX) Virtualization Technology : Enabled
- Advanced > Graphics Configuration > Primary Display : PEG Slot
- Advanced > Graphics Configuration > VT-d : Enabled
- Advanced > Graphics Configuration > Internal Graphics : Disabled
- Advanced > Graphics Configuration > Above 4GB MMIO BIOS Assignment : Enabled
- Advanced > PCI Subsystem Settings > Above 4G Decoding : Enabled
- Advanced > PCI Subsystem Settings >  Re-Size BAR Suport : Disabled
- Advanced > NTC5585D Super IO Configuration > Serial Port 1 Configuration > Serial Port : Disabled
- Advanced > USB Confiuration > XHCI Hand-off : Enabled
- Turbo > Memory Profile : XMP Profile 1
- Startup > Full Screen Logo Show : Disabled
- Startup > Fast Boot : Enabled
- Startup > Boot Option Priorities : Pendrive of Opencore
- Security > Secure Boot > Secure Boot : Disabled
- Exit > Save Changes and Exit

## Where to Buy

|Part|Link to Buy|
|-|:-------:|
|KIT ITX Interposer 12700H|https://s.click.aliexpress.com/e/_DmNW9WV|
|GPU AMD RX 6600 8Gb|https://s.click.aliexpress.com/e/_DBq9Phj|
|GPU AMD RX 6600M 8Gb|https://s.click.aliexpress.com/e/_DlfbevX|
|GPU AMD RX 5700 XT 8Gb|https://s.click.aliexpress.com/e/_DekuFv3|
|GPU AMD RX 5600 XT 6Gb|https://s.click.aliexpress.com/e/_DCxCfXX|
|GPU AMD RX 5500 XT 8Gb|https://s.click.aliexpress.com/e/_DBnlfXn|
|NVME Gen4 ERYING|https://s.click.aliexpress.com/e/_DkGeJel|

## Hackintosh Creator
- [Gabriel Luchina - Universo Hackintosh](https://luchina.com.br)

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
