# Lucid Blocks Recipe Browser Mod

## Description
Adds an in-game Fusion Browser overlay that lets players preview the
result of any item combination using the game's procedural fusion
(Apotheosis / crafting) system without leaving the game.

Press T while playing to open or close the browser. The game's cursor
is released while the browser is open so you can click items freely.

## How fusion works
Crafting in Lucid Blocks is procedural: items are not crafted from
explicit recipes. Instead, up to 6 items are placed into the Apotheosis
machine and their essence properties (energy, clay, phlegm, mercury,
aqua, utility, danger, wearability, hate, lust, faith, rank, bias, tags)
are combined into a weighted mood vector. The game then finds the item
whose essence is closest to that vector and returns it as the result.
Duplicate items in the slots are merged — their counts are summed before
the mood vector is calculated.

## Features
- Searchable item list: all items from ItemMap, sorted alphabetically.
  Type in the search box to filter by name.
- 6 ingredient slots in a 3×2 grid matching the in-game Apotheosis
  machine. Each slot shows the item icon and name.
- Per-slot ✕ button: clears only that one slot.
- Clear All button: empties all 6 slots at once.
- Live result preview: updates immediately whenever any slot changes.
  Shows the result item icon, name, and output count.
- If all 6 slots are already filled and you click another item, the
  slots shift left (slot 1 is dropped, 2-6 move down, new item fills
  slot 6) so you can keep exploring combinations.

## Installation
Create a mods folder within lucid blocks directory and place Recipe_Browser_v0.1.pck inside.
