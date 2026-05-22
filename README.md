# NvmeUsbQuickCheck
NvmeUsbQuickCheckTool - Plugin and Check ( with external interface via USB)

The files need to be compieled to get the .exe file

You will need the following software installed (all from MS)
- .NET SDK 8.0 and PowerShell

Build-Comand: powershell -ExecutionPolicy Bypass -File .\Build-Standalone.ps1  
Finished build will be in this subfolder: ../publish\win-x64-standalone\NvmeUsbQuickCheck.exe

Setup instructions: tools folder

The tools folder must be placed directly next to the program file.

Folder structure:

NvmeUsbQuickCheck.exe
                     /tools/
                             CrystalDiskInfo/
                                               DiskInfo64.exe

Only CrystalDiskInfo is required.
The file DiskInfo64.exe must be located here:
tools\CrystalDiskInfo\DiskInfo64.exe

Recommendation:

Copy the complete portable CrystalDiskInfo folder to:

tools\CrystalDiskInfo\
This ensures that all required CrystalDiskInfo files are available.
Nothing else is required.
