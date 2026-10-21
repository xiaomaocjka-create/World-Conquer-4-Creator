# World Conquer 4 Creator

**English** | [简体中文](README.zh-CN.md)

A local scenario and map editor for **World Conqueror 4**, distributed as a Windows desktop application. This repository holds release packages and documentation.

## Download and start

1. Download **World-Conquer-4-Creator-0.2.9-Windows-x64.zip** from [Releases](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/latest).
2. Extract the entire bundle into a writable folder.
3. Run `WC4EditorLauncher.exe` and follow the installation prompts.

**To update:** Close the editor, extract the complete new Windows-x64 ZIP into a new folder, and run its `WC4EditorLauncher.exe`. The launcher preserves existing work. `WC4Editor-0.2.9.zip` is an automatic-update payload, not the first-install package.

Python installation is not required. A compatible local game installation is required; resources are generated locally on first use. Game assets and game data are excluded from these downloads.

The editor defaults to English. Use **Settings → Interface language** to switch to Simplified Chinese. Open the guided tutorial from Settings; it walks through creating a stage and introduces the editors through guided interactions in the editor. Version 0.2.9 was verified on the maintainer's Windows 11 PC with Python removed from the program's search environment; this is not a separate clean-PC test.

## Editing and your work

Edit scenarios, events, unit deployments, airstrikes and conquest maps. Export ordinary and conquest maps from the desktop window.

Program versions, generated resources, work and backups are stored separately under `%LOCALAPPDATA%\WC4Editor`. Updates preserve work. Keep your own backups of important projects.

Protected game directories can supply resources. Deployment requires a writable target and updates supported battle files together with their verification records. The editor does not patch the game executable.

## Compiled implementation

The editor's own Python and JavaScript business logic is compiled, including map and unit rendering, animation, editor interactions, selection, catalogues and updates. Readable implementation `.py`/`.js` files are excluded from the release and are not served by localhost.

HTML/CSS, loading signals, data and UI strings, dynamic event-call expressions and GPU shader strings remain visible. Compiled binaries can be reverse engineered; this is not a promise of absolute secrecy or a completed C++ rendering rewrite.

## Updates and validity

Signed manifests authenticate update packages. A prepared update takes effect on the next launch. Activation recovery preserves the preceding version and work.

Each build has a 14-day offline validity period, with reminders from day 11. After expiry, viewing and exporting remain available; editing and deployment require a valid version. A signed online policy can also make a release read-only. Exact dates appear in the release notes.

## Third-party components

Installation presents the applicable Windows runtime terms. Dependency notices are included in the installation's `resources/licenses` directory. FFmpeg LGPLv2.1+ and Blink source and replacement instructions are provided on the same release:

- [FFmpeg source](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.2.9/NW-runtime-FFmpeg-source-0.118.0.tar.gz)
- [Blink source](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.2.9/NW-runtime-Blink-source-0.118.0.tar.gz)
- [Source and runtime replacement instructions](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.2.9/NW-runtime-source-instructions-0.118.0.zip)

These are third-party component sources, not the editor's implementation. Downloads exclude game assets, game data, user projects, research, repository history and signing private keys. The 0.1.0 release was withdrawn; 0.2.4 remains an unpublished draft.

This independent project is not an official EasyTech product. World Conqueror 4 and its assets belong to their respective owners.
