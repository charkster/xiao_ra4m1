# xiao_ra4m1
Helpful commands and files for Seeed Xiao RA4M1 board.

./rfp-cli -d RA -port /dev/ttyACM0 -a orig_xiao_ra4m1.hex

dfu-util --list -d 0x2886:0x0049 -a0 -D firmware.bin
