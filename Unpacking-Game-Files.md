## Unpacking the Game Files

<img alt="Screenshot of the .pak Selection window" src="https://i.imgur.com/zXBWhdK.png" align="right">

When you click on the `Unpacking .pak files` button, a window like the one on the right will open up. This is a list of most of the game files - all the most commonly needed ones, at least. Each of these `.pak` files correspond to either a featureset of the game, or a patch. But which ones matter to us?

### Materials
The following files contain visual assets that are useful if that's what you intend on working with: `Assets.pak`, `Effects.pak`, `Icons.pak`, `Materials.pak`, `Models.pak`, `Textures.pak`

### Game Definitions
***Game:*** Contains UI-related files, Scripts, and more. Very much worth unpacking.

***Gustav:*** Contains files with the Larian-specific Definitions for the game. This is a must to unpack.

***Shared:*** Contains files with the 5e-specific Definitions for the game. Almost all our spells, races, classes, items, and more are stored here. This is a must to unpack.

### Localization
***English:*** Contains the English Localizations files. Extremely useful for manual searching of the game files when the Index Search doesn't fit the bill.

### Patch Data
`day0`, `Patch0_Hotfix1`, `Patch0_Hotfix2`, `Patch0_Hotfix3`, `Patch0_Hotfix4`, `Patch1`, `Patch2`, `Patch2_Hotfix1`, `Patch2_Hotfix2`, and on and on. These, of course, override anything in the other `.pak` files.

If you have the space, it's recommended to hit the `Select All` button, but if not, You'll want to tick some of the above mentioned files. When you've made your selection, hit `Confirm`, and buckle in for a wait, as the Multitool will now start unpacking the files into a Folder next to it: `\UnpackedData`. 

![Screenshot of the Pak Unpacking Progress window in Multitool](https://i.imgur.com/6UMTR01.png)

Once the process is complete, you'll see the following folder: 

<img alt="Screenshot of the Multitool installation folder with an 'UnpackedData' folder" src="https://i.imgur.com/0bI8v4l.png">

When you click into it, it will look like this:

<img alt="Screenshot of the Multitool installation folder with an 'UnpackedData' folder" src="https://i.imgur.com/LmEd15P.png">

---

[<img src="https://img.shields.io/badge/Back_To-General_Usage-orange?style=for-the-badge">](https://github.com/ShinyHobo/BG3-Modders-Multitool/wiki/General-Usage)
