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