# 3rd Life Add-on
See more information about the 3rd Life Add-on [here](https://cda94581.github.io/downloads/bps.html#_2021-06-10)

Download the Add-on [here](https://github.com/cda94581/3rd-life-add-on/releases)

# ARCHIVED
Two years ago, this was a fun project. Since then, a lot has happened and I have decided maintaining and updating this pack through the different Life Series seasons wasn't where my interests lied in. Those who still enjoy the series may be interested in other projects such as [this one](https://mcpedl.com/last-life/), although their status is completely up to the creators of each pack.

## About
This add-on was a requested fan-based creation when the first installment of the 3rd Life series was launched. The premise is simple: You get 3 lives. If you lose them all, you are sent to a "spectator" mode. Recreations of Last Life and Double Life have been considered, however no formal plans have been made.

This add-on has not been updated in a while, but is still available. Use at your own risk.

[Showcase Video](https://youtu.be/GYFw8RbT58E)

[View on MCPEDL](https://mcpedl.com/3rd-life-add-on/)

## Introduction
3 lives, if you die you're sent to a custom spectator mode. There's a customizable world border in place. This is not a perfect recreation of the Java SMP, colored names are either too hard or not possible in Bedrock Edition at the current moment in time. Enjoy! This pack does not require prior setup, by applying the pack, you're good to go!

## Documentation
This add-on comes with 2 packs, a behavior pack, and an optional resource pack. The resource pack is just for aesthetic purposes, giving you a spectator head texture. Unfortunately with the current add-on functionality, this cannot change depending on the skin:
![Lack of Custom Skin](https://api.mcpedl.com/storage/submissions/107175/images/3rd-life-addon_2.png)

If you are in multiplayer, then your lives remaining will display below your name. After you die 3 times, you are sent into spectator mode. In your hotbar, you will have 5 items:
- **Milk** clears all effects you have
- **Feather** gives you levitation for 30 seconds
- **Book** explains what I'm explaining right now
- **Leather** Boots gives you Speed 3 for 30 seconds
- **Water Bottle**, when used, teleports you to the nearest player. This only works in multiplayer.

You will be unable to modify the world in any way, shape, or form, while in spectator.

If you have used up all your lives and really want to leave spectator, make sure Cheats are enabled and you have Operator permissions, and then input **/function cda003/reset**. Conversely, if you want to enter spectator, again, make sure Cheats are enabled and you have Operator permissions, then input **/function cda003/spectator**.

There is a world border in place. By default, it is set to 350 blocks away from 0,0, and will warn you with blindness when you're within 20 blocks of that. Changing this is fairly simple and straightforward:

If you have a world already created with the pack
1. Navigate to your **com.mojang** folder. If you are unsure on how to do that on your device, use this link for information.
2. Navigate to the **minecraftWorlds** folder.
3. Navigate to your specific world folder. To know if it is in fact the right one, open up the **levelname.txt** file inside and see if it matches your world name. Just make sure you name your worlds ;)
4. In your world folder, navigate to **behavior\_packs/3rdLifeAdd/animation\_controllers/**. Open the **cda003.json** file inside.
	- If you are unable to open the file, rename it to a **.txt** file extension while editing, and rename it back to a **.json** file extension afterwards
5. Find the line that says: **"transitions": [{ "variables": "v.border\_radius = 350; v.warning\_distance = 20; return 1.0;" }]**. You can modify the **v.border\_radius = 350;** to something else like **v.border\_radius = 500;**. You can do the same with **v.warning\_distance = 20;**. **Do NOT remove the semicolon!**
6. There you go!

If you are creating a new world, create the world first & and apply the pack, then logout and do the steps mentioned above!
Alternatively, you can modify the default border when on world creation, by skipping step 2 & 3. There's a **behavior\_packs** folder in the **com.mojang** folder as well so step 4 is do-able!

## Installation
1. Download the pack at the given link
2. Import it
	- If you are unable to import it with a tap/double click, rename the file from a **.mcaddon** file extension to a **.zip** file extension. Afterwards, **unzip** the folder and move the **behavior pack** to the **behavior\_packs** folder and the **resource pack** to the **resource\_packs** folder of the **com.mojang** folder
3. Apply it to your worlds
4. Enjoy!

## Contributing
This section is a work in progress, however you're free to contribute however you'd like! Please be aware that this project is licensed under the [MIT License](./LICENSE), which is a simple and permissive license that allows anyone to do anything with it, and any contributions should reflect this understanding. These are a few options on what can be contributed:
- Language Translations
- Changes to the Base Source Code
- [Open Bug Reports](https://github.com/cda94581/3rd-life-add-on/issues)
- Create and Maintain Documentation