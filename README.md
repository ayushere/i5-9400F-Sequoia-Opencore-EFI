macOS Sequoia on i5 9400F - OpenCore EFI Configuration

This repository contains my OpenCore EFI configuration for successfully running macOS Sequoia on a i5 9400F Hackintosh. This is a developer beta configuration, so expect some instability and potential issues. Use this configuration at your own risk.

Table of Contents

About This Configuration
Hardware
Configuration Overview
Installation Guide
Troubleshooting Tips
Credits
Disclaimer
About This Configuration

This configuration is tailored for the following hardware:

Motherboard: MSI 365M-PRO-VDH
CPU: i5 9400F
GPU: Sapphire 5700XT 8GB
RAM: 24GB DDR4 2400MHZ
Storage: SAMSUNG NVMe 980 Evo Plus 500G
Additional Components: Apple Magic Keyboard, G PRO Mouse
I have successfully booted and run macOS Sequoia (Developer Beta 1) with this configuration. However, your mileage may vary depending on your specific hardware.

Configuration Overview

OpenCore Version: OpenCore 1.0.1
Kexts:
Lilu
WhateverGreen
VirtualSMC
AppleALC
Realtek RTL8111
NVMeFix
RestrictEvents
VirtualSMC & Plugins
USB Tool Box
XHCI-Unsupported

ACPI:
SSDT-AWAC-DISABLE.aml
SSDT-EC-USBX.aml
SSDT-PLUG.aml
SSDT-PMC.aml

SMBIOS: iMac 19,1

Installation Guide:
https://kextcache.com/guide-make-intel-700-hackintosh-build-using-opencore-bootloader/

USB Mapping Guide:
https://kextcache.com/guide-how-to-do-usb-mapping-for-hackintosh-in-windows/

ACPI Patching Guide:
https://kextcache.com/advanced-hackintosh-acpi-a-deep-dive-into-ssdt-selection-and-configuration/

Bootable USB guide:
Windows: https://kextcache.com/make-macos-bootable-usb-on-windows-a-step-by-step-guide/
macOS: https://kextcache.com/guide-to-create-a-bootable-macos-usb-drive-using-gibmacos-tool/

Troubleshooting Tips

If you encounter any issues during installation or booting, refer to the troubleshooting section on my website: https://kextcache.com/common-problems-and-workarounds-in-hackintosh-2020/

on Comment on Specific blog about your problem.

