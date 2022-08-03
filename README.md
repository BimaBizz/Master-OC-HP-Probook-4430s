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

![Screen Shot 2022-08-03 at 14 59 08](https://user-images.githubusercontent.com/98264074/182559634-0ed5cb84-873e-480c-a0db-de9627590a94.png)

and save it, The last things is copy EFI folder to your EFI partition Flashdisk

# Installation Wifi

download wifi.ketx and kext utility -> https://drive.google.com/drive/folders/1azODhxqdK-grlT_sxIiEctbmf6TGuwJ4?usp=sharing

just unzip kext_utility, open it and grag the wifi kext into kext_Utility 

# Installation Graphics intel HD 3000 for mojave

follow installation on -> https://github.com/chris1111/Fix-Graphics-HD-3000-Mojave-10.14

# installation Sound

download hackintosh vietnam tool -> https://drive.google.com/file/d/1D5BKME_ZeCxuO85biRc0r_vZCBhrwv0D/view?usp=sharing

![Screen Shot 2022-08-03 at 15 34 01](https://user-images.githubusercontent.com/98264074/182563595-0a1929d8-66ca-44b0-b4c6-fd411e4dafb9.png)

Uncheck all list just check the list on kext->sound->VodooHDA

