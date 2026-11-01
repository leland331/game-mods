# Walk On Ships

*A mod for Empyrion: Galactic Survival*

Walk around inside your ships while they fly, in single player and multiplayer.
It's still being play-tested, so please report anything odd.

## Features

- Walk, jump and build inside a moving ship. You stay where you are instead of being left behind.
- Other players aboard move smoothly with the ship.
- Log out on a flying ship and you're back aboard when you log in.
- Warps: players standing on the ship come along (still being tested).
- Locked ships: players who aren't allowed aboard are placed just outside.

## Install (players)

Use the **Empyrion Mod Manager**. The download and steps are on the [main page](https://github.com/leland331/game-mods#install).
Then start the game with EasyAntiCheat off.

## Install (dedicated server)

1. Download `WalkOnShipsServer-empyrion-walkonships-v<version>.zip` from the newest
   [Walk On Ships release](https://github.com/leland331/game-mods/releases?q=empyrion-walkonships&expanded=true).
2. Stop the server and delete any old `Content/Mods/WalkOnShipsServer` folder.
3. Unzip the file into the server's `Content/Mods/` folder.
4. Turn EasyAntiCheat off for the server, then start it.

Players need the same version as the server. If the server's mod is missing a part or fails to start, players get
"Can't connect: WalkOnShips error" instead of joining a half-working game. The details are in the server log.

## Uninstall

In the Mod Manager, click **Uninstall**. Or delete `Content/Mods/WalkOnShips` in the game folder.

## Problems

Send the `WalkOnShips*.log` files from `Content/Mods/WalkOnShips` (on a server, `Content/Mods/WalkOnShipsServer`).
