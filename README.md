# dolphin-no-drown

A Minecraft datapack that makes dolphins not drown.<br>
Works by resetting the `Moistness` and `Air` NBT tags of all dolphins to `2400` and `4800` respectively, every second.

## Installation:
[![GitHub release](https://img.shields.io/github/release/vkritya/dolphin-no-drown?include_prereleases=&sort=semver)](https://github.com/vkritya/dolphin-no-drown/releases/)<br>
 1. Download the latest dolphin-no-drown.zip file from [releases](https://github.com/vkritya/dolphin-no-drown/releases/)
 2. Follow the [Wiki Tutorial](https://minecraft.fandom.com/wiki/Tutorials/Installing_a_data_pack#In_an_existing_world)

## Warning:
As of 1.17.1, dolphins spawned using `/summon` have their `Moistness` tag default to `0`, meaning they will take damage immediately if spawned on land.<br>
Because the datapack runs every second instead of every tick, the new dolphin might take a bit of damage, you can:
 - Specify the `Moistness` tag during summoning (`/summon minecraft:dolphin ~ ~ ~ {Moistness:2400}`)
 - Heal the dolphin with a potion after summoning
 - Use a spawn egg instead
