# Petalinux_Tutorial
-- Let's build a FPAG petalinux by the workstation petalinux!
### *** Definition clarification:
###(1) Workstation(Desktop) petalinux (petalinux 15.4-yocto 1.8): Software design tool for building customized embedded Linux distribution
###(2) FPGA (SoC) petalinux: Linux system runs on zc706

##### Authors : Baohui Wang (bhwang@tju.edu.cn); Hanchen Jin (hj424@cornell.edu)
##### Date    : Jan. 31, 2017
##### Version : 2.0
#####**CONTENT**:
1. workstation
  1.  /workstation/ch0.txt - instructions of installing the workstation petalinux on your workstation
  2.  /workstation/ch1.txt - build FPGA petalinux from scratch 
  3.  /workstation/ch2.txt - build FPGA petalinux from the shell script (petalinux.sh)
  4.  /workstation/petalinux.sh - shell script for building FPGA petalinux
  5.  /workstation/SDcard.txt - SD card preparation 
  6.  /workstation/BOOT.BIN - FPAG petalinux boot loader
  7.  /workstation/uImage - FPGA petalinux kernel built (for zc706)
  8.  /workstation/devicetree.dtb - FPGA petalinux device tree (for zc706)
  9.  /workstation/uramdisk.image.gz - FPGA petalinux root file system (for zc706)
  10. /workstation/uEnv - file to configure the MAC address

2. FPGA
  1. /FPGA/config.txt - FPGA petalinux configuration after boot up on board
  2. /FPGA/user.txt - user guide for using FPGA petalinux

******Instructions******:

1. For common user of FPGA petalinux, please directly go to 2.2 /FPGA/user.txt

2. If you have a zc706 board, and are trying to find a customized linux system which is compatible with SDSoC, please download the following files: /workstation/BOOT.BIN, /workstation/uImage, /workstation/devicetree.dtb, /workstation/uramdisk.image.gz, /workstation/uEnv and follow the instructions provided in the file: /workstation/SDcard.txt and /FPGA/config.txt to boot up and configure your FPGA petalinux

3. If you want to build a petalinux for zc706 by yourself but you don't want to learn too many details, please read: /workstation/ch0.txt, then /workstation/ch2.txt, finally /workstation/SDcard.txt to finish the building process.

4. If you want to build a customized FPGA petalinux for another Xilinx board, say zc702, we strongly recommend you read: /workstation/ch0.txt, then /workstation/ch1.txt, finally /workstation/SDcard.txt to finish the building process. And REMEMBER to modify the necessary parameters for your own requirements.
