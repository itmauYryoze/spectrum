
 
# How to Install Windows 7 Directly to USB External Drive with NT 6.x Fast Installer
 
If you want to install Windows 7 or other NT 6.x operating systems (such as Vista or 2008) directly to a USB external drive, you may find the official setup.exe very limiting and frustrating. Fortunately, there is a better way to do it with NT 6.x Fast Installer, a set of cmd batch files that can install NT 6.x from any version of WinPE and Windows 2000 or above, without extracting or burning the ISO file. In this article, we will show you how to use NT 6.x Fast Installer to install Windows 7 directly to USB external drive in a few simple steps.
 
## What You Need
 
- A Windows 7 ISO file mounted by any kind of virtual drive.
- A USB external hard drive with enough space for the OS installation.
- The NT 6.x Fast Installer files, which you can download from [here\[^1^\]](http://reboot.pro/index.php?showtopic=10126). You will need to find and put the following files in the same folder as the installer.cmd: imagex.exe from Win7 7600 WAIK, bcdboot.exe from Win7 beta 7000, and bootsect.exe from Win7 7600.
- A computer that can boot from USB device.

## How to Install Windows 7 Directly to USB External Drive

1. Run the installer.cmd as administrator. You will see a command prompt window with some options.
2. Select the source of installation. You can choose the mounted ISO file or a folder that contains the extracted files.
3. Select the target of installation. You can choose any partition on your USB external drive. Make sure it is formatted as NTFS.
4. Select the index of installation. You can choose which edition of Windows 7 you want to install from the list.
5. Select the boot partition. You can choose which partition will contain the boot files. It is recommended to choose the same partition as the target of installation.
6. Select the letter of installation. You can choose which letter the OS partition will occupy in Windows 7. It is recommended to choose C:.
7. Wait for the installation process to finish. It will take about 10 minutes or less depending on your hardware.
8. Reboot your computer and change the boot order to boot from USB device.
9. Enjoy your Windows 7 on USB external drive!

## Tips and Tricks

- After installing Windows 7 on USB external drive, you should open the write cache of the hard drive in device manager to speed up the system.
- If you want to plug the USB OS to another PC, you should run the command as administrator: `sysprep /generalize /oobe /shutdown` before shutting down your system. This will make Windows 7 re-detect the hardware and drivers on the next boot.
- If you want to uninstall Windows 7 from USB external drive, you can simply delete all the files on the OS partition and use diskpart or other tools to remove the boot flag and active flag from the partition.

**Download Zip ✫ [https://t.co/uPuoHDfZpG](https://t.co/uPuoHDfZpG)**


 8cf37b1e13
 
