# Manual_MK8D_RampantEpsilon

For use with Manual Archipelago Client Only. (https://discord.gg/T5bcsVHByx)

To Use:
- Download all files as a ZIP folder
- Rename the ZIP folder as a .apworld file
- Add to /lib/worlds/ folder for Manual AP
- Generate a YAML using the example below

```
Manual_MK8D_RampantEpsilon:
    progression_balancing: 50
    accessibility: items
    
    # Change if you don't want base tracks or DLC tracks #
    include_base_game: true
    include_DLC: true

    # Change if you want the game to be completable by other games #
    ## NOTE: Removing local_items could make your game beatable without ever playing it! ##
    local_items: Gold Trophy

game: Manual_MK8D_RampantEpsilon
name: Player
```

Generate & Enjoy
NOTE: It should be possible to generate seeds with just base game or just DLC by modifing the YAML with the excluded_locations and starting_items flags.

## Goal

Complete all four Rainbow Road tracks. (SNES, N64, 3DS, WiiU)

## Randomized

All Characters, Karts, Wheels, Gliders, and Cup Passes

## Checks

Each track has two checks (Original was one per track but it caused a lot of items to not be placed.)

## Starting Items

Starting Items: One Character/Kart/Wheel/Glider Combination and one cup.
