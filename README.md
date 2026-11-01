# Game Mods

Mods for PC games, ready to install. Each game has an easy installer app; you don't need to touch any files.

| Game | Mod | What it does | Status |
|---|---|---|---|
| Empyrion: Galactic Survival | [Walk On Ships](empyrion/walkonships/) | Walk around inside ships while they fly, also in multiplayer | Play test |

## Empyrion: Galactic Survival

### Install

1. Download the **Empyrion Mod Manager**:
   - **Windows:** [EmpyrionModManager.exe](https://github.com/leland331/game-mods/releases/download/empyrion-modmanager-v1.0.1/EmpyrionModManager.exe)
   - **Linux / Steam Deck (desktop mode):** [EmpyrionModManager-x86_64.AppImage](https://github.com/leland331/game-mods/releases/download/empyrion-modmanager-v1.0.1/EmpyrionModManager-x86_64.AppImage)
2. Close the game and open the manager.
   - **Windows:** if it says "Windows protected your PC", click **More info**, then **Run anyway**.
   - **Linux:** right-click the file, open **Properties**, tick **Allow executing**, then double-click it.
3. The manager finds your game by itself. If it can't, click **Change...** and pick the game folder.
4. Click **Install** next to a mod. Later, the same button says **Update** when a new version is out.
5. Start Empyrion with **EasyAntiCheat off** (untick EAC in the game's launcher). Mods don't load while EAC is on.

**Multiplayer:** the server needs the same mod version. Each mod's page explains the server install.

## Releases

The [Releases](../../releases) page lists every download. Each mod and the manager have their own version line:

| Tag | What it is |
|---|---|
| `empyrion-modmanager-v…` | Empyrion Mod Manager (the installer app) |
| `empyrion-walkonships-v…` | Walk On Ships: the mod and its server package |

Every file comes with a `.sha256` checksum. The manager checks it before it installs anything.
