# AutoWipe
AutoWipe is a Windows Preinstallation Environment (WinPE) that includes Active KillDisk. It is designed to automatically run KillDisk with specific parameters to wipe hard drives and securely erase all data.

### How to Use AutoWipe
To use AutoWipe, you will need to create a bootable USB drive or DVD using the WinPE image provided. You can use software such as Rufus to create the bootable media.

Once you have created the bootable media, insert it into the computer that you want to wipe and boot from the USB or DVD drive. AutoWipe will automatically start and run KillDisk with the following parameters:

-ai2 -eh=0 -xr -em=4 -nc -beep

These parameters are designed to perform a secure erase of the hard drive and overwrite all data with zeroes. The process may take several hours depending on the size of the hard drive.

### Disclaimer
AutoWipe is intended for use on personal computers that you own or have permission to wipe. Using this tool on computers that you do not own or without permission may be illegal and could result in legal consequences.

Use AutoWipe at your own risk. The creators of this tool are not responsible for any data loss or damage that may result from the use of this tool.

### Credits
AutoWipe was created by Jan Novotny. Active KillDisk is a registered trademark of LSoft Technologies Inc..

### License
AutoWipe is released under the NO license. See the LICENSE.md file for more details.
