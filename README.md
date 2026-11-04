# Fabric Stock for Windows

[**Download the Windows installer**](https://github.com/Yao-6183/fabric-stock-downloads/releases/latest/download/FabricStock-Setup.exe)

Install on the office host PC (Windows 10/11, 64-bit), then open Fabric Stock.
Create a supervisor login and one shared staff login. Passwords need at least 3 characters.

Automatic updates are already enabled. No GitHub account or key is needed.
The app checks when opened and every hour while running. It backs up stock and
waits until stock pages close before installing a verified signed update.

Use the **Start with Windows** On/Off switch on the main host window.
For the optional visible window, open More actions → Windows startup.
Start with Windows is on by default after the first installed launch. Choose
whether to show the control window or start quietly in the tray. Windows must
be signed in; a switched-off or sleeping host cannot serve stock pages.

[Download the illustrated user guide](https://github.com/Yao-6183/fabric-stock-downloads/releases/latest/download/FabricStock-User-Guide.pdf)

For phone/tablet access, close the stock browser pages and open **Show QR code**
or **Local network** on the host. Choose your home/office Wi-Fi, confirm that you
trust it, and click **Enable Wi-Fi**. Approve Windows administrator permission
when asked; this allows only the selected local network on the app's port.
Join the same Wi-Fi on the phone, scan the QR and sign in. This simple option
uses an unencrypted local connection, as selected by the owner. It is not a
public internet link. If the network changes, sharing pauses until reconnected.

The installer is branded **ERIC**. This free build is not Windows code-signed,
so Windows can still display **Unknown publisher**. App update files have their
own verified signature; this is separate from Windows publisher identity.

This repository contains public installer/update downloads and instructions.
Office stock records and account data stay on the host PC. Development source is
maintained separately. Future approved releases appear at this same download link.
