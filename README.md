ROM-to-EXE Conversion Tool
Overview
This tool is designed to convert various game ROM files (e.g., N64, NES, PSX) into standalone executable files that can be run on modern systems without needing an emulator. The tool leverages performance enhancements such as Vulkan, 4K resolution, ray tracing, and more.

Disclaimer
By using this tool, you agree to the following terms and conditions:

Usage: This tool is intended for personal use only. You should only use it to convert ROMs that you legally own or have obtained in a manner that complies with your local laws.

No Liability: This tool is provided "as-is," without any warranties or guarantees of any kind. The creator of this tool cannot be held responsible for any damages, legal consequences, or loss of data that may result from the use of this software.

Copyright Laws: It is your responsibility to ensure that you have the legal right to use and convert the ROMs. Distributing, sharing, or using copyrighted ROMs without permission may violate copyright laws. The creator of this tool is not responsible for any illegal activity related to the use of the software.

Emulator Paths: The tool requires you to specify paths to emulators for different ROM formats. You must own the appropriate emulator software and have it properly configured on your system.

Privacy: This tool does not collect any personal data or information. However, you are responsible for the files you input into the tool. Make sure to handle all data with care.

File Handling: This tool creates executable files that run ROMs. Use caution and ensure that the files you are converting do not infringe on any rights. The converted files are for personal use only and should not be distributed.

Requirements
Python 3.x
PyInstaller
Emulator software for each supported ROM type (e.g., Dolphin for GameCube ROMs, Mupen64Plus for N64 ROMs)
A valid game ROM that you have legal access to
Image file (for game cover art) in one of the supported formats (JPEG, PNG, BMP)
Instructions
Install Python 3.x from python.org.
Install PyInstaller by running:
bash
Copy
Edit
pip install pyinstaller
Configure the emulator paths in the script (EMULATOR_PATHS dictionary) for the different supported ROM types.
Run the script and select the ROM you want to convert.
Optionally, choose a cover art image for the converted EXE file.
The converted EXE file will be saved in the specified output directory.
Supported Formats
This tool supports various ROM formats, including but not limited to:

N64 (.z64)
NES (.nes)
Sega Genesis (.smd, .gen)
PlayStation 1 (.psx)
PlayStation 2 (.iso)
GameCube (.gcm)
Wii (.wii)
Game Boy Advance (.gba)
TurboGrafx-16 (.pce)
License
This software is released under the MIT License.
