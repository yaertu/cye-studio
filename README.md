# CYE Studio 4.3.0

Developer: **yaaertu codeR**

CYE Studio is a Windows x64 desktop visual effects app. It changes the Windows system selection color for apps that respect system colors, adds a desktop selection glow, cursor glow, and a premium taskbar visualizer.

## What's included

- RGB selection color presets and sliders
- Five visually different premium taskbar modes: Aurora Glass, Crystal Spectrum, Inferno EQ, Cyber Scan, and Meteor Storm
- Music-level reaction through local Windows output metering
- Tray-first always-on behavior: pressing X hides the window, the app keeps running
- Desktop drag selection overlay and cursor click pulse
- Embedded logo, icon, and **yaaertu codeR** signature

## Install

1. Download `CYE Studio.exe` from the release.
2. Run it on Windows x64.
3. Double-click the tray icon or the desktop shortcut to open it again.
4. Use **Kapat ve geri yükle** inside the app when you want to fully exit and restore Windows colors.

The EXE is self-contained; users do not need to install .NET separately.

## Notes

Some apps draw their own themes and may ignore Windows system selection colors. CYE uses Windows APIs for supported apps and separate transparent overlays for desktop/taskbar effects. The visualizer reads only the local system output peak level; it does not record, save, or upload audio.

This public package does not include source code. Source is private to the owner.

## Verification

Self-test result for this release: 7 passed checks, including RGB apply/restore, crash recovery, and invalid recovery rejection.

SHA256 for `CYE Studio.exe`:

```text
4D2FA374CA5C64EC6301A0F6BE2F38D1D39BC4BB730613AAE26187EF40659E72
```

Copyright © 2026 yaaertu codeR. All rights reserved.
