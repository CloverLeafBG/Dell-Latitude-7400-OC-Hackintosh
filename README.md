# Dell-Latitude-7400-OC-Hackintosh

OpenCore based EFI for Dell Latitude 7400


![7400 copy](https://user-images.githubusercontent.com/93620854/222604110-178aa25d-482f-4298-bd87-c95512504164.png)






## MacOS Version

- macOS BigSur
- macOS Monterey
- macOS Ventura
- macOS Sonoma
- macOS Sequoia

I am currently using macOS Sonoma as a daily driver. If you want to install macOS Sequoia you need to use Heliport + itlwm.kext for your Wi-Fi.

## System Configuration

- CPU:  Intel Core i7-8665U
- iGPU: Intel UHD Graphics 620 (Whiseky Lake)
- RAM:  Crucial 32GB DDR4 3200Mhz (2x16GB)
- SSD:  1TB WD Black SN770
- WiFi: Intel 9560NGW
- Display: 14" 1920*1080 FullHD IPS TouchScreen
- Sound Card: Realtek ALC295


### BIOS Version

1.24.0


### Bootloader

OpenCore

### SMBIOS

MacBookPro15,4


## BIOS Settings

- Boot mode: UEFI
- Fast Boot: Minimal
- SecureBoot: Disable
- SATA Mode: AHCI 
- Intel SGX: Software Controlled


## What's working

 
 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management
 
 - [x] Sleep/Wake
 
 - [x] Internal Speakers
 
 - [x] Internal Microphone
 
 - [x] Audio Jack - Working with ALCPlugFix-Swift - https://github.com/black-dragon74/ALCPlugFix-Swift
 
 - [x] WiFi (2.4Ghz + 5Ghz)
 
 - [x] Bluetooth

 - [x] HDMI + audio over HDMI

 - [x] Touchpad with Gestures + Buttons
 
 - [x] TouchScreen with 2 and 3 fingers gestures

 - [x] Web Camera

 - [x] USB 3.0

 - [x] MicroSD card reader 

 - [x] Native hotkeys support with Fn keys (Volume Fn+F2/F3 and Screen Brightness Fn + F6/F7)
 
 - [x] USB-C charging

 - [x] USB-C DP-alt Mode
  
 - [x] USB-C Data transfer
 
 - [x] Thunderbolt (needs to plug a device before boot)
 

## Benchmarks


![Screenshot 2025-03-09 at 10 20 50 AM](https://github.com/user-attachments/assets/d2f97718-552b-4303-a5da-42405f2afd1c)



![Screenshot 2025-03-09 at 11 18 13 AM](https://github.com/user-attachments/assets/f5ac0a58-4e49-42c8-bd7f-2a4e74e93da0)



![Screenshot 2025-03-09 at 12 25 01 PM](https://github.com/user-attachments/assets/a640c3ab-9a16-42ba-85cb-6dd8f01b0c61)



![Screenshot 2025-03-09 at 11 45 24 PM](https://github.com/user-attachments/assets/8aa59544-7740-4f49-91ee-42873aa5cbeb)



![Screenshot 2025-03-09 at 8 33 34 PM](https://github.com/user-attachments/assets/560b5a27-2406-4c6b-a501-d1e93bab845c)



## What's not working

- Everything is working great so far!

## What's not tested yet

- WWAN card

## Additional Notes

Don't forget to generate your own SMBIOS! 

- ENJOY!
