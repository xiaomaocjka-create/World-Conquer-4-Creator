# World Conquer 4 Creator

**English** | [简体中文](README.zh-CN.md)

Creator is an independent Windows tool for editing local scenarios, maps, events and unit deployments in **World Conqueror 4**, and exporting map images.

**Install the official PC version of World Conqueror 4 before using Creator. Creator cannot function normally without a compatible local game installation.**

## Official rights and tool boundaries

World Conqueror 4, its trademarks, artwork, audio and original game content belong to EasyTech and the respective rights holders. Creator is an independent project, not an official EasyTech product, and is not endorsed by EasyTech.

- Creator downloads contain no original game assets or game data and do not include the game. Required resources are read and prepared locally from your installed official PC game.
- Creator does not provide editing of out-of-battle currencies or account resources, such as owned generals. It does not grant paid currency, generals or other account entitlements.
- Its purpose is local scenario and map creation. It does not modify the game executable.
- Obtain the game through official channels, respect the rights holders, and follow the game's licence and terms. Installing Creator does not grant permission to redistribute original game assets.

## Install and use

1. Install the official Windows PC version of **World Conqueror 4**.
2. Download the complete **Windows-x64** bundle from [Releases](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/latest) and extract all files into a writable folder. The smaller `WC4Editor-<version>.zip` is an automatic-update payload, not a first-install bundle.
3. Run `WC4EditorLauncher.exe` and follow the prompts. Creator reads the local game installation and prepares resources on first use; no Python installation is needed.
4. Select a stage to edit, or open the guided tutorial in **Settings**. Change language under **Settings → Interface language**. Applying supported changes to the game requires a writable target directory.

## Work and updates

Work and generated resources are stored separately from the application under `%LOCALAPPDATA%\WC4Editor`. To update, close Creator, extract the complete new bundle into a new folder, and run its launcher. Updates preserve work; back up important projects.

## Validity and release protection

- **Each build has a 14-day offline validity period, with reminders from day 11.** See its release notes for exact dates.
- **After expiry, viewing and exporting remain available; editing, writing changes and deployment require a valid version.** Expiry does not delete existing work. Update to a valid release to continue editing.
- Signed manifests authenticate update packages. A signed online policy may also make a release read-only.
- Creator's own business implementation is distributed in compiled form to reduce direct source disclosure. Compilation does not prevent reverse engineering. Required third-party notices and sources remain available under their licences.

These measures manage Creator's releases and validity; they do not change ownership of the original game or its content.

## Third-party components

Applicable runtime terms are shown during installation; dependency notices are included in `resources/licenses`. The existing release provides the required component sources and replacement instructions:

- [FFmpeg source](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.3.0/NW-runtime-FFmpeg-source-0.118.0.tar.gz)
- [Blink source](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.3.0/NW-runtime-Blink-source-0.118.0.tar.gz)
- [Source and runtime replacement instructions](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.3.0/NW-runtime-source-instructions-0.118.0.zip)

These are third-party component sources, not Creator's own implementation.
