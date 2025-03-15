# WinAutoManualInstall
A custom Windows installation tool that automates the manual installation process using DISM, DiskPart, and BCDBoot within WinPE.
# Steps:
Click yes when you see the prompt.
Then enter your BIOS type.
Then wait for diskpart to display the disks...
Choose the disk number to install Windows to.
Then choose the efi drive letter.
Then choose the Windows drive letter.
Then choose the size in GB of the Windows partition.
Then wait for diskpart to finish...
Then enter the image file path.
Then enter the index of the Windows edition.
Then enter a product key for the Windows edition you chose (leave blank if you dont have a product key).
Then wait for dism to finish...
Then wait for bcdboot to finish after dism...
Then press any key or wait 10 seconds for it to reboot...
