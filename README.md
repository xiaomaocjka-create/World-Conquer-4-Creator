# World Conquer 4 Creator

**English** | [简体中文](README.zh-CN.md)

A local scenario and map editor for **World Conqueror 4**. This repository contains Windows release packages and release notes.

## Download and start

1. Download the Windows x64 bundle from [Releases](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/latest).
2. Extract the entire bundle into a writable folder.
3. Run `WC4EditorLauncher.exe` and follow the setup prompts.

The bundle includes its runtime; you do not need to install Python. A compatible local game installation is required. The editor prepares its resources from your installation on first use; game assets are not included in these downloads.

The current release has been tested on the maintainer's Windows 11 PC. Its editor interface remains in Simplified Chinese; the language links above switch this documentation.

## Your work and game installation

The editor keeps program versions, generated resources, your work, and backups in separate directories under `%LOCALAPPDATA%\WC4Editor`. Updates preserve your work. Keep your own backups of important projects.

Protected game directories can be used as resource sources. Deployment requires a writable target; the editor refuses protected writes. It does not move your installed game or modify the game executable. Supported battle deployments update the corresponding battle verification records together with the battle file.

## Updates and version validity

Updates use signed manifests and verify downloaded packages before installation. A new version takes effect on the next launch; a failed activation restores the preceding version.

Each release has a 14-day offline validity period. Update reminders begin on day 11. After expiry, viewing and exporting remain available, while editing and deployment require a valid version. A signed online policy may also place a release in read-only mode.

## Distribution

These downloads contain the editor program and its dependency notices. They exclude game assets, game data, user projects, research files, repository history, and signing private keys. Third-party notices are included under `resources/licenses` in the bundle.

This project is independent and is not an official EasyTech product. World Conqueror 4 and its assets belong to their respective owners.
