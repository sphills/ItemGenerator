# ItemGenerator

Download the project files here: https://www.dropbox.com/sh/bypoqwovxiq0jjx/AAAC6iUS6JUigsSDIcXPkecpa?dl=0

This is an ongoing, non-commercial, self-taught project built from scratch by using the Blueprints Visual Scripting solution available in Unreal Engine 4.18. Please download and extract the "ItemGenerator.zip" file to your local machine and make sure that all of the components ("Engine", "QNR_0", "QNR-0.exe", and "Manifest...") are located in one folder together.

This project incorporates weighted random number generation, object casting, extension of classes to incorporate new behaviors, saving/loading data from multiple objects to an in-game file, enums, C++ structs, and arrays of structs. The main objects are the <a href="https://github.com/sphills/ItemGenerator/wiki/MyPlayerController-Blueprint" target=_blank>MyPlayerController</a>, <a href="https://github.com/sphills/ItemGenerator/wiki/ThirdPersonCharacter-Blueprint" target=_blank>ThirdPersonCharacter</a>, <a href="https://github.com/sphills/ItemGenerator/wiki/WeaponComponentBP-Blueprint" target=_blank>WeaponComponentBP</a>, and <a href="https://github.com/sphills/ItemGenerator/wiki/MasterWeaponDataTable" target=_blank>MasterWeaponDataTable</a>. Please contact me if you would like a more detailed breakdown of the functions within each object.

To move the character, use W/S for forward/backward, A/D for left/right, and move the mouse to maneuver the camera.

Press TAB to open the current character's inventory. Click on the inventory subdivision you'd like to browse through, then click on the item to drop it (if it's a weapon) or equip it (if it's a piece of armor).

The rarity and prefix of a piece of loot is determined dynamically upon being spawned by a weighted random number generator. This consists of a .csv file I create in Google Sheets that correlates the pseudo-randomly generated number to an index in the .csv to select the rarity/prefix. It's also used to determine the balance/frequency of dropping weapon (Assault Rifles, Light Machine Guns, Marksman Rifles, etc.) or gear (Mask, Chest, Backpack, etc.) items, though those are built to drop evenly by default.

The characters don't have a limit for how many items they can hold, so be wary of how many you spawn and loot!

The character model, its textures, and the textures of the floor were pre-existing assets produced by the team at Epic Games.

The inventory and weapon class objects were created by me in-engine. All Blueprint scripting written by me.
