---
title: Classic Taskbar Groups support
permalink: /classic-taskbar-groups/
---
# Classic Taskbar Groups support

_Last updated: November 23, 2026_

Classic Taskbar Groups is published by Deck-Of-Jacks.

**Found a problem?** [Report an issue](https://github.com/IanD-Bot/support/issues/new?template=classic-taskbar-groups.yml)

## About this app

Classic Taskbar Groups puts apps, shortcuts, files, folders and web links into folder buttons on the Windows taskbar. Each folder is one button with its own icon. Clicking it opens a small popup of that folder's contents. It is local-only: no telemetry, no accounts, no ads, and no network connections of its own.

## Requirements

Windows 10 version 2004 (build 19041) or later, 64-bit. Windows 11 is the supported release. Windows 10 is best effort.

## Install and launch

Install the app from the Microsoft Store, then open it from the Start menu. You can also launch it from Classic Control if that app is installed. Opening the app with no arguments shows Settings. `ClassicTaskbarGroups.exe --tray` starts the notification-area helper without opening Settings.

## Folders and items

In Settings, create a folder, then add apps, shortcuts, files, Explorer folders and web links. Each folder can use a grid or a list layout. You can pick a built-in icon, or an icon from an .ico, a .png, or an .exe or .dll.

Use **Pin to taskbar...** in Settings to create a shortcut for the folder, then follow the on-screen steps to pin it. The shortcut is stored with the app, not on the desktop or in the Start menu. On Windows 11 the steps include **Show more options**. On Windows 10, right-click the shortcut and choose **Pin to taskbar**.

## Behavior and the tray

Open the **Behavior** tab in Settings.

- **Hover-to-open** is off by default. When you turn it on, resting on a pinned folder button for the delay you set (100 to 5000 milliseconds, default 400) opens that folder. A quick pass across the button does not. Clicking a button still opens the folder when hover is off. The tray helper needs to be running for hover-to-open.
- **Start with Windows** is off until you opt in. The packaged app uses a Windows startup task; the unpackaged exe uses a shortcut in the Startup folder.
- The notification-area icon lists your folders, opens Settings, and follows Windows dark or light mode. A left click opens Settings. If the icon is in the overflow (^), drag it onto the taskbar.

## Backup

On the **Backup** tab, export your folders, items, icons and settings to one file, or import a file you saved earlier. Import replaces the current setup. It does not turn on Start with Windows.

## Common questions

- **A folder has no taskbar button.** Pin it from Settings with **Pin to taskbar...** and finish the on-screen steps. Until it is pinned, opening the folder still works from Settings, the tray menu, or `ClassicTaskbarGroups.exe --folder <id>`.
- **Hover-to-open does nothing.** Turn it on in Settings > Behavior, confirm the tray helper is running, and rest on the pinned button for the delay. Hover-to-open is optional and off by default.
- **An item says Missing.** The file, shortcut, folder or app is gone. Choosing it does not crash. It stays in the list until you remove it or restore the target.
- **Import did not turn on Start with Windows.** That is by design. Turn it on in Settings > Behavior if you want it.
- **Where is my setup stored?** In a settings folder in your Windows user profile. Uninstalling the packaged app removes it.

## Reset and uninstall

To replace your folders with a backup, import a file on the Backup tab. To remove the app, uninstall it from Settings > Apps. Uninstalling the packaged app removes its data. If you turned on Start with Windows for the unpackaged exe, turn it off in Settings first, or delete the Startup folder shortcut after uninstalling.

## Report a problem

[Report an issue](https://github.com/IanD-Bot/support/issues/new?template=classic-taskbar-groups.yml) on GitHub. Issues are public. Please don't include personal information in the issue.

## Privacy

See the [Classic Taskbar Groups privacy policy](https://privacy.deckofjacks.com/classic-taskbar-groups).
