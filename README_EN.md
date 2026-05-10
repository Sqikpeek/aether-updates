# Aether Launcher

Aether Launcher is a Minecraft launcher with containers, Modrinth content installation, auto updates, and a separate data storage folder.

## Links

- GitHub: https://github.com/Sqikpeek/Aether
- Releases: https://github.com/Sqikpeek/Aether/releases
- Installer download: open the latest release and download `Aether Installer.exe`
- Update package: the latest release uses `Aether Update.zip`

## Features

- Separate containers for different Minecraft versions and mod sets.
- Vanilla, Fabric, Quilt, Forge, and NeoForge support.
- Search and install mods, modpacks, data packs, and plugins from Modrinth.
- Shared saves between containers.
- Java auto-detection and memory settings.
- Game log copying for troubleshooting.
- Launcher auto updates through GitHub Releases.
- UI themes and instant language switching.

## Installation

1. Open the Releases page.
2. Download `Aether Installer.exe` from the latest release.
3. Run the installer and choose the storage folder.
4. The installer downloads `Aether Update.zip`, extracts the launcher, and creates a shortcut.

## Release Assets

Each new GitHub Release should include two files:

- `Aether Installer.exe` - the installer.
- `Aether Update.zip` - the launcher package used for installation and auto updates.

The installer and updater select `Aether Update.zip` and do not use `Aether Installer.exe` as an update package.
