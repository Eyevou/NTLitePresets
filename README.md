<h1>Windows 11 Presets for NTLite</h1>
<h5>The goal of this preset is to give you the most barebones install while maintaining as much compatibility for everything you probably care about. This preset is a good starting point for Gaming, Video editing, streaming, and much more!</h5><hr>
<h3>Everyone wants something different from their Windows experience. Why not start here?</h3>

🔴 Important Notes and File Descriptions 🔴

▶ Script Descriptions:

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

▶ How to use, step-by-step:

1) Download an installation ISO from Microsoft and the XML files from the repo.
2) Mount the ISO, by double clicking the file you got from Microsoft.
3) Copy/paste the contents of the mounted drive into a newly created folder on your desktop.
4) Open NTLite.
5) Drag and drop the XML files you downloaded from this github page into NTLite.
6) Drag and drop the folder you made on the desktop, that contains the ISO files, into NTLite.
7) Find the edition you want to apply the preset to, right-click it, click "Remove Editions".
8) Check the box beside all editions you don't want. Click "Ok".
9) When it finishes double click on the edition and mount it, wait for it to complete.
10) After it's loaded, go into Updates and click "Add" then "Latest Updates".
11) Add the latest Cumulative Update, .NET framework, and security updates then click Enqueue.
12) Click "Drivers" then "Import Host".
13) Click "Image" then under "Preset" double click "01.WinXX-Components_XXXX.xml".
  13a) (Optional) If there are additional component presets you'll want to right-click them and select "Load - Merge"
14) Click "Apply" then "Process".
15) Wait for everything to complete.
16) (SKIP if attempting to UPDATE an install) Open the folder on your desktop containing your install media and add "autounattended.xml" into the directory, where setup.exe is.
17) Drag and drop all the files onto a USB Flash drive.
    17a) If Updating just double click setup.exe from the USB drive. If done correctly the installer WILL NOT prompt you for a drive to install to.
18) Restart and boot into the installation process.

-----

▶ Known Issues:

1) ImageGlass10: Default extension hooks can get unset after an update. Run their "Set as default" wizard in Settings or manually set the files default program when going to view an image.

> If you find any other program oddities after updating please let me know through either the ![Issues Tracker](https://github.com/Eyevou/NTLitePresets/issues) or [NTLite Discord](https://discord.com/invite/UDMbgc6B5e). Thanks!
