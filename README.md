# RLECViewer
Clevo Custom fan control

This fork is an attempt to update the code to a more modern code standart. As Gigabyte (and I think also other vendors) also uses Clevo designs this project should also work for those devices.

As of now, I only tested the originally published executable.

* Tested on Gigabyte G5 MF, Windows 11 23H2

It seems that (opposite to the hint in the original fork) there is no need to uninstall the Gigabyte Control Center Package, at least as far as I know. For me the program just overrides the fan speed as long as it is running and the operation goes back to default if it is exited.

For reference follows the content of the original document.

# RLECViewer - Original Document
Clevo custom fan control

Original post: http://tieba.baidu.com/p/4872453181

Uninstall Clevo Control Center first

Then install this: https://github.com/zuyan9/RLECViewer/raw/master/Install/Product/RLECViewer.exe

Tested on Clevo P751DM2, Windows 10 1803 with UEFI.

Developed in VC6.0 (I know...)

## WARNING

Windows Release is detected as Trojan in multiple antivirus software (see [issue #3](https://github.com/zuyan9/RLECViewer/issues/3)) and [issue #4](https://github.com/zuyan9/RLECViewer/issues/4)), use (or compile from the source code) at your own risk.
