# Alienware-17-R4-i7-7820HK-Hackintosh (Dual Graphics)

[![Platform](https://img.shields.io/badge/platform-macOS-red.svg)](https://developer.apple.com/macos)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](http://mit-license.org)

## Specifications

- Alienware 17 R4
- i7-7820HK CPU @ 2.90GHZ
- 32 GB Memory
- Intel HD630 / GTX 1080 Graphics
- NVMe TOSHIBA 512 GB SSD + 1T HDD

## Update history

### v0.2.0

Fixed USB detection issue.

It is totally the same as the [clover](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-Mojave-10.14-Hackintosh/tree/master/CLOVER-hd630%2Bnv1060) shared by RockJesus. Additionally, I removed the `-v` argument and replaced the default theme.

### v0.1.0

This one is for macOS 10.13.6 High Sierra, currently there are some known issues.

1. USB devices cannot be detected on the first boot, if you want to get it worked, click the sleep button before logging in via touch panel, when the keyboard light goes out, wake up your computer, then it should be available.

2. No sound.

3. Cannot boot the OS installer, use [AW17R4-Post-Install](AW17R4-Post-Install/CLOVER) instead while installing the system.

4. For screen resolution issue, refer to this online tool: [SCALED RESOLUTIONS FOR YOUR MACBOOKS EXTERNAL MONITOR](https://comsysto.github.io/Display-Override-PropertyList-File-Parser-and-Generator-with-HiDPI-Support-For-Scaled-Resolutions/).

5. If you failed to format the disk to APFS, choose HFS first then use the 'Edit -> Convert to APFS' option in the top menu.

## References

1. http://bbs.pcbeta.com/viewthread-1761528-1-1.html
2. https://github.com/RockJesus/Alienware-17-R4-I7-7700HQ-MacOS-High-Sierra
3. https://blog.huihut.com/2018/10/13/GIGABYTE_Z370_HD3P_i7-8700K_GTX1080_Install_Hackintosh_HighSierra10.13.6/
4. https://comsysto.github.io/Display-Override-PropertyList-File-Parser-and-Generator-with-HiDPI-Support-For-Scaled-Resolutions/
5. https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-Mojave-10.14-Hackintosh
