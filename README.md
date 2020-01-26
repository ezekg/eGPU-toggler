# eGPU-toggler (Windows 10 Bootcamp)
Fix "Error 12" with the 2015 MBP 15" to trigger a successful eGPU connection (TB3->TB2).

# Features
Here's a Windows Batch script that will toggle on and off the eGPU PCIe controller until a successful connection is made.  This program has only been tested with the 2015 MBP 15", the Razer Core X eGPU enclosure and Windows 10 Pro build 1903.

# How To Use Program

1. Extract the files from the .zip to its own folder.

2. Right click on "eGPU-toggler.bat" file and create a .lnk shortcut.

3. Right click on the .lnk shortcut and click Properties, Advanced, then turn on Run as Admin.

4. Make sure the Razer Core X is turned on and plugged into your MBP through the TB2 port.  Then double click on the .lnk shortcut, click "Yes".  After a successful bridge is made, the program will automatically close.
