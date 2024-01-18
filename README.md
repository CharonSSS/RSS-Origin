# (WIP) _RSS-Origin - Exclusive add-ons with hundreds of asteroids, comets, moons and overhauls RSS_

![A](https://github.com/CharonSSS/RSS-Origin/blob/main/assets/insignia%20by%20Alice%20Christina.jpg)
***
# Note
This mod is still **work-in-progress**. The Github page is still **under construction**.

Currently the mod is in **closed-beta**, many features are **unfinished**.

**If you want to play it right now, just clone and download ZIP. But remember, this is still unfinished right now, me and my team are devoting every effort to improve it.**

**If you want to play and test it, or report bugs of it, or you have some ideas about my mod, I'm applying for a discord channel in Kopernicus server, once I've got a channel you can join the discussion.**

***
# !!!Please be sure to read "[Installation Guide](README.md#installation-guide)" before installation!!!
***

# About the mod

Like the title, **this mod is basically a DLC for "[Real Solar System](https://forum.kerbalspaceprogram.com/topic/177216-*)"**, and currently it includes the following parts:

- **_RSS-Origin CelestialsPack_**, the major part of this mod, which adds plenty of asteroids, asteroid moons, comets, moons of gas/ice giants, dwarf planets, dwarf planet moons, and interstellar objects into the solar system, currently 141 in total. (dozens more in the future)

- **_RSS-Origin RSSTexture&TopoRevamp_** (textures awaiting for upload), which overhauls some of the RSS celestials with more accurate, more realistic and higher res textures and topography, since some of the RSS textures are unrealistic in color and topo and other stuff.

- **_RSS-Origin JSUNrings_**, which adds accurate and realistic rings to the 4 gas giants in our solar system.

- **_RSS-Origin GalaxyTex_** (textures awaiting for upload), which replaces your skybox with a high-quality Milky Way background.

# More details about the mod (points for attention, to-dos, plans, screenshots)

- ### _RSS-Origin CelestialsPack_

**_RSS-Origin CelestialsPack_** is originally made for playing in Principia, now too. Many of its unique features can only be displayed in Principia, like irregular gravitational field of potatos, binary/trinary systems, orbital mechanics of trojans and co-orbitals, etc. **So it is highly recommended to play the mod in Principia.** You can play without Principia though, but I bet you won't get a good experience, especially conducting interplanetary missions.

Me and my team are doing our best to ensure that every celestial body visited by spacecraft uses models and textures that are as close to reality as possible in the game, celestial bodies that have not been visited by spacecraft use their models and spectra based on ground observations as much as possible. The physical characteristics of those completely unknown objects are reasonable artistic creations based solely on existing data.

### --- Again, [Principia](https://forum.kerbalspaceprogram.com/topic/162200-*) is highly recommended to play with ---

### And please be sure to read "[Installation Guide](README.md#installation-guide)" before installation!

And here is a list about all the celestials added and planning to add soon.

![A](https://github.com/CharonSSS/RSS-Origin/blob/main/assets/Celestial%20bodies%20added%20in%20RSS-Origin%20up-coming%20initial%20release.png)

- ### _RSS-Origin RSSTexture&TopoRevamp_

**_RSS-Origin RSSTexture&TopoRevamp_** is an overhaul to some of the RSS celestials. I've done a widely search for information and figure out some of the RSS celestials are using wrong surface textures and topograhy maps, so this mod's purpose is to fix those issues. Different texture resolutions are provided, 4k, 8k and 16k as of now. And here is a list for all the objects been revamped. (only maximum resolution listed)

### Don't forget to read "[Installation Guide](README.md#installation-guide)" before installation!

![A](https://github.com/CharonSSS/RSS-Origin/blob/main/assets/list%20of%20revamped%20objects%2016k.png)

- ### _RSS-Origin JSUNrings_

**_RSS-Origin JSUNrings_** adds realistic rings to Jupiter, Saturn, Uranus and Neptune:
- Jupiter: Halo ring, Main ring, Amalthea gossamer ring, Thebe gossamer ring.
- Saturn: Main rings (A,B,C,D,F), G ring, E ring.
- Uranus: Narrow main rings (6, 5, 4, α, β, η, γ, δ, ε), Dusty rings (1986U2R/ζ, λ), Outer rings (ν, μ).
- Neptune: Galle ring, Le Verrier ring, Lassell ring, Adams ring.

It should be incompatible with other ring mods or visual mods that add rings.

### Once again, don't forget to read "[Installation Guide](README.md#installation-guide)" before installation!

- ### _RSS-Origin GalaxyTex_

**_RSS-Origin GalaxyTex_** replaces your skybox with a fairly good Milky Way background in correct orientation. 4 resolutions are provided (8k, 16k, 32k, 64k). Source [https://svs.gsfc.nasa.gov/4851](https://svs.gsfc.nasa.gov/4851).

- ## Plans, to-dos:

- ## Screenshots:

where?

***

# Installation Guide

## For _RSS-Origin CelestialsPack_

**Since this is the major part of the mod, we will give you a detailed guide and note, and we hope that you can patiently read it through**

### Things you should know:

Since this mod adds 141 extra celestial bodies to your game by default, along with 33 celestial bodies from RSS, for a total of 174, **this will cause your game to lag during acceleration and slow scene switching**. Given this situation, the folder structure of this mod is: each celestial or celestial system is placed in a separate folder, and you can add or remove celestial folders according to your own needs to ensure the smoothness of your gameplay.

We strongly **do not recommend** installing all celestials at once. (except for viewing scenery or searching for your target(s))

It is highly recommended **not to** install all celestials while you are ready to conduct interplanetary missions! We suggest retaining only the celestial(s) required for the mission and removing the remainings.

**Specific operations for adding/removing celestial bodies:**
Go to RSSOrigin in gamedata, search for celestial folders you need or don't need.
Move the unwanted celestial folders out of GameData. (! Please remember the location of the celestial folder before moving it out! If you forget, you can go to check "[List of added celestials](https://github.com/CharonSSS/RSS-Origin/blob/main/assets/Celestial%20bodies%20added%20in%20RSS-Origin%20up-coming%20initial%20release.png)" for the location of the celestial folder)
If you need a certain celestial or celestial system, you can place it back in the corresponding position within GameData/RSSOrigin.

If you want to install small moons in the ring of gas/ice giants and also want to add rings to gas/ice giants, it is recommended to use "**_RSS-Origin JSUNrings_**". This ring pack is matched with RSS-Origin, and the positions of the small moons and rings are adjusted according to reality. If this ring pack is not used, the small moons may drift elsewhere, which is very unreasonable.

**Statement: The orbital data, physical data, appearance, etc. of celestial bodies are not guaranteed to be completely consistent with reality.**

**There're also 6 issues of this mod**
- 1. Objects with smaller radii (<400m) may have rendering bugs. When viewed from a distance, the overall display will be black. When approaching, the texture will flicker, but it does not affect landing. Once approached, it will return to normal.
- 2. Objects that are too small may not be visible (or appear black) on the tracking station and map view even if the camera is pulled closest, which is the scaling limitation of KSP.
- 3. After installing a large number of celestials with Principia, when the Plotting Frame Selection interface is fully expanded, the game will become extremely laggy. Reducing the number of expanded celestials or closing the interface can solve this problem.
- 4. After installing a large number of celestials without Principia, when you go to map view, the game will become laggy due to too much orbit lines rendered.
- 5. The limitation of Principia results in some moons that are tidally locked with planets being unable to effectively maintain tidal locking. After a period of timewarp, the moons will deviate from the correct orientation, which cannot be solved at present.
- 6. There may be some bugs for unknown reasons when attempting to transfer between some small asteroids and their moons (passing through SOI). Switching to the tracking station and then switch back to the vehicle can solve this problem.

### Dependencies and recommendations

[Real Solar System](https://forum.kerbalspaceprogram.com/topic/177216-*) and all dependencies of it (of course)

(In case you are new to KSP, dependencies of RSS are: [Module Manager](https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*), [Kopernicus](https://forum.kerbalspaceprogram.com/index.php?/topic/200143-*), [RSS-Textures](https://forum.kerbalspaceprogram.com/index.php?/topic/177216-*), [KSP Community Fixes](https://forum.kerbalspaceprogram.com/index.php?/topic/204002-*))

### !!! Important note：
#### - Check if you have "KSP Community Fixes" installed. If yes, turn the option "Maneuver Tool" off in your gameplay settings. If you don't follow this step, you "may" experience a extremely laggy gameplay once you are inflight.
#### - If you haven't install "KSP Community Fixes" yet, install it, and follow the step above. If "KSP Community Fixes" is not in your gamedata, you will be sure to experience the same issue.

Highly recommend: 
- [Principia](https://forum.kerbalspaceprogram.com/topic/162200-*)
- [Realism Overhaul](http://forum.kerbalspaceprogram.com/index.php?/topic/155700-122-realism-overhaul-v1150-05262017/)
- [Realistic Progression One (RP-1)](https://forum.kerbalspaceprogram.com/index.php?/topic/190040-*)
- [KSC Switcher](https://forum.kerbalspaceprogram.com/index.php?/topic/106206-*)
- [RSS DateTime Formatter](http://forum.kerbalspaceprogram.com/index.php?/topic/139335-*)

Recommend:
- [Environmental Visual Enhancements](https://forum.kerbalspaceprogram.com/index.php?/topic/196411-19-111x-eve-redux-performance-enhanced-eve-build-v11121-31012021/)
- [Scatterer](http://forum.kerbalspaceprogram.com/index.php?/topic/103963-wip-scatterer-atmospheric-scattering)
- [Parallax](https://forum.kerbalspaceprogram.com/index.php?/topic/197024-*)
- [TUFX](https://forum.kerbalspaceprogram.com/index.php?/topic/192212-*)

Incompatibles:
Seriously, I didn't expect anything incompatible. If there has to be an answer, it is other expansion pack for RSS are incompatible.

### Download & installation instruction

1. Go to the release page of this repository, download **"_RSS-Origin Core.zip_"**.
2. Unzip **"_RSS-Origin Core.zip_"**，put "RSSOrigin" into your Gamedata.
3. Go to the release page of this repository, download **"_RSS-Origin CelestialsPack Core.zip_"**.
4. Go to the release page of this repository, choose what celestial(s) you desired, download it.
5. Unzip **"_RSS-Origin CelestialsPack Core.zip_"**，you will find 2 folders, Principia and RSSOrigin. Put both of them into your Gamedata and overwrite the 2 cfgs of Principia. (if you are playing without Principia, just ignore the 2 cfgs)
6. Unzip the **_celestial pack(s).zip_**, and put all of them into your Gamedata.
7. Follow the [step in "Important note"](tree/main#-important-note) above.
8. If you are playing **without** Principia, just launch the game and continue your saves.
9. If you are playing **with** Principia, launch your game and create a new save to play. (Don't open your old saves, or your game will crash or your save will be broken!)

### Hardward requirements
If you can run RSS (or RSS+Principia) on your device, you can run this mod. But notice, more celestials added to your game means better device you should have.

## For _RSS-Origin RSSTexture&TopoRevamp_

**This mod only replaces textures and cfgs, so [Real Solar System](https://forum.kerbalspaceprogram.com/topic/177216-*) is the only dependency.**

Incompatibles:
This mod may be incompatible with RSS-Reborn. If you want to use my mod and you are using RSS-Reborn at the same time, please contact me or [@ballisticfox](https://github.com/ballisticfox) in discord first. If you have the ability to correctly merge and modify mods, you can go for it and do it yourself.

### Download & installation instruction

1. Go to the release page of this repository, download **"_RSS-Origin RSSTexture&TopoRevamp Configs.zip_"**.
2. Go to the release page of this repository, choose a resolution you desired, download it.
3. Unzip **"_RSS-Origin RSSTexture&TopoRevamp Configs.zip_"**，put all the files into your Gamedata and overwrite all.
4. Unzip **"_RSS-Origin RSSTexture&TopoRevamp Textures(xx)k.zip_"**，put all the files into your Gamedata and overwrite all.
5. Launch your game.

### Hardward requirements
It is the same as RSS Textures.

## For _RSS-Origin JSUNrings_

Dependency: [Real Solar System](https://forum.kerbalspaceprogram.com/topic/177216-*)

Recommend: If you want realistic ring shadow, [Scatterer](http://forum.kerbalspaceprogram.com/index.php?/topic/103963-wip-scatterer-atmospheric-scattering) is needed.

Incompatibles: All the other ring mods or visual packs that adds rings. Make sure there're no other rings and ring cfgs in your gamedata except for the RSS one of Saturn.

### Download & installation instruction

1. Go to the release page of this repository, download **"_RSS-Origin Core.zip_"**.
2. Unzip **"_RSS-Origin Core.zip_"**，put "RSSOrigin" into your Gamedata.
3. Go to the release page of this repository, download **"_RSS-Origin JSUNrings.zip_"**.
4. Unzip **"_RSS-Origin JSUNrings.zip_"**，put all the files into your Gamedata.
5. Launch your game.

## For _RSS-Origin GalaxyTex_

Dependency: Only [TextureReplacer](https://forum.kerbalspaceprogram.com/index.php?/topic/96851-x) is needed

Incompatibles: Other skybox packs or mods that adds custom skybox.

### Download & installation instruction

1. Go to the release page of this repository, download **"_RSS-Origin Core.zip_"**.
2. Unzip **"_RSS-Origin Core.zip_"**，put "RSSOrigin" into your Gamedata.
3. Go to the release page of this repository, choose a resolution you desired, download **"_RSS-Origin GalaxyTex(xx)k.zip_"**.
4. Unzip **"_RSS-Origin GalaxyTex(xx)k.zip_"**，put all the files into your Gamedata.
5. Launch your game.

***
# Credit

## Author: **Charon_S (me)**

### Main Contributors: (Ranked in alphabetical order without distinction of the extent of contribution)
	himīśā
	NewoEther
	Proxima-b

### Special Contributors: (Ranked in alphabetical order without distinction of the extent of contribution)
	Alice Christina
	ballisticfox
	caps lock
	Kerbinator Fras
	猫猫是我心头好
	R-T-B
	游荡云雀
	YWMKerman

### Acknowledgement：
	All members mentioned above
	All members of closed-beta team
	All members who have provided suggestions and comments on this mod

### Apologize to:
	All members who have made noteworthy contributions to this mod but are not listed above

For more information about credits, contributions and acknowledgements, see [CREDIT.md](https://github.com/CharonSSS/RSS-Origin/blob/main/CREDIT.md)
