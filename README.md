# NT Access

An editor and librarian for the [Expert Sleepers disting NT](https://www.expert-sleepers.co.uk/distingNT.html) Eurorack module, designed for screen reader users (NVDA, JAWS and Narrator on Windows, VoiceOver on macOS).

The latest version is always on the **[Releases page](https://github.com/RaisedBar/nt_access-releases/releases/latest)** of the nt_access-releases repository on GitHub.

## Downloads

- **Windows portable (64-bit)**: `NtAccess-<version>-Windows-portable-64bit.zip`. It holds `NtAccess.exe` and these notes, with no installer: unzip it anywhere and run `NtAccess.exe`. The program is a single file that needs nothing else. Requires 64-bit Windows 10 or 11.
- **macOS universal (Apple silicon and Intel)**: `NtAccess-<version>-macOS-universal.zip`. It holds `NtAccess.app` and these notes; unzip it and move `NtAccess.app` to Applications. Requires macOS 11 or later.

The Mac app is not yet signed with an Apple Developer ID. The first time you open it, Control-click it (or VoiceOver: VO-Shift-M on the app for its shortcut menu) and choose Open, then Open again in the dialog. Alternatively, after trying to open it once, go to System Settings > Privacy & Security and choose Open Anyway.

## What it does

- Edit the module's preset: add, remove, move and rename algorithms, and change their parameters, mappings and routing, with every control labelled for screen readers.
- Copy presets and other files to and from the module's SD card.
- Make presets offline and upload them later.
- Export a preset's MIDI mappings as an instrument definition for Asp, the accessible sequencer platform (File > Export as Asp Instrument, Ctrl+E).
- Read the module's display aloud, including which menu item is selected, and announce what changes on it (NT > Read Display, Ctrl+T; NT > Announce Display Changes, Ctrl+Shift+T).
- Operate the module's buttons, encoders and pots from the computer keyboard (NT > Remote Control, Ctrl+R).

Connect the disting NT by USB; its MIDI ports are called "disting NT". Press F1 in the program for help on the item with focus, and Shift+F1 for the list of keyboard shortcuts.

## Licence

NT Access is distributed under the MIT licence: see the file LICENSE.txt. It includes other open source software, compiled into the program; their licences are in the file THIRD-PARTY-NOTICES.txt. Both files come with every download.

NT Access is made by Raised Bar and is not affiliated with Expert Sleepers. The context-sensitive help is derived from the disting NT User Manual, with kind permission of Expert Sleepers.
