<!-- omit in toc -->
#  HP EliteBook 840 G7 üzerinde macOS

<h3> 
    <a href="https://github.com/relaxewdy/HP-EliteBook-840-G7-Hackintosh/blob/main/README.md">İngilizce |</a>
    Türkçe
</h3>

<img align="right" src="https://i.loli.net/2021/02/17/KqIEFsp6SjneLTY.png" width="200px" alt="preview">

HP EliteBook 840 G7 için OpenCore config dosyası.

[![macOS](https://img.shields.io/badge/macOS-11.2-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.6.6-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/HP-EliteBook-840-G7-Hackintosh/releases)

## Ekran Görüntüsü
<details>
<summary>Big Sur</summary>

![](https://i.loli.net/2021/02/17/5AmDMFQ4qE9TtrV.png)

</details>

<!-- omit in toc -->
## Hardware

| **HP** | Detaylar                                                 |
| ------------------- | ------------------------------------------- |
| Model İsmi     | HP Elitebook 840 G7      |
| İşlemci              | Intel(R) Core(TM) i5-10210U CPU @ 1.60GHz (max 4.20Ghz) Comet Lake             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Dahili Grafik Kartı | Intel® UHD Graphics 620                     |
| Wi-Fi             | BCM94360CS2 |
| Ses      | Realtek ALC285                       |

## Neler Çalışıyor

- Turbo hızlandırma ve İşlemci frekansı.
- Intel® UHD Graphics 620
  - Parlaklık Kontrolü
- Ses Realtek ALC285 
  - layout-id: `11`
  - 3.5mm Jak Girişi
- BCM94360CS2 Wi-Fi ve Bluetooth (Airdrop, Handoff..)
- USB 3.0 and Type-C Portları (Port Mapping, ThunderBolt 3 ile birlikte)
- Touchpad (14 harekette çalışıyor)
- Batarya Durumu
- Kamera
- Fn kısayol tuşları

## Neler Çalışmıyor

- Uyku / Uyanma
- Dahili Mikrofon
- Parmak izi
 
Kesinlikle OpenCore Configrator ile SMBIOS ayarlarınızı yapın çünkü config dosyası her hangi bir SMBIOS bilgisi içermiyor.
 - MacBook Pro 16.3
