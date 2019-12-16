1 Open Hackintool app
2 Clik Tools > Home Icon (to disable Gatekeeper temporarily)
3 go to System/Library/Extensions and delete IO80211Family.kext and IO80211FamilyV2.kext
4 open kext utility and install corecapture.kext and CoreCaptureResponder.kext
5 open clover configurator and mount your efi partition
6 go to EFI/CLOVER/kexts/10.12 and move IO80211Family.kext
7 reboot enjoy