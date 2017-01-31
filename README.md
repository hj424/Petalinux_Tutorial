# Petalinux-Tutorial
-- Let's build a FPAG petalinux by the workstation petalinux!
### *** Definition clarification:
###(1) Workstation(Desktop) petalinux (petalinux 15.4-yocto 1.8): Software design tool for building customized embedded Linux distribution
###(2) FPGA (SoC) petalinux: Linux system runs on zc706

##### Authors : Baohui Wang (bhwang@tju.edu.cn); Hanchen Jin (hj424@cornell.edu)
##### Date    : Jan. 31, 2017
##### Version : 2.0
#####**CONTENT**:
1. workstation
  1. /workstation/ch1.txt - build FPGA petalinux from scratch 
  2. /workstation/ch2.txt - build FPGA petalinux from the shell script (petalinux.sh)
  3. /workstation/petalinux.sh - shell script for building FPGA petalinux
  4. /workstation/uImage - FPGA petalinux kernel built (for zc706)
  5. /workstation/devietree.dtb - FPGA petalinux device tree (for zc706)
  6. /workstation/uramdist.image - FPGA petalinux root file system (for zc706)
  7. /workstation/uEnv: file to configure the MAC address

2. FPGA
  1. /FPGA/config.txt - FPGA petalinux configuration after boot up on board
  2. /FPGA/user.txt - user guide for using FPGA petalinux

Instructions:
