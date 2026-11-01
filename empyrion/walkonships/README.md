# Walk On Ships (Empyrion: Galactic Survival)

Walk around inside ships while they fly. Work in progress: please report anything odd.

**Install:** download the newest `empyrion-walkonships-v*` zip from [Releases](../../../../releases),
unzip it, double-click `Install.bat`. Start the game with EasyAntiCheat off (mods don't load with it on).

**Automatic updates (recommended):** after `Install.bat`, it prints a line to paste into Steam
(Empyrion -> Properties -> General -> Launch Options), like:
`"<game folder>\Content\Mods\WalkOnShips\updater\Launch.bat" %command%`
Each time you press Play it installs the newest release (SHA-256 checked). If anything fails (offline, etc.)
the game just starts as normal; see `Content\Mods\WalkOnShips\updater.log`. Linux/Steam Deck: `launch.sh %command%`.

**Uninstall:** `Uninstall.bat`, or delete `Content\Mods\WalkOnShips` in the game folder.

**Something wrong in game:** press Ctrl+Shift+K (the mod stops; press again to turn it back on) and send the
`WalkOnShips*.log` files from `Content\Mods\WalkOnShips`.
