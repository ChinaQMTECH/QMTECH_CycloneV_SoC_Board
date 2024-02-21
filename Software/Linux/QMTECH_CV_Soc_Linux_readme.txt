Prerequisite: you need at least a 4Gb microSD card

Setup steps:
1. Unzip the image file
2. Insert the microSD card to the host PC and write the image file into the microSD with the Win32DiskImager tool, balenaEtcher or equivalent tools
3. Insert the programmed microSD card to the QMTECH Cyclone V SoC development board
4. Set the MSEL[4:0] on your development board to 01010(factory setting, no need to change it)
5. Connect a Mini USB cable to the development board
6. Power on the board and you will see the linux info from the console
7. Linux user name root, NO password

Additional information:
2. The Linux kernel version is 4.1.33-ltsi-altera. You can get the kernel source code from https://github.com/altera-opensource/linux-socfpga
