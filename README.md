# T6-Scarlett

Call of Duty: Black Ops II **Zombies**, running natively on **Xbox Series X|S** (codename Scarlett) and **Xbox One**, **in Developer Mode**, as a UWP game.

This repository only hosts the **playable builds** (see [Releases](../../releases)). The source code is not published here.

All of the game's features work, including **crossplay multiplayer**.

**Xbox One:** it works there too (tested). Performance is lower than on Series X|S and will be improved as soon as possible.

**Pre-alpha:** expect bugs, slow loading and crashes.

## Known issue: the game can freeze

The freezing problem is still in the game. The picture stops and you can't skip or press anything, but the sound keeps playing (seen in the intro cutscene of Mob of the Dead).

**To unfreeze it, press the Xbox button, then press B to go back to the game.** The sound can be out of sync after that.

This will be fixed in the next patch.

## What you need

- An Xbox console in **Developer Mode** (tested on Xbox Series X and Xbox One).
- Your own copy of the **PC game files** of Black Ops II. They are **not** included and never will be.
- A USB drive with about 25 GB free, or an FTP tool to send the game to the console's internal storage.
- A PC on the same network, to install the package through the Xbox Device Portal.

## Installing

Download the zip from the latest release and follow the `README.txt` inside it.

### Without a USB drive (FTP)

The game also runs from the console's internal storage. Send the game's files by FTP, together with the `custom` folder from the zip, to:

```
User Folders\LocalAppData\T6X.BlackOps2_...\LocalState\game\
```

Install the package and set it as a game first, then open it once so that the folder exists. When you open the game, no USB drive with a `T6X\game` folder can be plugged in: it would be used instead. Uninstalling the app deletes these files too.

## Thanks

- **Requiem** (Xbox, Android & Switch), our group: [Discord](https://discord.gg/7yDHBpxvwn)
- **Protarium**, for the servers that make the online mode possible: [Discord](https://discord.gg/e3SCtkWFhU)
- **Unbound** (Nintendo Wii U), [tonytrawl/bo2-unbound](https://github.com/tonytrawl/bo2-unbound): [Discord](https://discord.gg/4Jw79dXAev)

## Disclaimer

This is a fan project, not affiliated with or endorsed by Activision or Microsoft. Call of Duty and Black Ops are trademarks of Activision Publishing, Inc. You must own the game to use this.
