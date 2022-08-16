Once you have setup your first CAN board, you can follow this process for additional boards:
- SSH into your Pi 
- Run lsusb to confirm the can board is in DFU mode
- Run sudo dfu-util -a 0 -D ~/CanBoot/out/firmware_canbus.bin --dfuse-address 0x08000000:force:mass-erase:leave -d 0483:df11
- Run lsusb to confirm the can board is no longer in DFU mode
- To get the UUID, run ~/CanBoot/scripts/flash_can.py -q
- Reboot the Pi by running sudo reboot 
