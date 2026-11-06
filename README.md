
<p align="center">
  <img src="assets/azura-tools-icon.png" alt="Azura Tools" width="96">
</p>

<h1 align="center">Azura Tools</h1>

<p align="center">
  Overlays and utilities for SpiritVale, all in one Windows application.
</p>

<p align="center">
  <strong>Version 0.10.23</strong> · Windows x64 · Portable
</p>

---

## What's Included

| Module | Description |
| --- | --- |
| **Boss Skills** | Tracks skill casts from up to three bosses and alerts you to Umbral Collapse. |
| **Boss DPS** | Displays up to three encounters with DPS, TPS, and HPS modes. Only DPS history is saved. |
| **Personal DPS** | Independently tracks the local player's damage against up to three valid targets. |
| **Skill Reminder** | Displays up to three cooldown reminders, each with its own customizable widget. |
| **Boss Elements** | Recommends elements for bosses in the catalog. |
| **Build Export** | Saves inspected builds and opens their links in the SpiritValers planner. |
| **Item Refine** | Automates item refinement using coordinate capture and Safe verification. |
| **Hotkey Macro** | Manage sequences, profiles, and hotkeys directly from the launcher, powered by AutoHotkey v1.1. |

All overlays support customizable positioning, size, opacity, and visibility. AzuraBossTracker is a separate application.

## Installation

1. Download the ZIP file from the [latest public release](https://github.com/iurirs/Spiritvale-Azura-Tools-Downloads/releases/latest).
2. Extract **all** files into a folder and run `azura-tools/AzuraTools.exe`.
3. Install [Npcap](https://npcap.com/#download) to capture game data. To use Hotkey Macro, also install [AutoHotkey v1.1 64-bit](https://www.autohotkey.com/download/1.1/).
4. Launch SpiritVale and check the capture status in the **SpiritVale Session** panel. The **Requirements** tab lists all prerequisites.

Node.js and Bun are not required to run the application. History and settings are stored in `%LOCALAPPDATA%\AzuraTools` and are not included in the ZIP package.

## Notes

This repository contains only download information and releases. The application checks for the latest stable release when it opens and displays a notification when a new version is available. Updates are performed manually using a ZIP file.
