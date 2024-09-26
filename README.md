# Hackintosh-HP-Elitebook-840-G5-Sonoma

Hackintosh EFI for Hp EliteBook 840-G5 based on OpenCore 1.2.1 running Sonoma 14.7

Based on EFI by jkaninada: https://github.com/jkaninda/Hackintosh-HP-EliteBook-830-G5-OC-Ventura
What is different: Updated a couple of kexts to support sonoma and removed IntelBluetoothInjector kext


![Sonoma-preview](https://github.com/user-attachments/assets/8f7073de-5a85-4c96-a27c-93b2e442af9d)


## Hardware Specs  💻

Type | Spec
:---------|:---------
Model Name      | HP Elitebook 840 G5
CPU              | Intel(R) Core(TM) i5-8350U CPU @ 1.70GHz Kaby Lake R
RAM           | 8 GB 2400 MHz DDR4
Internal Graphics Card | Intel® UHD Graphics 620 (rev 07)
Wi-Fi             | Intel 8265/8275
Ethernet          | Intel I219-LM
Audio       | Conexant CX8200
Storage       | Toshiba 512Gb NVMe SSD

Note: For Wifi, Heliport app is required as the EFI uses itlwm kext (AirportItlwm kext does not work for me for now)



## What's working  💻
  
Type | Status
:---------|:---------
Intel HD Graphics             |  ✅  
Brightness control                  |  ✅  
HDMI                                |  ✅  
Audio          |  ✅  
Microphone   |  ✅  
Ethernet            |  ✅  
Wi-Fi and Bluetooth         |  ✅ 
USB 3.0        |  ✅  
USB Type-C        |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Shutdown / Reboot / Sleep / Wake |  ✅  
Fn shortcut keys   |  ✅  
Camera   |  ✅  
Pointing Stick (Nipple)   |  ✅  

Everything seems to be working except for the Fingerprint reader (Which is not supported by Apple by default)


## What's you have to do  💻
  
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With [GenSMBIOS] you should definitely generate and set your SMBIOS settings and ROM value for iCloud and Apple services. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️


README template from: https://github.com/yusufklncc
