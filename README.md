<h1>Windows 11 Presets for NTLite</h1>
<h5>The goal of this preset is to give you the most barebones install while maintaining as much compatibility for everything you probably care about. This preset is a good starting point for Gaming, Video editing, streaming, and much more!</h5><hr>
<h3>Everyone wants something different from their Windows experience. Why not start here?</h3>

🔴 Notes 🔴

▶ Scripts:

`all.reg`

This is a file that contains tweaks to make Windows feel better to use. Included but not limited to: <br>
Restoring the Windows 10 right-click menu, Cleaning folder bloat from Windows Explorer, and disabling Sticky Keys.

`all_Hide_Settings_Options.reg`

Removes Home and Windows Update tabs in the Settings App for Windows 11. It will also disable Windows Delivery Optimization.

`all_Disable-DevHome-OutlookNew.ps1`

This file removes the Taskbar pin/component for DevHome and Outlook (New). Safe for both Windows 10 and 11.

▶ Desktop Preview (Windows 11):

![win11-desktop](https://github.com/user-attachments/assets/52402e6d-e9b5-4d22-b760-82552d13371e)

▶ How to update without Windows Update (Windows 11 only):

[![IUpdating Windows](https://img.youtube.com/vi/MOL-pYqzcXM/0.jpg)](https://youtu.be/MOL-pYqzcXM)

▶ autounattended.xml:

  This is the unattended file that I use to solo boot into Windows as Administrator (System) and set the time to USET.

-----

▶ Known Issues:

1) ImageGlass10: Default extension hooks can get unset after an update. Run their "Set as default" wizard in Settings or manually set the files default program when going to view an image.

> If you find any other program oddities after updating please let me know through either the ![Issues Tracker](https://github.com/Eyevou/NTLitePresets/issues) or [NTLite Discord](https://discord.com/invite/UDMbgc6B5e). Thanks!
