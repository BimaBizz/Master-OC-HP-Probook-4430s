# Master-OC_077-HP-Probbok-4430s

Support Mojave version

Support Mojave version 10.14.6

# Installation MacOS

Before copy EFI folder change first SMBIOS, GenSMBIOS -> https://github.com/corpnewt/GenSMBIOS

Edit config.plist with propertree -> https://github.com/corpnewt/ProperTree

select GenSMBIOS.bat -> for Windows, select GenSMBIOS.command -> for Mac, and select number Generate SMBIOS

![Screen Shot 2022-08-03 at 14 59 20](https://user-images.githubusercontent.com/98264074/182556836-39cc5c79-dad0-4ffe-819d-98470daaf4aa.png)

The Type part gets copied to Generic -> SystemProductName.

The Serial part gets copied to Generic -> SystemSerialNumber.

The Board Serial part gets copied to Generic -> MLB.

The SmUUID part gets copied to Generic -> SystemUUID.

The Apple ROM part gets copied to Generic -> ROM.

and save it, The last things is copy EFI folder to your EFI partition Flashdisk

#Installation Wifi

