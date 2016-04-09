# linkit-smart-uboot
This feeds holds the UBoot bootloader source code for the LinkIt Smart 7688 (Duo)

# Compile

Start by cloning the tree

`git clone https://github.com/MediaTek-Labs/linkit-smart-uboot.git`

We need to install the cross toolchain required to build the source

`sudo tar xjf buildroot-gcc342.tar.bz2 -C /opt/`

Finally we can start building the source

`make`

Notes: Uboot firmware is uboot.bin NOT uboot.img

#Update
make sure tftp server is installed on server:

1. copy uboot.bin to /tftpboot
2. reset board and select 9
3. confirm local ip and server ip, bin name

