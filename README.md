SparkFun Electronics SAMD21/SAMD51 Drivers for Windows 7
========================================

This is a Windows 7 installer package for SparkFun's SAMD21 and SAMD51 based breakout boards.

By default Windows 7 fails to recognize SAMD based processors, preventing use of boards based on these processors. Running the installer created form this repository installed the proper drivers for the supported boards, enabling use of these boards in Arduino, CircuitPython and UF2 boot loader modes.

This installer is for Windows 7 only. Later versions of Windows have built in support for SAMD based boards.

## Supported SparkFun Boards

* SparkFun Qwiic Micro
* SparkFun RedBoard Turbo
* SparkFun SAMD21 Development Breakout Board
* SparkFun SAMD21 Mini Breakout Board
* SparkFun LumiDrive
* SparkFun SAMD51 Thing +
* SparkFun 9DoF Razor IMU
* SparkFun ProRF - LoRa
* SparkFun ProRF - LoRa 1W

## Installation

Head to the [tagged releases in this GitHub repo](https://github.com/sparkfun/samd_windows7_installer/releases) to download the installer package (this is the executable and will have a version number associated with the release like **sparkfun_drivers_1.0.5.3.exe**). To install the package, just double click on the executable and follow the steps outlined by the installer. If you have previously installed these drivers, you may need to uninstall the previous drivers to update them to the latest version.

During the install process, Windows will warn that "**Windows can't verify the publisher of this driver software**". This is normal for this particular package. The "**Install this driver software anyway**" option should be selected.
