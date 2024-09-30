**First off, a huge shoutout to the following national treasures!**

* **Engezerstorung ([https://github.com/dear-github/dear-github/issues/150](https://github.com/dear-github/dear-github/issues/150))** - He allowed me to use his Pokémon ROM hack as a base for my own!
* **FroggestSpirit, Drenn, and dannye** for their full-colored Pokémon Red patch (see [https://github.com/dannye/pokered-gbc](https://github.com/dannye/pokered-gbc))
* **Everyone who has contributed to the pret disassembly and the tutorials in its wiki** (see [https://github.com/pret/pokered/](https://github.com/pret/pokered/))
* **Makers of the Shockwave Crystal Clear Sprites**

**The base Pokémon ROM hack by Engezerstorung includes several changes, such as:**

* Tweaked color palettes for improved visuals.
* Enhanced tilesets for more color usage and visual improvements while maintaining the vanilla design.
* Adjusted maps and blocksets for better visuals.
* Added unique party Pokémon icons following the tutorial on pret/pokered/wiki.
* Introduced new sprites and palettes for Gym Leaders.
* Replaced generic Pokémon sprites on maps with unique ones from Crystal Clear.
* Transformed the PokéCenter Bench Guy into a real little boy (requires an overhaul to the sprite_OAM engine).

**The sprite_OAM engine overhaul offers these features:**

* Creation of dedicated animation tables for specific sprites.
* Definition of per-sprite XY pixel offsets.
* Easy implementation of both features through a list at the bottom of data/sprites/facings.asm.

**Quality of Life (QoL) Updates:**

* Running shoes are now available.

**# IMPORTANT: Importing Saves Across Versions**

To import saves between patched and unpatched versions:

1. Save at the entrance of an interior location (e.g., PokéCenter) to avoid needing to move a block to exit.
2. Import the save into the new version.
3. Load the save and press a direction to exit the building.
4. Enjoy!
