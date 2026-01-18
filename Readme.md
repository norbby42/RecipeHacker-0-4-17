## RecipeHacker-0-4-17

Adds ways to get to recipes in Obenseuer that are currently unobtainable due to a bug in the way magazines and random recipe spawns work.
Put 2 of the magazine that grants the recipe into the Drawing Board and you can turn them into that specific recipe.
For Handwheel and 50L can, you need 1 Puuhari and 1 IC instead.

# Requirements

Requires Lavender 6.0.1 (see https://github.com/leonarudo/Lavender)

# Installation

1. Extract the .zip to Obenseuer/BepInEx/plugins
2. Start game

# Alternate No-Mod installation

Not recommended if the terms "JavaScript", "JSON", or "steamapps" frighten you

1. Extract the .zip to a location of your choosing
2. Open items.json and copy everything *EXCEPT* the outmost wrapping `[` and `]`
3. Open Obenseuer/Obenseuer_Data/StreamingAssets/Items.json
4. Paste the items at the bottom.  Make sure to move the wrapping `]` down to after the newest item, and ensure there's a `,` added after the last vanilla item.
5. Repeat for recipes.json in both places
6. Start game
