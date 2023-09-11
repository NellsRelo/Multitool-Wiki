# Packaging and Unpacking Mod Workspaces
The Multitool is not limited to unpacking the game files. While it's commonly used for Packaging mods, the Multitool can also unpack existing mod `.pak` files. What's more, both packaging a mod and unpacking a mod use the same general workflow. You'll notice the big blue section in the Multitool's UI:

<img alt="Screenshot of the 'Drop mod workspace folder or a mod .pak here' section of Multitool." src="https://i.imgur.com/C9bKPeI.png">

This is fairly self-explanatory, but let's break down what to do for the two use cases of this feature.

## Packaging Mod Files
So, you've built your mod, and you're ready to start testing it, or maybe you're sure it will work and you want to release it right away. The Modder's Multitool's here to help. You can easily package your mod in a few easy steps:

1. Find your Mod's Workspace Folder - the folder that contains the Localization, Mods, and Public folders - in your file manager.
2. Drag the Folder over the `Drop mod workspace folder or a mod .pak here` section of the Multitool.
3. Wait for it to finish packaging your mod.

You'll have a freshly-created "ModName.zip" file in the same directory as your folder. This is your mod, now playable and release-ready (as long at the mod is set up correctly, at least).


<img alt="screenshot of the 'Add Meta File' UI, presenting an Author and Description text field." src="https://i.imgur.com/itoSbX9.png" align="left">

### Auto-Generating Meta.lsx


If your Mod's Workspace folder doesn't contain a `meta.lsx` file under `Mods/ModName/`, don't worry! You won't have to create this from scratch, as the above process will prompt you to fill out your Author Name and a description of the mod, while the Multitool does the rest of the work.

After filling out those fields and hitting `Confirm`, a new `meta.lsx` file will be generated in the mod Workspace folder you provided to the Multitool, and will also be packaged into your mod.

## Unpacking Mods
Not quite finished with your mod, and want to look at existing mods for examples on how to handle certain situations? Or maybe you need to unpack a previous version of your mod to root out the cause of a bug, or you're just curious. Whatever your reasons, the Multitool allows you unpack the files held in a mod's `.pak` file. Just like with Packaging, this only takes a few simple steps:

<img src="https://i.imgur.com/zKLWubD.png" alt="A Screenshot of the Multitool Directory showing an 'UnpackedMods' folder." align="right">

1. Find the `.pak` file you want to unpack.
2. Drag it onto the  `Drop mod workspace folder or a mod .pak here` section of the Multitool.
3. Wait for the mod to Unpack.

You'll notice a new folder created in your Multitool folder: `UnpackedMods`. If you enter this folder, you'll see a Workspace folder of the unpacked mod, which you can enter into and look through.

---

[<img src="https://img.shields.io/badge/Back_To-General_Usage-orange?style=for-the-badge">](https://github.com/ShinyHobo/BG3-Modders-Multitool/wiki/General-Usage)