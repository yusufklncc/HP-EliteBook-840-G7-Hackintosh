<!-- omit in toc -->
# <img align="left" src="https://github.com/yusfklncc/HP-EliteBook-840-G7-Hackintosh/blob/main/Apple.png" width="30px" alt="preview">macOS on HP EliteBook 840 G7

<h3> 
    English
</h3>

<img align="right" src="https://i.loli.net/2021/02/17/KqIEFsp6SjneLTY.png" width="200px" alt="preview">

OpenCore config for Hackintosh OpenCore HP EliteBook 840 G7.

<p align="center">
<a href="https://www.apple.com/macos/big-sur/">
  <img src="https://img.shields.io/badge/macOS-Big_Sur_v11.6.1-red.svg"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg">
  <img src="https://img.shields.io/badge/OpenCore-0.7.5-12AED6"/> </a>
<a href="https://github.com/yusfklncc/HP-EliteBook-840-G7-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusfklncc/HP-EliteBook-840-G7-Hackintosh"/> </a>
<a href="https://damnthattelevision.com/Contact">
   <img src="https://img.shields.io/badge/%40-Contact-FFF27D"> </a>
</p>

<p align="center">
<a href="https://www.apple.com/macos/big-sur/">
  <img src="https://img.shields.io/badge/macOS-Big_Sur_v11.6.1-red.svg"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg">
  <img src="https://img.shields.io/badge/OpenCore-0.7.5-12AED6"/> </a>
<a href="https://github.com/yusfklncc/HP-EliteBook-840-G7-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusfklncc/HP-EliteBook-840-G7-Hackintosh"/> </a>
<a href="https://damnthattelevision.com/Contact">
   <img src="https://img.shields.io/badge/%40-Contact-FFF27D"> </a>
</p>

## Screenshot
<details>
<summary>Big Sur</summary>

![](https://i.loli.net/2021/02/17/5AmDMFQ4qE9TtrV.png)

</details>

<!-- omit in toc -->
# Laptop's Hardware

| **HP** | Details                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | HP Elitebook 840 G7      |
| CPU              | Intel(R) Core(TM) i5-10210U CPU @ 1.60GHz (max 4.20Ghz) Comet Lake             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Internal Graphics Card | Intel® UHD Graphics 620                     |
| Wi-Fi             | Intel (replaced by BCM94360CS2) |
| Sound       | Realtek ALC285                       |

# Update History
- [x] macOS Big Sur 11.6.1
- [x] macOS Big Sur 11.2
- [x] macOS Big Sur 11.0.1

# What's Working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  Turbo boost and CPU frequency stage |  ✅  |
|  Intel UHD Graphics 620              |  ✅  |
|  Brightness control                  |  ✅  |
|  Audio Realtek ALC285 (id:21)        |  ✅  |
|  BCM94360CS2 Wi-Fi and Bluetooth, Airdrop, Handoff, SideCar, iMessage...         |  ✅  |
|  USB 3.0 and Type-C (with Port Map)        |  ✅  |
|  Touchpad (14 gestures are working)   |  ✅  |
|  Battery status   |  ✅  |
|  Camera   |  ✅  |
|  Shutdown / Reboot   |  ✅  |
|  Fn shortcut keys   |  ✅  | 

# What's not working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  S3 Sleep / Wake    | ❌  |
|  Built-in Microphone| ❌  |
|  Fingerprint        | ❌  |

# What You Have to Do?
|                                 |                                    |
| -----------------------------------  | -------- |
|  SMBIOS Settings  | ⚠️ |
 
With OpenCore Configurator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 16.3
