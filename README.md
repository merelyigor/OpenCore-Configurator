# OpenCore Configurator
A tool for creating and editing OpenCore configuration files. 

## Features
## creator https://github.com/notiflux/OpenCore-Configurator

* Paste ACPI patches from either OC or Clover in plist format
* Auto-add entries for ACPI tables in OC/ACPI/Custom
* Auto-add entries for KEXTs in OC/Kexts
* Auto-add entries for UEFI drivers in OC/Drivers
* Verify file integrity for ACPI tables, KEXTs and UEFI drivers
* Generate SMBIOS with macserial
* EFI partition mounter

#### Coming soon
* convert clover config.plist into OC format
* In-app updater (OCC and macserial)

## Building
When building this project, make sure you download the macserial binary (linked below) and put it in the root folder of the project. Then you can just run/archive the app from Xcode.  
Note: This app is written in Swift 5, so you will need at least Xcode 10.2.

# Credits
[vit9696](https://github.com/vit9696) for [OpenCore](https://github.com/acidanthera/OpenCorePkg) and [macserial](https://github.com/acidanthera/MacInfoPkg)  
[Download-Fritz](https://github.com/Download-Fritz) for OpenCore and for helping me understand the ins and outs of its configuration  
[xmari0](https://github.com/xmari0) for helping me debug various issues  
[CorpNewt](https://github.com/CorpNewt) for motivating me to write this app  
[Tony](https://github.com/tonyarnold), [Pavo](https://github.com/Pavo-IM) and notiflux for writing and maintaining this app
