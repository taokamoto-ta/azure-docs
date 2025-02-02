---
title: What's new in the Remote Desktop WebRTC Redirector Service?
description: New features and product updates the Remote Desktop WebRTC Redirector Service for Azure Virtual Desktop.
author: Heidilohr
ms.topic: release-notes
ms.date: 11/27/2023
ms.author: helohr
manager: femila
ms.custom: references_regions
---

# What's new in the Remote Desktop WebRTC Redirector Service

This article provides information about the latest updates to the Remote Desktop WebRTC Redirector Service for Teams for Azure Virtual Desktop, which you can download at [Remote Desktop WebRTC Redirector Service](https://aka.ms/msrdcwebrtcsvc/msi).

## Latest available version

The following table shows the latest available version of the Remote Desktop WebRTC Redirector Service.

| Release | Latest version | Download |
|---------|----------------|----------|
| Public | 1.45.2310.13001 | [MSI Installer](https://aka.ms/msrdcwebrtcsvc/msi) |

## Updates for version 1.45.2310.13001

*Published: November 15, 2023*

Download: [MSI Installer](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RW1eNhm)

In this release, we've made the following change:

- Added support for Teams optimization reinitialization upon virtual machine (VM) hibernate and resume.

## Updates for version 1.43.2306.30001

*Published: September 7, 2023*

Download: [MSI Installer](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RW1bg9v)

In this release, we've made the following changes:

- If a user is sharing a PowerPoint edit window then selects **Present**, the shared window will automatically switch to the PowerPoint presentation window.
- Improved WebRTC redirector service reliability and performance handling.
- Fixed an issue where the diagnostic overlay hotkey (<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>;</kbd>) caused hotkeys to be disabled for non-Teams applications during Teams calls.
- Fixed an issue where a race condition caused a loss of audio during Teams calls.

## Updates for version 1.33.2302.07001

*Published: March 1, 2023*

Download: [MSI Installer](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RWWDIg)

In this release, we've made the following change:

- Support for non-Latin characters for window names in the application window share tray.

## Updates for version 1.31.2211.15001 

*Published: January 19, 2023*

Download: [MSI Installer](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE5c8Kk)

In this release, we've made the following changes:

- Support for application window sharing for Windows users.
- Support for Give and Take Control functionality for macOS users.
- Latency and performance improvements for Give and Take Control on Windows.
- Improved screen share performance.

## Updates for version 1.17.2205.23001

*Published: June 20, 2022*

In this release, we've made the following changes:

- Fixed an issue that made the WebRTC redirector service disconnect from Teams on Azure Virtual Desktop.
- Added keyboard shortcut detection for Shift+Ctrl+; that lets users turn on a diagnostic overlay during calls on Teams for Azure Virtual Desktop. This feature is supported in version 1.2.3313 or later of the Windows Desktop client.
- Added further stability and reliability improvements to the service.

## Updates for version 1.4.2111.18001

*Published: December 2, 2021*

In this release, we've made the following changes:

- Fixed a mute notification problem.
- Multiple z-ordering fixes in Teams on Azure Virtual Desktop and Teams on Microsoft 365.
- Removed timeout that prevented the WebRTC redirector service from starting when the user connects.
- Fixed setup problems that prevented side-by-side installation from working.

## Updates for version 1.1.2110.16001

*Published: October 15, 2021*

In this release, we've made the following changes:

- Fixed an issue that caused the screen to turn black while screen sharing. If you've been experiencing this issue, confirm that this update will resolve it by resizing the Teams window. If screen sharing starts working again after resizing, the update will resolve this issue.
- You can now control the meeting, ringtone, and notification volume from the host VM. You can only use this feature with version 1.2.2459 or later of [the Windows Desktop client](/windows-server/remote/remote-desktop-services/clients/windowsdesktop-whatsnew).
- The installer will now make sure that Teams is closed before installing updates.
- Fixed an issue that prevented users from returning to full screen mode after leaving the call window.

## Updates for version 1.0.2106.14001

*Published: July 29, 2021*

In this release, we've made the following change:

- Increased the connection reliability between the WebRTC redirector service and the WebRTC client plugin.

## Updates for version 1.0.2006.11001

*Published: July 28, 2020*

In this release, we've made the following changes:

- Fixed an issue where minimizing the Teams app during a call or meeting caused incoming video to drop.
- Added support for selecting one monitor to share in multi-monitor desktop sessions.

## Next steps

Learn more about how to set up Teams on Azure Virtual Desktop at [Use Microsoft Teams on Azure Virtual Desktop](teams-on-avd.md).

Learn about known issues, limitations, and how to log issues at [Troubleshoot Teams on Azure Virtual Desktop](troubleshoot-teams.md).
