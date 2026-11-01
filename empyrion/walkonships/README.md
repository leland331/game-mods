# Walk On Ships (Empyrion: Galactic Survival)

Walk around inside ships while they fly. Work in progress: please report anything odd.

## Download

**[WalkOnShips-install.zip](https://github.com/leland331/game-mods/releases/download/empyrion-walkonships-latest/WalkOnShips-install.zip)** (always the newest version)

1. Download the zip above and unzip it anywhere.
2. Close the game, then double-click `Install.bat` (it finds the game through Steam by itself).
3. Start Empyrion with EasyAntiCheat **off** (untick EAC in the game's launcher; mods don't load with it on).

That's all. The mod keeps itself up to date: each time the game starts it checks for a newer tested version in the
background (SHA-256 checked) and uses it from the next start. Offline or any problem: the game just starts with what you
have. What it did is in `Content\Mods\WalkOnShips\updater.log`. To turn updates off, put an empty file named `no-update` there.

**Install by hand (Linux/Proton, Steam Deck):** copy the `WalkOnShips` folder from the zip into the game's `Content\Mods` folder.

**Uninstall:** `Uninstall.bat`, or delete `Content\Mods\WalkOnShips` in the game folder.

**Something wrong in game:** press Ctrl+Shift+K (the mod stops; press again to turn it back on) and send the
`WalkOnShips*.log` and `updater.log` files from `Content\Mods\WalkOnShips`.

Older versions: [Releases](../../../../releases) (tags `empyrion-walkonships-v*`).
