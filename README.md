# Starfield Console Commands

This page is a searchable list of every console and script command in Starfield. It was read from the game's own command table in `Starfield.exe` (game version 1.16.244.0).

**View it here:** https://taosecurity.github.io/starfield-console-commands/

## Example

1. Open the page and type `god` in the search box.
2. The row for `ToggleGodMode` shows its short form `TGM` and the game's own help text: "Toggle God mode (infinite health/stamina/magicka)."
3. Click the name to copy the short form, then press ~ in the game (PC only), paste it and press Enter.

God mode turns on, which by the game's help text gives you infinite health and stamina. Type `tgm` again to turn it off.

## Using the console

On PC, press the **~** key (the key under Esc) to open the console, type or paste the command, and press Enter. Xbox and PlayStation have no console. Using the console turns off achievements for that save unless you use a mod that keeps them on.

## What's on the page

- The page lists 1,527 commands in 15 topics, with a "Most commonly used" group first.
- Each command shows its short form, parameters and the game's own help text, plus an example built from real game IDs.
- You can search, filter by console or script commands, and click a name to copy it.

What's new: see the top of the [live page](https://taosecurity.github.io/starfield-console-commands/).

## Words used here

- **Console:** the PC command line inside the game, opened with ~.
- **Record:** one thing in a plugin, such as a weapon, a quest, a location or a setting.
- **Plugin:** a mod's data file (`.esm`, `.esp` or `.esl`). It adds or changes records in the game.
- **Form ID:** a record's number, such as `0002B560`. The first two digits depend on the load order.
- **Editor ID:** a record's readable name, such as `Ammo_556`, used by the Creation Kit and xEdit.
- **Reference:** one copy of a thing placed in the world. Commands marked "Target" work on the reference you click while the console is open, or on `player.` when you put it in front.

## How it was made

- The command names, short forms, parameters and help text were read from the command table in `Starfield.exe`, game version 1.16.244.0.
- Commands that SFSE plugins add are not included.
- The examples were not run in the game. They show a valid shape with real values.
- The list is regenerated after game updates.

## Found a mistake?

Open an issue: https://github.com/taosecurity/starfield-console-commands/issues

## Credits and license

Richard Bejtlich of [Richard Presents Starfield Essentials](https://www.youtube.com/@RichardBejtlich) made this page. More Starfield tools and references are on the [Richard Presents Development Hub](https://taosecurity.github.io/).

This is an unofficial list, not made or endorsed by Bethesda. Starfield is a trademark of ZeniMax Media. The command names and help text are the game's own.

The page is a single self-contained `index.html` with no external dependencies. Its code (layout, search and copy features) is under the MIT license; see [LICENSE](LICENSE).
