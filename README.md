# usb_msd_bootloader

A mass storage device bootloader for STM32

I've changed target device for STM32F103C8T6. Original code is designed for bigger device with 2K page size, the FAT disk was designed with 2K sector size, I haven't change it yet so BIN files will not work properly.

What I've improved is HEX file function. Program will not restart when a unknown file arrives. And I've fixed erase on HEX file.
