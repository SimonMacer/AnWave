AnWave 2024
===================================================

### ※AnWave All in One Features
* 【Main Feature】AnWave UI - Manage downloaded AMD/NVIDIA drivers
* 【Main Feature】AMD Radeon Software Customize Setup
* 【Main Feature】Advanced Cleanup Utility
* 【Main Feature】Windows Key-Point


### ※Requirements
* Microsoft .NET Framework 4.5 or newer
* Microsoft Windows 10 or newer
* 64-bit operating system

### ※Introduction
--------

This is a personal project developed using Visual Studio 2022 C#. Includes AMD Radeon Software Customize Setup, For customizing AMD Software: Adrenalin Edition installation. and Windows Key-Point, Best Windows 10 or 11 Settings Options Organizer. and AnWave Advanced Cleanup Utility, Cleanup AMD and NVIDIA graphics card drivers and application utilities.

### ※AnWave Demo
[AnWave V8 - 自訂 AMD Software: Adrenalin Edition 安裝](https://youtu.be/yEow3n5rLQ0?si=qxqGxAKR25ZVhgk6)

### ※Release

[Download the latest release](https://github.com/SimonMacer/AnWave/releases)

> I use WinRAR version 7.0 or above to compress files. It is recommended to use the latest version of WinRAR to open files.
>
> [WinRAR download free and support: WinRAR](https://www.win-rar.com/start.html?&L=0)

### ※Customize your AMD Software: Adrenalin Edition (Or use AnWave to install NVIDIA drivers)
Download AMD or NVIDIA drivers

> Note: Please download the offline version of the driver.

【AMD】[AMD Radeon™ Series graphics card driver](https://www.amd.com/en/support/download/drivers.html)

【NVIDIA】[NVIDIA Driver download](https://www.nvidia.com/Download/index.aspx?lang=en-us)

Installing AMD Software: Adrenalin Edition or GeForce Game Ready
Set the path to the AMD/NVIDIA driver. Press the [Extract] button to start decompressing. After a while, press the [Custom] button to open the AMD Radeon Software Customize Setup interface or press [Install] to start installing the driver.

* In the [Executable File Package (*.exe)] Tab, select a version from [Driver Version] menu to start the installation.

* In the [Extracted Packed] Tab, select a unpacked driver from tree view to start the installation.

![AnWave Install Drivers](https://i.meee.com.tw/DR62zie.png "AnWave Install Drivers")

### ※Advanced Cleanup Utility
In the AnWave window menu [Feature] > [Advanced Cleanup Utility Center], open the AnWave Advanced Cleanup Utility Center window and select an option for the cleaning process.

* Supports for AMD Ryzen™ Chipset Driver, AMD Software: Adrenalin Edition, AMD Software: PRO Edition, AMD ROCm™ Software, AMD Privacy View, AMD Chatbot, AMD Install Manager, NVIDIA GeForce Game Ready Driver, NVIDIA Studio Driver, NVIDIA Geforce Experience, NVIDIA App, NVIDIA Broadcast, NVIDIA FrameView and NVIDIA CUDA Toolkit cleanup.

![Advanced Cleanup Utility](https://i.meee.com.tw/kDyM3Ib.png "Advanced Cleanup Utility")

### ※NVIDIA DLSS Global Override Mode
Allow you to update DLSS games and apps to use the latest DLSS models.

DLSS Global Override Mode Recommend

* NVIDIA GeForce R566.36 or later.

* NVIDIA DLSS version 3.1.11 or later.

#### HOW TO USE NVIDIA DLSS Global Override Mode
1. Download [AnWave](https://github.com/SimonMacer/AnWave/releases) or [NVIDIA DLSS Global Override Mode Standalone](https://github.com/SimonMacer/AnWave/releases/tag/AnWave-DLSS).

2. [Download NVIDIA DLSS DLL](https://www.techpowerup.com/download/nvidia-dlss-dll/)

3. [Download NVIDIA DLSS 3 Frame Generation DLL](https://www.techpowerup.com/download/nvidia-dlss-3-frame-generation-dll/)

4. [Download NVIDIA DLSS 3.5 Ray Reconstruction DLL](https://www.techpowerup.com/download/nvidia-dlss-3-ray-reconstruction-dll/)

5. [Download Streamline Integration Framework Files](https://github.com/NVIDIAGameWorks/Streamline)

6. Extract and place these DLSS *.dll files in the same location as nvidiaDlssGlom.exe.

7. Run nvidiaDlssGlom.exe and click 'Update' button.

![NVIDIA DLSS Global Override Mode](https://i.meee.com.tw/Dic0uxA.png "NVIDIA DLSS Global Override Mode")

### ※Restore Microsoft Dolby Digital Decoder/Encoder MFT (and WordPad) support in Windows 11, version 24H2
Microsoft has removed the AC-3 codec (Dolby Digital) and WordPad features in Windows 11 24H2 or higher builds. Now, you can use this toolkit to install AC-3 codec (Dolby Digital) and WordPad FoD and re-enable these features.

【1】Dolby AC-3 Features On Demand for Microsoft Windows (Server) operating system version 24H2.

【2】WordPad Features On Demand for Microsoft Windows (Server) operating system version 24H2.

- Download [Dolby AC-3 and WordPad FoD Optional-In](https://github.com/SimonMacer/AnWave/releases/tag/RollbackDolby).

### ※Disable or Enable Memory Integrity and VBS Enablement

Some applications and hardware device drivers may be incompatible with memory integrity. This incompatibility can cause devices or software to malfunction and in rare cases may result in a boot failure (blue screen). Such issues may occur after memory integrity has been turned on or during the enablement process itself. If compatibility issues occur, see [Troubleshooting](https://learn.microsoft.com/en-us/windows/security/hardware-security/enable-virtualization-based-protection-of-code-integrity?tabs=security#troubleshooting) for remediation steps.

#### Run msinfo32.exe or Disable Memory Integrity and VBS Enablement in AnWave to check Credential Guard & VBS Key Isolation and Memory Integrity status.

![Disable Memory Integrity and VBS Enablement](https://i.meee.com.tw/RRdAY14.png "Disable Memory Integrity and VBS Enablement")

1. Run AnWave.exe. Menu > System > Disable Memory Integrity and VBS Enablement.

2. Click 'Start' to disable Memory Integrity and VBS Enablement or 'Re-enable VBS and Memory Integrity' to enable Memory Integrity and VBS Enablement.

> May require resetting (Facial recognition, Fingerprint recognition and PIN) Windows Hello configuration.

![Windows Hello configuration](https://i.meee.com.tw/6mzUlax.png "Windows Hello configuration")

3. Run Windows PowerShell, copy all the text in the text box and paste the (Ctrl + V) PowerShell, then press Enter on your keyboard.

![Disable Memory Integrity and VBS Enablement powershell](https://i.meee.com.tw/6hmX5qG.png "Disable Memory Integrity and VBS Enablement powershell")

4. Reboot to continue disable (re-enable) VBS Enablement.

![Credential Guard Opt-out Tool](https://i.meee.com.tw/ZWkD4fR.png "Credential Guard Opt-out Tool")

![VBS Opt-out Tool](https://i.meee.com.tw/wSNdkR8.png "VBS Opt-out Tool")

### ※Microsoft Defender Uninstaller
Microsoft Defender Uninstaller is a utility tool for uninstalling Windows Defender. Microsoft Defender Uninstaller is included with AnWave, and a standalone version is also available for download. [Microsoft Defender Uninstaller Standalone Download](https://github.com/SimonMacer/AnWave/releases/tag/AnWave-Split)

### ※Disable Memory Integrity and VBS Enablement in Windows 11, version 24H2

HOW TO: Run AnWave.exe. Menu > System > Disable Memory Integrity and VBS Enablement.

![Disable Memory Integrity and VBS Enablement](https://i.meee.com.tw/1uy3nN7.png "Disable Memory Integrity and VBS Enablement")

![Disable Memory Integrity and VBS Enablement](https://i.meee.com.tw/L4KJBLv.png "Disable Memory Integrity and VBS Enablement")

### ※Install Legacy DX11 driver into Adrenalin 24.x.x and Disable DXNAVI on RDNA2 architecture

HOW-TO

[1] Download official Adrenalin 24.1.1 WHQL or latest version.

[2] Download [AnWave latest version](https://github.com/SimonMacer/AnWave/releases).

[3] In AMD Radeon Software Customize Setup, Advanced Tab > Additional > Enable Install Legacy DirectX 11 UMD Support and Pop-up Interface Allows Users to Configure DirectX 11 API Mode options in Experimental group box. and install.

> Or in Applied Install Profile, Enable Install Legacy DirectX 11 UMD Support and Pop-up Interface Allows Users to Configure DirectX 11 API Mode options. and install.

![Applied Install Profile](https://i.meee.com.tw/uiQtewT.png "Applied Install Profile")

See 【HOW-TO】[Install Legacy DX11 driver into Adrenalin 24.x.x and Disable DXNAVI on RDNA2 architecture](https://github.com/SimonMacer/AnWave/discussions/6)

### ※AnWave Library
--------

### [NVIDIA Power Management](https://github.com/SimonMacer/AnWave/releases/tag/NVPMMan)

### 【AMD Ryzen】AMD Ryzen CPU - Precision Boost Overdrive (PBO) Google Spreadsheets:https://github.com/SimonMacer/AnWave/discussions/13

===================================================
### ※AMD / NVIDIA Drivers Download Link
--------

### AMD Software: Adrenalin Edition Download

https://www.amd.com/en/support/download/drivers.html

### NVIDIA GeForce® Drivers Download

https://www.nvidia.com/en-us/drivers/

https://www.nvidia.com/en-us/geforce/drivers/

===================================================
### ※External Forum Link
AnWave 2024 | AMD Radeon Software Customize Setup @ forums.guru3d.com

https://forums.guru3d.com/threads/anwave-2024-amd-radeon-software-customize-setup-advanced-cleanup-utility-gpu-cleanup-tool.443504/

AnWave 2024 | NVIDIA Power Management @ forums.guru3d.com

https://forums.guru3d.com/threads/anwave-2024-advanced-cleanup-utility-gpu-cleanup-tool-nvidia-power-management-power-control.447584/

### ※台灣-繁體中文外部論壇

【原創】AnWave 2024 | GPU 專用的進階清理公用程式、自訂 AMD 顯示卡驅動程式安裝、NVIDIA 電源管理工具

https://forum.gamer.com.tw/C.php?bsn=60030&snA=629234&tnum=0

【原創】AnWave Windows Key-Point - Windows 設定選項管理器 | 設定商務用 Windows Update 輕鬆設定管理工具

https://forum.gamer.com.tw/C.php?bsn=60030&snA=645785&tnum=1

【其他】AnWave Advanced Cleanup Utility 專門清理 AMD 晶片組、AMD 或 NVIDIA 圖形驅動公用程式

https://forum.gamer.com.tw/C.php?bsn=60030&snA=663817&tnum=1
