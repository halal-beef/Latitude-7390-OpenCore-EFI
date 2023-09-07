# Dell Latitude 7390 - OpenCore Configuation

<img align="right" src="https://github.com/halal-beef/res/blob/main/latitude.png" alt="macOS Ventura running on the Latitude 7390" width="425">


[![macOS](https://img.shields.io/badge/macOS-Ventura-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.4-blue)](https://github.com/acidanthera/OpenCorePkg)
[![License](https://img.shields.io/badge/license-MIT-purple)](/LICENSE)

<p align="center">
   <strong>Status: Maintained</strong>
   <br />
   <strong>Version: </strong>0.3
   <br />
   <a href="https://github.com/halal-beef/Latitude-7390-OpenCore-EFI/archive/refs/heads/main.zip"><strong>Download now »</strong></a>
   <br />
   <a href="https://github.com/halal-beef/Latitude-7390-OpenCore-EFI/issues">Report Bug</a>
  </p>
</p>
</br>

## 💻 Hardware Configuration

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i5-8350U                  |
| GPU       | Intel UHD Graphics 620               |
| SSD       | Western Digital PC SN720 NVME        |
| Memory    | 16GB DDR4 2400Mhz                    |
| WiFi & BT | Intel Wireless AC-8625               |

##  Sonoma EFI

- With the latest commit you may have noticed that there is now a "Sonoma" folder, this is just the main EFI with a new AirportItlwm build (Preview 2 for anyone seeing this in the future), Post installation steps still apply here and right now there is no bugs that I have seen.

- For installation right now you'll have to use the main EFI and install Mac OS Ventura then update the EFI folder with the Sonoma EFI folder making sure you do not reboot your system then you can install the update.

## ❗ Post Installation

#### Fixing crackly audio coming from the headphone port

- Open the Terminal 
- cd into the "ComboJack_Installer" folder
- Type ./install.sh and type in your password when asked
- Reboot

## 🛠️ Status

- [X] WiFi & Bluetooth
- [X] Brightness / Volume Control
- [X] Battery Information
- [X] Audio (Audio Jack & Speaker)
- [X] USB Ports & Built-in Camera
- [X] Graphics Acceleration
- [X] Trackpoint / Touchpad
- [ ] Touchpad Buttons
- [X] Power management / Sleep
- [X] FaceTime / iMessage (iServices)
- [X] HDMI
- [X] Automatic OS updates
- [X] USB-C

## 📜 Credits

- [valnoxy](https://github.com/valnoxy) ```For the README Template```
- [AlbinoGiraffe](https://github.com/AlbinoGiraffe) ```For the SSDT-GPI0.aml```
- [dortania](https://github.com/Dortania) ```For the OpenCore guide```
