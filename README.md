# NT Access

An editor and librarian for the [Expert Sleepers disting NT](https://www.expert-sleepers.co.uk/distingNT.html) Eurorack module, designed for screen reader users (NVDA, JAWS and Narrator on Windows, VoiceOver on macOS).

This repository holds the downloads. Get the latest version from the **[Releases page](https://github.com/RaisedBar/nt_access-releases/releases/latest)**.

## Downloads

- **Windows portable (64-bit)**: `NtAccess-<version>-Windows-portable-64bit.zip`. It holds a single `NtAccess.exe`, with no installer and no other files: unzip it anywhere and run it. Requires 64-bit Windows 10 or 11.
- **macOS universal (Apple silicon and Intel)**: `NtAccess-<version>-macOS-universal.zip`. It holds `NtAccess.app`; unzip it and move it to Applications. Requires macOS 11 or later.

The Mac app is not yet signed with an Apple Developer ID. The first time you open it, Control-click it (or VoiceOver: VO-Shift-M on the app for its shortcut menu) and choose Open, then Open again in the dialog. Alternatively, after trying to open it once, go to System Settings > Privacy & Security and choose Open Anyway.

## What it does

- Edit the module's preset: add, remove, move and rename algorithms, and change their parameters, mappings and routing, with every control labelled for screen readers.
- Copy presets and other files to and from the module's SD card.
- Make presets offline and upload them later.
- Read the module's display aloud, including which menu item is selected, and announce what changes on it (Device > Read Display, Ctrl+D; Device > Announce Display Changes, Ctrl+Shift+D).
- Operate the module's buttons, encoders and pots from the computer keyboard (Device > Remote Control, Ctrl+R).

Connect the disting NT by USB; its MIDI ports are called "disting NT". Press F1 in the program for help on the item with focus, and Shift+F1 for the list of keyboard shortcuts.

## Licence

NT Access is distributed under the MIT licence (see [LICENSE](LICENSE)). It includes other open source software, compiled into the program; their licences are in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).

NT Access is made by Raised Bar and is not affiliated with Expert Sleepers. The context-sensitive help is derived from the disting NT User Manual, with kind permission of Expert Sleepers.
