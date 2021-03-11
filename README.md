# nx_toolchain
https://docs.nvidia.com/jetson/l4t/index.html

# nx jetpack
https://drive.google.com/file/d/1bopRtmCN0bV1DCED6GykAYeGvgPZGdRG/view?usp=sharing

flash device
1. sudo tar zxvf JetPack_4.4_Linux_JETSON_XAVIER_NX_DEVKIT_full.tar.gz
2. cd JetPack_4.4_Linux_JETSON_XAVIER_NX_DEVKIT_full/Linux_for_Tegra
3. sudo ./flash.sh jetson-xavier-nx-devkit mmcblk0p1

update cboot

  sudo ./flash.sh -k cpu-bootloader --image ./bootloader/cboot_t194.bin jetson-xavier-nx-devkit mmcblk0p1
