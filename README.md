# Empyrion Scenario Editor

Official Windows downloads for the **Empyrion Scenario Editor** by LumaSoftWorks.

This repository holds release files only. It does not contain source code, backend code, or configuration.

Current release: **1.0.4 Beta** (internal build 1.3.56), published as a pre-release.

## Requirements

- Windows
- [Empyrion - Galactic Survival](https://store.steampowered.com/app/383120/Empyrion__Galactic_Survival/) (the editor uses your Steam game and Workshop paths; it does not modify original scenarios or the game's files)

## Install

**Recommended — installer (Setup 1.0.2)**

1. Download `ScenarioEditorSetup.exe` from the [latest release](https://github.com/Kanade-Tachibana/Empyrion-Scenario-Editor/releases/tag/v1.0.4-beta).
2. Run the installer. It uses the official update feed and checks the download size and SHA-256 hash before installing.
3. The installer is **not code-signed**. Windows SmartScreen may say "Windows protected your PC". Click **More info**, then **Run anyway**.

**Manual — release zip**

1. Download `EmpyrionScenarioEditor-1.3.56.zip` from the same release.
2. Verify the SHA-256 hash below.
3. Unzip the archive and run `EmpyrionScenarioEditor.exe`.

After install, the Update page can use the public feed at [api.lumasoftworks.com](https://api.lumasoftworks.com) or a local update folder. Downloads are size- and hash-checked, backed up, and installed only after you choose Restart to finish. If the new version does not start healthy, it rolls back.

## SHA-256

| File | Size | SHA-256 |
| --- | ---: | --- |
| `ScenarioEditorSetup.exe` (Setup 1.0.2) | 116,736 bytes | `48618A0206141484B29B12F963B9681483285BECB31646E3A269881274C87321` |
| `EmpyrionScenarioEditor-1.3.56.zip` (1.0.4 Beta) | 3,803,831 bytes | `16C2DE55831058BA47ECF23238CBCA00F9A0DBA222D9FCBE8B3FFC16BCFC06AF` |

## What the editor can do

**Scenario authoring**

- Open an official or Workshop scenario read-only, then create a working copy in a new named folder. Original scenarios and the game's files are never changed.
- Review & save shows a diff for every changed file, writes a timestamped `.bak` first, and records edits in History (undo, search, restore a backup).
- Edit galaxy and stars, sectors, playfields, blocks and items, templates and recipes, loot, traders, factions, the tech tree, tokens, dialogues, quests / PDA, localization, status effects, creatures / NPCs, weapons, ores, custom assets, files, and loading screens.
- Animated star preview (a stylised approximation, not the game shader) and a galaxy map for star regions, faction territories, and sector systems.
- Dedicated pages for Playfields (planets, moons, space, and orbits, with sliders, where-used, checks, templates, and compare), Creatures / NPCs, Traders, Status Effects, Damage & Materials, and a Files page with a tabbed code editor and live validation.
- Scenario Validator (Tools > Validation) checks YAML / ECF structure, keys, references, and file damage, with explanations and one-click fixes staged through History.
- Build a small loadable test scenario from your changes (minimal mode, or vanilla mode as a fallback).

**Workshop, blueprints, and community**

- Public Workshop (Extensions, Resources, Tools, and Blueprints) from [api.lumasoftworks.com](https://api.lumasoftworks.com). Every package is SHA-256 checked before it is unpacked.
- Browse, filter, search, and download shared blueprints (Base/POI, CV, SV, HV). A download that would replace a blueprint you already have asks first and keeps a backup. Uploading needs Steam sign-in.
- My Blueprints can upload a local blueprint to the Workshop (name, class, `.epb`, and thumbnail are filled in). Your Saves files are only read, never changed.
- Owners can edit title, description, icon, screenshots, and YouTube videos. Click a screenshot to view it full size; owners can remove, reorder, or restore screenshots (up to 8). Official items by the developer show a verified check mark.
- Install Blueprint Viewer from the public Workshop (the package is SHA-256 checked).
- Sign in through Steam via a LumaSoftWorks page. The editor never sees your password.
- Forum sections for Bug Reports, Suggestions, Changelog, and Servers, with screenshots, replies, status badges, and view counts.
- A Discord button opens the Scenario Editor community.

**Updates and safety**

- Online features need the Scenario Editor service. If you are offline or the service is down, authoring keeps working.
- Nothing is written to an original scenario or to the game's files. Do not edit an active game save.

## Links

- Official API and update feed: https://api.lumasoftworks.com
- Releases on this repository: https://github.com/Kanade-Tachibana/Empyrion-Scenario-Editor/releases
