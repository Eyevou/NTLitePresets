<h1>Windows 11 Presets for NTLite</h1>
<h5>The goal of this preset is to give you the most barebones install while maintaining as much compatibility for everything you probably care about. This preset is a good starting point for Gaming, Video editing, streaming, and much more!</h5><hr>
<h3>Everyone wants something different from their Windows experience. Why not start here?</h3>

🔴 Notes 🔴

▶ Scripts:

`all.reg`

This is a file that contains tweaks to make Windows Explorer less bloated. Removes Home, Gaming, and Windows Update tabs in the Settings App for Windows 11. Can also be used on Windows 10. Should be placed to run AFTER logon.

`all_Disable-DevHome-OutlookNew.ps1`

This file removes the Taskbar pin/component for DevHome and Outlook (New). Safe for both Windows 10 and 11. Should be placed to run AFTER logon.

`all_Standard_Install.reg`

This file is for when you make Install Media that includes XBOX and Windows Update stuff. It doesn't remove their entries in the Settings App so that you can edit them later.

▶ Windows 11:

![win11-desktop](https://github.com/user-attachments/assets/52402e6d-e9b5-4d22-b760-82552d13371e)

▶ How to update without Windows Update (Windows 11 only):

[![IUpdating Windows](https://img.youtube.com/vi/MOL-pYqzcXM/0.jpg)](https://youtu.be/MOL-pYqzcXM)

▶ autounattended.xml:

  This is the unattended file that I use to solo boot into Windows as Administrator (System) and set the time to USET.

-----

▶ Known Issues after Updating:

1) LDPlayer9: You'll need to run the installer for this program again (can take a bit to start)
2) ImageGlass: This program is restored to default.
3) Chatty: Notifications panel doesn't show properly. Run the installer again to rehook the overlay.

> If you find any other program oddities after updating please let me know through either the ![Issues Tracker](https://github.com/Eyevou/NTLitePresets/issues) or [NTLite Discord](https://discord.com/invite/UDMbgc6B5e). Thanks!
