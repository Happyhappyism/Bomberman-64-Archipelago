# Bomberman 64 Archipelago

## Resources
[Poptracker Pack](https://github.com/RunInAWeek/Bomberman-64-AP-Tracker/releases) by [RunInAWeek](https://github.com/RunInAWeek)

# Setup Guide

## What you need
- Bizhawk https://tasvideos.org/BizHawk/ReleaseHistory#Bizhawk210
- The latest Bomberman 64 .apworld provided in the latest release post


## Installation
Same as every other unsupported N64 apworld, 
- simply move bomberman_64.apworld into the custom_worlds directory in your Archipelago install server
(default path: C:\ProgramData\Archipelago\custom_worlds)
- or simply double click the apworld and it should install itself (Archipelago version 0.5.0 and later)

## Running
1. In the Archipelago launcher push the 'Generate Template Options' button to generate a yaml for your options
2. Like every other apworld, fill out your yaml options and have the host generate the multiworld, the produced zip file should contain a .apbomb64 patch file. Receive this .apbomb64 patch from the multiworld host.
3. Push the 'Open Patch' button in the launcher and it should ask for a 'Bomberman 64 (US)' legal ROM dump (MD5 Hash: 093058ece14c8cc1a887b2087eb5cfe9), then select the generated  .apbomb64 patch file to produce a .z64 ROM which should auto launch in a bizhawk instance. You should be set otherwise from here just follow the same instructions as any other supported N64 apworld.

## Troubleshooting
- The windows 7 version of archipelago uses python 3.8 which will not work with this apworld.

# Features
- Normal and Hard modes included
- Playable up to Altair final battle
- Start with either first level or first three levels of each world
- Gold Cards obtained without completing stage
- Deathlink
- Random music!
- Randomized sound effects

## Locations
- Stage Clears
- Gold Cards
- Power Bomb Powerups
- Remote Bomb Powerups
- Custom Part Capsules

## Gameplay Notes
- Kicking Bombs and Power Glove are locked as checks at first.
- Remote Bombs and Power Bombs are checks within levels but are permanent when you receive them from your item pool.

Planned Features
Randomized enemies
Rainbow Castle to come ... at some point!
