<h1 align="center"> macOS on HP EliteBook 840 G7 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh/blob/main/macOS%20HP%20EliteBook%20840%20G7.png">
</p>

<h4 align="center"> OpenCore config for Hackintosh HP EliteBook 840 G7 </h4>

<p align="center">
<a href="https://www.apple.com/macos/ventura/">
  <img src="https://img.shields.io/badge/macOS-Ventura%2013.0-orange" width="195"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.8.5-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="120"/> </a>
<a href="https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusufklncc/HP-EliteBook-840-G7-Hackintosh" width="145"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>

## Contents
  - [Screenshots](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#screenshots-)
  - [Original Hardware](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#original-hardware--)
  - [macOS Update History](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#whats-working--)
  - [What's not working](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#whats-not-working--)
  - [What's you have to do](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#whats-you-have-to-do--)
  - [Kexts Used](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#kexts-used)
  - [SSDTs Used](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#ssdts-used)
  - [Credits](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh#-donate---ba%C4%9F%C4%B1%C5%9F-)
  
## Screenshots 📷

<details>
<summary>Big Sur</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/HP-EliteBook-840-G7-Hackintosh/blob/main/macOS%20Big%20Sur.png">
</p>
</details>


## Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | HP Elitebook 840 G7 | ✅
CPU              | Intel(R) Core(TM) i5-10210U CPU @ 1.60GHz (max 4.20Ghz) Comet Lake | ✅
RAM           | 8 GB 2400 MHz DDR4 | ✅
Internal Graphics Card | Intel® UHD Graphics 620 | ✅
Wi-Fi             | Intel | ✅
Audio       | Realtek ALC285 | ✅


## macOS Update History

- ✅ macOS Ventura 13.0 
- ✅ macOS Monterey 12.6.1
- ✅ macOS Big Sur 11.6.1
- ✅ macOS Big Sur 11.2
- ✅ macOS Big Sur 11.0.1
  

## What's working  💻
  
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅  
Intel HD Graphics             |  ✅  
Brightness control                  |  ✅  
HDMI                                |  ✅  
Audio          |  ✅  
Wi-Fi and Bluetooth         |  ✅  
USB 3.0 (with Port Map)        |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Camera   |  ✅    
Shutdown / Reboot   |  ✅  
Fn shortcut keys   |  ✅  

## What's not working  💻
Type | Status
:---------|:--------- 
S3 Sleep / Wake   |  ❌
S4 Hibernation / Wake   |  ❌
Built-in Microphone   |  ❌
Fingerprint Reader   |  ❌
 
## What's you have to do  💻
  
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With [GenSMBIOS] you should definitely set your SMBIOS settings and ROM value for iCloud and Apple services. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️
  
## Kexts Used 
 
Kext | Info 
:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | [Global] An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | [SMC] Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | [Graphics] Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs.
[USBMapG7Dock](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | [USB] Kext to inject mapped USB Ports.
[AppleALC](https://github.com/acidanthera/AppleALC) | [Audio] An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications. 
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | [Battery] a member of VirtualSMC that parses battery info.
[SMCLightSensor](https://github.com/acidanthera/VirtualSMC) | [Sensor] a member of VirtualSMC that activate light sensor.
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | [Processor] a member of VirtualSMC that provides power info of processor temperature.
[CodecCommander](https://github.com/Dolnor/EAPD-Codec-Commander) | [Audio] 
[VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) | [Touchpad] VoodooI2C is a project consisting of macOS kernel extensions that add support for I2C bus devices.
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | [PS2] Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[AirportItlwm](https://github.com/OpenIntelWireless/itlwm) | [Wi-Fi] An Intel Wi-Fi Adapter Kernel Extension for macOS.
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | [Intel Bluetooth] Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS.
[IntelBTPatcher](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | [Intel Bluetooth] A Lilu base patcher that fix Intel Bluetooth on Bigsur, Catalina, Mojave, High sierra etc, tested with Bigsur and Catalina all working good.
[IntelBluetoothInjector](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | [Intel Bluetooth] Injecting intel bluetooth firmware on Big Sur-.
[BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM) | [Bluetooth] Injecting bluetooth firmware on Monterey+.
[NVMeFix](https://github.com/acidanthera/NVMeFix) | [SSD] NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily.
[HibernationFixup](https://github.com/acidanthera/HibernationFixup) | [Hibernate] An open source kernel extension providing a sync between RTC variables and NVRAM.
[RTCMemoryFixup](https://github.com/acidanthera/RTCMemoryFixup#rtcmemoryfixup) | [RTC] An open source kernel extension providing a way to emulate some offsets in CMOS (RTC) memory. It can help you to avoid some conflicts between macOS AppleRTC and firmware/BIOS of your PC.
[CPUFriend](https://github.com/acidanthera/CPUFriend) | [Processor] A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider](https://github.com/corpnewt/CPUFriendFriend) | [Processor] A CPUFriend plug-in for CPU power management.
[NoTouchID](https://github.com/al3xtjames/NoTouchID) | [Fingerprint] Lilu plugin for disabling Touch ID support.

  
## SSDTs Used
  
SSDT | Info | Status
:---------|:---------|:---------
[SSDT-ALS0](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Ambient_Light_Sensor_(SSDT-ALS0)) | Adds a fake Ambient Light Sensor (SSDT-ALS0) or enables an existing one in macOS (SSDT-ALSD). | [Functional]
[SSDT-AWAC](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/System_Clock_(SSDT-AWAC)) | Disables AWAC system clock for macOS and force-enables RTC instead. For 300-series chipsets and newer. | [Functional]
[SSDT-BATT.aml](https://dortania.github.io/OpenCore-Post-Install/laptop-specific/battery.html#battery-status) | Fixes the battery status indicator. | [Functional]
[SSDT-CPD0.aml] | I2C Touchpad. [Functional]
[SSDT-DATA.aml] | 
[SSDT-EC-USBX.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | [Functional]
[SSDT_GPIO](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/OCI2C-GPIO_Patch) | Enables GPIO device. [Functional]
[SSDT-GPRW](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html) | macOS will instant wake if either USB or power states change while sleeping. To fix this we need to reroute the GPRW/UPRW/LANC calls to a new SSDT. | [Functional]
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | [Functional]
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | [Functional]
[SSDT-PNLF-CFL.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. | [Functional]
[SSDT-RHUB](https://dortania.github.io/Getting-Started-With-ACPI/Universal/rhub.html) | So on 400 series motherboards, certain OEMs have broken the ACPI spec and this results in issues when booting into macOS. To fix this, we'll want to turn off the RHUB device and force macOS to manually rebuild the ports. | [Functional]


## Credits
  
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
