# My-Desktop-Hackintosh Optiplex 9010 i7-3770 4k IGPU

Files needed my desktop hackintosh to work, attached current version working Mojave 10.14.6 - please update files for future versions

I used VirtualBox for emulation - This the only if you don't have a real macOS machine.

Vanilla install process.

Unibeast for Mojave - https://www.tonymacx86.com/resources/unibeast-9-2-0-mojave.426/
guide for unibeast (intel iGPU) - https://www.tonymacx86.com/threads/unibeast-install-macos-mojave-on-any-supported-intel-based-pc.259381/

Config file:
-------------
Config.plist (it's especially made for my motherboard/CPU)

Kexts:
------
Lilu - https://github.com/acidanthera/Lilu/releases
WEG - https://github.com/acidanthera/WhateverGreen/releases
AppleALC - https://github.com/acidanthera/AppleALC/releases
FakeSMC - https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/
USBinjectALL - https://bitbucket.org/RehabMan/os-x-usb-inject-all/downloads/
Ethernet - https://bitbucket.org/RehabMan/os-x-intel-network/downloads/

Pkgs needed to function,
-------------------------
Clover EFI - https://www.tonymacx86.com/resources/categories/clover-builds.12/
HFS+ EFI - Attached on the repo

Other apps:
-----------
KextBeast : https://www.tonymacx86.com/resources/kextbeast-2-0-2.399/
Clover Config (Only used to copy paste files from it to config, don't edit directly on it) - 
                https://mackie100projects.altervista.org/download-clover-configurator/

SSDT's:
SSDT.aml (main one) - Attached on the repo
7 other SSDTs - for different usage - Attached on the repo

Currently 27-Nov-19 all files are updated in the repo

