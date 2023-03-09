# **OpenCore 0.8.9 for GA-H110M-S2H + i5-7400**

## Hardware Configuration

| Part               | Name                                    |
|--------------------|-----------------------------------------|
| **Motherboard**    | Gigabyte GA-H110M-S2H                   |
| **Processor**      | Intel Core i5-7400 (7th Gen)            |
| **Memory**         | Kingston HyperX Fury 16Gb DDR4 2133 MHz |

***

## Features

- [x] CPU Power Management (Not Tested)
- [x] Wake from Sleep (S3)
- [x] All USBs without USBMap.kext
- [x] Ethernet RTL8111
- [x] Apple Services (Please! Write your own SMBios for iMac19,1)
- [x] Realtek ALC887 Audio 🎧 

***

## Included Kexts

| Name               | Description                            |
|--------------------|----------------------------------------|
| **AirportBrcmFixup** | Patches required for non-native Airport Broadcom Wi-Fi cards. |
| **AppleALC** | Native macOS HD audio for not officially supported codecs. |
| **BrcmPatchRAM3** | macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices. |
| **CodecCommander** | Used for updating EAPD (External Amplifier) state on HDA (High Definition Audio) codecs. |
| **CPUFriend** | Dynamic macOS CPU power management data injection. |
| **FeatureUnlock** | Add Sidecar support to unsupported models. |
| **Lilu** | Kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS. |
| **NVMeFix** | Set of patches for the Apple NVMe storage driver, IONVMeFamily. Improve compatibility with non-Apple SSDs |
| **RealtekRTL8111** | Open Source driver for the Realtek RTL8111/8168 family |
| **VirtualSMC** <br> **SMCProcessor** <br> **SMCSuperIO** | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning. |
| **WhateverGreen** | Patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. |
