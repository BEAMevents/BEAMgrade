# BEAMgrade

Live colour grading for events by [BEAM Events](https://beamevents.com). It grades a camera or Blackmagic input in real time, sends the result out a Blackmagic DeckLink card, and exports the grade as a 3D LUT (.cube).

This repository only holds the **Windows installers and updates**.

## Download
Get the latest version from **[Releases](https://github.com/BEAMevents/BEAMgrade/releases/latest)**:

- **BEAMgrade-Setup-x.y.z.exe** installs BEAMgrade and **updates itself automatically**. Use this one.
- **BEAMgrade-Portable-x.y.z.exe** runs without installing (e.g. from a USB stick). It tells you when a newer version is out, but doesn't update itself.

The installers aren't code-signed yet, so Windows SmartScreen may warn on first launch: click **More info → Run anyway**.

## Updates
The installed version checks for updates in the background and shows **Update x.y.z ready** in its header. Click it, then **Install & restart**. Updates never install while the output is live.
