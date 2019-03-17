# Enemy Territory Unity Version

uTerritory is a complete remake of the classic game Enemy Territory using the Unity game engine.

![Original game screenshot](https://ue3s31vhmez1o77f81aycos1-wpengine.netdna-ssl.com/wp-content/uploads/2018/07/Screen-Wolf-ET-002.jpg)

## License

This software is free software and licensed under the [MIT License](https://github.com/bsimser/uterritory/blob/master/LICENSE). 

## History and Description

Wolfenstein: Enemy Territory is a free and open-source multiplayer first-person shooter video game set during World War II. It was originally planned to be released as a commercial expansion pack to Return to Castle Wolfenstein and later as a standalone game. However, due to problems with the single-player aspect, the multiplayer portion was released on 29 May 2003 as a freeware standalone game. In January 2004, the source code for the game logic (not the game engine) was released to the benefit of its modding community.

The game uses a modified Return to Castle Wolfenstein engine, itself being a heavily modified id Tech 3 engine, which has been open source since 2005. As of the first day of the August 2010 QuakeCon, the entire source code was released under the GNU General Public License v3.

## Gameplay

Wolfenstein: Enemy Territory is an online multiplayer game, wherein the players interact with each other over a network, in two teams (Allies and Axis) to defend or destroy mission objectives. The game is playable over the Internet or a Local Area Network. In public games, PunkBuster used to protect the game, however its developer, EvenBalance, discontinued support for the game in October 2011.

There are six officially released maps that are partially based on real locations or events (North African Campaign: Gold Rush, Siwa Oasis, and Atlantic Seawall Battery; Europe Campaign: Rail Gun, Würzburg Radar, and Fuel Dump), as well as hundreds of custom maps made by the gaming community. On most maps, the offense needs to complete a certain set of objectives within a limited amount of time. The defense needs to keep the offense from completing objectives until time runs out. Some objectives may be optional, and some objectives can be carried out by either team. These minor objectives assist the team completing them. Depending on game mode the action will continue on another map (Campaign Mode) or the same map (Objective Mode, Stopwatch Mode, Last Man Standing).

In all but the Last Man Standing Mode, dead players respawn all at the same time, every X seconds. In the default maps—assuming that the server settings are not changing it—Allies spawn every 20 seconds and the Axis every 30 seconds, the only exception being Rail Gun where both have a 20-second spawn. With default settings, one can see the spawn timer in the right side of the screen. Experienced players should watch the timer all the time—dying to a 1-second spawn practically means losing your position (and a life, if the server has the rarely used Limited Lives feature enabled) and resetting your health and ammo, while a 30-second spawn can be deadly if there are only a few players. A good tactic is to find out the spawn time of your enemy, for example looking at the mission timer, and time your attacks so that every dead opponent will have to wait a full-time spawn.

In the official six map campaign (most common on public servers), Allies are offense for all but one map, Railgun. In Stopwatch Mode (most common for locked or LAN servers) two teams—most common setups: 6vs6 or 3vs3—will play the same map twice, once on each side and the winner is the team with the fastest offense (it can be a tie when both teams defense manage to keep the offense from completing the objectives until time runs out (commonly known as a "full hold")).

Players may earn experience points in several skill categories. All character classes may earn points in Battle Sense and Light Weapons. Class skills are generally restricted to the current class, the exception being Heavy Weapons (the Soldier class skill).

Players have certain abilities based on their character class. The player has a Power Bar that provides "power" for their special abilities. The power bar regenerates slowly. Constructing the Command post speeds up the recharge rate though. Players have up to eight weapon slots, depending on character class. The classes that are available are engineer, soldier, field ops, medic, and covert ops.

## Game Data

Wolfenstein: Enemy Territory is a free release, and can be downloaded from [Splash Damage](https://www.splashdamage.com/games/wolfenstein-enemy-territory/).

This source release contains only the engine but not any game data, which is still covered by the original EULA and must be obeyed as usual.

In order to run uTerritory you will need to copy the orginal asset files (*pak0.pk3*, *pak1.pk3* and *pak2.pk3*) to the *Assets/etmain* folder.

## Bug Reports

Please feel free to submit bug reports on the [GitHub issue tracker](https://github.com/bsimser/uTerritory/issues) for this project.

## Prerequisites

* Unity 2018.3.8f1 (or newer)
* Visual Studio

## Git Branches

* `master` branch is the production branch of the latest release
* `develop` branch is for development and new features; it may be out of date compared to master.
* `gh-pages` branch is for the website

## Downloading

To get the latest source code install [git](http://git-scm.com/) and clone our repository hosted at [Github.com](https://github.com/bsimser/uTerritory):

    $ git clone https://github.com/bsimser/uTerritory.git
    
## Quick Start

1. Ensure you've prepared the prerequisites above
2. Clone this repo
3. Open the folder in Unity
4. Copy the orginal asset files (*pak0.pk3*, *pak1.pk3* and *pak2.pk3*) to the *Assets/etmain* folder
5. Build and run
6. All done!

## Credits

* [Will Fowler](https://github.com/wfowler1) ([LibBSP](https://github.com/wfowler1/LibBSP))
* Wolfenstein: Enemy Territory (Copyright (C) 1999-2010 id Software LLC, a ZeniMax Media company)

## Contributing

Please submit all patches as a GitHub pull request.
