# Petalinux-Tutorial
-- Let's build a FPAG Petalinux by Workstation Petalinux!
### *** Definition clarification:
###(1) Workstation(Desktop) Petalinux (Petalinux 15.4-yocto 1.8): Software design tool for building customized embedded Linux distribution
###(2) FPGA (SoC) Petalinux: Linux system runs on zc706

##### Authors : Baohui Wang (bhwang@tju.edu.cn); Hanchen Jin (hj424@cornell.edu)
##### Date    : Jan. 31, 2017
##### Version : 2.0

**CONTENT**

1. commands - including some general commands of Petalinux and the specific configuration for our design
2. configs - details about Linux configuration
  1. general configuration 
  2. kernel configuration
  3. root file system configuration   
3. images
  1. uImage: linux kernel 
  2. devicetree.dtb: linux devie tree
  3. uramdisk.image: linux root file system
  4. uEnv: file to configure the MAC address
