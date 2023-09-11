# Mod Workspace Structure

<img alt="Image depicts the structure of the Mod Workspace for CommunityLibrary, showing a Localization, Mods, and Public main folder, and their contents." src="https://i.imgur.com/3s7gkR2.png" align="right">

The Multitool can package mods, but to do so effectively, you'll need to ensure you mod has a valid structure. At it's core, you'll want something like this:

```
ModFolder
   | -> Localization
      | -> LanguageName
   | -> Mods
      | -> ModName
         | -> meta.lsx
   | -> Public
      | -> ModName
         | -> Folder1
            | -> File.lsx
         | -> Folder2
            | -> File.lsf
```

Of course, seeing it in action may be easier to understand, so on the right, we've supplied an image of what this looks like.

### Custom Subfolder Support
It's useful to note here, that while the game will not typically read files in custom subfolders, the Multitool will automatically merge files in subfolders within `Public/ModName/Stats/Generated/Data` into root-level files with the name of their Subfolder. In the example to the right, you can see that there's a subfolder, `CL_Util`, containing the files `CL_IndestructibleSummon_AI_Ignore.txt` and `CL_RacialProficiency.txt`. When the mod is packaged, these will be merged into `Public/ModName/Stats/Generated/Data/__MM_CL_Util_Timestamp_.txt`, becoming readable by the game.

Using a structure like this is recommended for improved code organization while making mods.