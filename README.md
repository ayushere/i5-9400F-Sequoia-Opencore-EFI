<div align="center">

# 🚀 macOS Sequoia on i5 9400F – OpenCore EFI Configuration 🚀

</div>

This repository contains my meticulously tested OpenCore EFI configuration to unleash the power of macOS Sequoia (Developer Beta 1) on an i5 9400F Hackintosh build. 
⚠️ **Caveat:**  This is a developer beta, so expect some instability. Proceed at your own risk!

<br>
<div align="center">

## Table of Contents
1.  [About This Configuration](#about-this-configuration)
2.  [Hardware](#hardware)
3.  [Configuration Overview](#configuration-overview)
4.  [Installation Guides](#installation-guides)
5.  [Troubleshooting Tips](#troubleshooting-tips)
6.  [Credits & Disclaimer](#credits--disclaimer)

</div>


<br>

## About This Configuration 

This EFI is meticulously tailored for the following hardware:

*   **Motherboard:** MSI 365M-PRO-VDH
*   **CPU:** i5 9400F
*   **GPU:** Sapphire 5700XT 8GB
*   **RAM:** 24GB DDR4 2400MHZ
*   **Storage:** SAMSUNG NVMe 980 Evo Plus 500G
*   **Additional Components:** Apple Magic Keyboard, G PRO Mouse

<br>

I've personally booted and run macOS Sequoia (Developer Beta 1) with this configuration.  However, your experience may vary depending on your unique hardware setup. 

## Configuration Overview

*   **OpenCore Version:** OpenCore 1.0.1
*   **Kexts:**
    *   Lilu
    *   WhateverGreen
    *   VirtualSMC
    *   AppleALC
    *   Realtek RTL8111
    *   NVMeFix
    *   RestrictEvents
    *   VirtualSMC & Plugins
    *   USB Tool Box
    *   XHCI-Unsupported
*   **ACPI:**
    *   SSDT-AWAC-DISABLE.aml
    *   SSDT-EC-USBX.aml
    *   SSDT-PLUG.aml
    *   SSDT-PMC.aml
*   **SMBIOS:** iMac 19,1

<br>

## Installation Guides 

Need help with the installation process? Follow my detailed guides:

*   **Complete Hackintosh Setup:**  [https://kextcache.com/guide-make-intel-700-hackintosh-build-using-opencore-bootloader/](https://kextcache.com/guide-make-intel-700-hackintosh-build-using-opencore-bootloader/)
*   **USB Mapping:** [https://kextcache.com/guide-how-to-do-usb-mapping-for-hackintosh-in-windows/](https://kextcache.com/guide-how-to-do-usb-mapping-for-hackintosh-in-windows/)
*   **ACPI Patching:**  [https://kextcache.com/advanced-hackintosh-acpi-a-deep-dive-into-ssdt-selection-and-configuration/](https://kextcache.com/advanced-hackintosh-acpi-a-deep-dive-into-ssdt-selection-and-configuration/)
*   **Bootable USB Creation:**
    *   **Windows:**  [https://kextcache.com/make-macos-bootable-usb-on-windows-a-step-by-step-guide/](https://kextcache.com/make-macos-bootable-usb-on-windows-a-step-by-step-guide/)
    *   **macOS:** [https://kextcache.com/guide-to-create-a-bootable-macos-usb-drive-using-gibmacos-tool/](https://kextcache.com/guide-to-create-a-bootable-macos-usb-drive-using-gibmacos-tool/)

<br>

## Troubleshooting Tips

If you encounter issues, head to my website for common Hackintosh problems and workarounds: [https://kextcache.com/common-problems-and-workarounds-in-hackintosh-2020/](https://kextcache.com/common-problems-and-workarounds-in-hackintosh-2020/)

Don't hesitate to comment on the specific blog post for your problem – I'm here to help!

<br>

## Credits & Disclaimer

Big thanks to the Hackintosh community and OpenCore developers!

**Disclaimer:** Use this configuration at your own risk. I'm not responsible for any damage to your hardware or data. 
