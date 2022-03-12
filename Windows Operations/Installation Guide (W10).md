This guide will assist you with the installation process for Windows 10 versions (All versions from Home to Enterprise (non-LTSB/LTSC) share the same installer).
We will assume that the host machine for creating the bootable USB drive is a Windows machine. If you are trying to create a bootable Windows drive from a Linux machine, check the other guide (which, for now, does not exist :( oof)

## 1. Check system requirements
It is very likely that your computer meets the minimum requirements already, but this section has been included for peace of mind, as there are a lot of folks who are running old or very old hardware. If your computer does not meet these system requirements, perhaps it is time to get a new one (or switch to a Linux distribution).

The official system requirements for Windows 10, as provided by Microsoft, are the following:

- Processor:	1 gigahertz (GHz) or faster compatible processor or System on a Chip (SoC)
- RAM: 	1 gigabyte (GB) for 32-bit or 2 GB for 64-bit 
- Hard drive size: 32GB or larger hard disk
- Graphics card:	Compatible with DirectX 9 or later with WDDM 1.0 driver
- Display:	800x600
- Internet Connection:	Internet connectivity is necessary to perform updates and to download and take advantage of some features. 

These requirements may change over time. To see the most recent version of these requirements, please access [Microsoft's Website](https://www.microsoft.com/en-us/windows/windows-10-specifications)

## 2. Create USB installation media (if needed)
If you do not already have a Windows 10 installation disk or flash drive, or you simply want to create your own, you can create one by accessing [this link](https://www.microsoft.com/en-us/software-download/windows10) and clicking on "Download Tool Now".

You will want to use a blank flash drive that has at least 8GB of blank space to install Windows on your computer, but other options are also possible (CD/DVD).

## 3. Run the installer
Double click on the installer to open it. Read through (I am sure you will do that, ugh) the Terms of Service and accept them.

At the next step, you will be asked what you want to do. Simply select the button that says "Create installation media for another PC".
Choose the type of media you want to use. For the sake of this tutorial (and my sanity; I have only slept 4 hours in the past 32 hours), we will choose "USB Flash Drive" installation.

Click next, and plug in your flash drive (if you haven't done it already). Select the appropriate flash drive from the list (or click on "refresh drive list" if nothing shows up) and proceed further.

The setup tool will now create the bootable USB flash drive. Please note that the tool will need to download a rather hefty ammount of files, and this might take a while (depending on your internet connection).

At the end, you will be informed that the flash drive is ready to use. Simply click on "finish".

## 4. Boot into BIOS & Change Boot Order
(or simply boot from device, if your BIOS offers this feature)

The process of booting into BIOS differs from device to device; the general strategy would be to spam the F2, F12 and Delete keys as the computer boots up.
If the computer you want to install windows on has a blank drive, you might not even have to do this step (as it would automatically boot into BIOS).

Once you have access to the BIOS menu, you will need to locate the boot order settings.

[TBA - too tired to continue]
