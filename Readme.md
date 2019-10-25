MSI ProBox23 Mojave EFI for Hackintosh

CPU : i3-4370
GPU : Intel HD 4600

-------------------------------------------------------------------------------------------------------
for 10.14.6
Clover         v2.5k 5070
lilu           v1.3.8
AppleALC       v1.4.2
WhatEvergreen  v1.3.3

SMBIOS : iMac14,2

Download Mojave 10.14.6 18G103 from Apple's Server:

https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/InstallInfo.plist
https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/061-26589.English.dist
https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/InstallAssistantAuto.pkg
https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/AppleDiagnostics.chunklist
https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/AppleDiagnostics.dmg
https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/BaseSystem.chunklist
https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/BaseSystem.dmg
https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/InstallESDDmg.pkg
https://swdist.apple.com/content/downloads/17/32/061-26589-A_8GJTCGY9PC/25fhcu905eta7wau7aoafu8rvdm7k1j4el/InstallESDDmg.chunklist

1.Rename InstallESDDmg.pkg to InstallESD.dmg
2. Edit InstallInfo.plist, change InstallESDDmg.pkg to InstallESD.dmg , and delete below 4 lines.
   change com.apple.pkg.InstallESDDmg to com.apple.dmg.InstallESD
   Check edit_InstallInfo.jpg for detail.
3. Create a folder, name it as SharedSupport. copy all downloads files to this forlder. 
4. Extract "Install macOS Mojave.app" from BaseSystem.dmg. Then move the SharedSupport folder to "Install macOS Mojave.app/Content/".
5. Using "Install macOS Mojave.app/Content/Resources/createinstallmedia" make your own install media.



-------------------------------------------------------------------------------------------------------

=======================================================================================================
for 10.14.5
Clover         v2.4k 4961
lilu           v1.3.6
AppleALC       v1.3.8
WhatEvergreen  v1.2.9

SMBIOS : iMac14,2

Download Mojave 10.14.5 from Apple's Server:

http://swcdn.apple.com/content/downloads/21/07/041-59913/m210y0lkn7bsiqsi98vfuyk08x2z4to1qk/BaseSystem.dmg
http://swcdn.apple.com/content/downloads/21/07/041-59913/m210y0lkn7bsiqsi98vfuyk08x2z4to1qk/BaseSystem.chunklist
http://swcdn.apple.com/content/downloads/21/07/041-59913/m210y0lkn7bsiqsi98vfuyk08x2z4to1qk/InstallInfo.plist
http://swcdn.apple.com/content/downloads/21/07/041-59913/m210y0lkn7bsiqsi98vfuyk08x2z4to1qk/InstallESDDmg.pkg
http://swcdn.apple.com/content/downloads/21/07/041-59913/m210y0lkn7bsiqsi98vfuyk08x2z4to1qk/AppleDiagnostics.dmg
http://swcdn.apple.com/content/downloads/21/07/041-59913/m210y0lkn7bsiqsi98vfuyk08x2z4to1qk/AppleDiagnostics.chunklist
==========================================================================================================================


Reference：
https://www.insanelymac.com/forum/topic/329828-making-a-bootable-high-sierra-usb-installer-entirely-from-scratch-in-windows-or-linux-mint-without-access-to-mac-or-app-store-installerapp/

https://www.insanelymac.com/forum/topic/338810-create-legit-copy-of-macos-from-apple-catalog/

https://www.insanelymac.com/forum/files/file/944-mojave-mbr-hfs-firmware-check-patch/

https://www.tonymacx86.com/threads/create-legit-copy-of-macos-from-apple-catalog.277388/

Apple's Regular Software Catalog
https://swscan.apple.com/content/catalogs/others/index-10.14-10.13-10.12-10.11-10.10-10.9-mountainlion-lion-snowleopard-leopard.merged-1.sucatalog.gz

/Library/Preferences/com.apple.SoftwareUpdate.plist
