#  GameObject Explorer
The GameObject Explorer, or GOE for short, is a useful tool that allows for quickly searching through Game Objects and their properties, as well as viewing thier models. GameObjects include Characters, Items, and more. It serves a different purpose than the index search, and both are valuable tools for any modder. To access the GameObject Explorer, in the Menubar, go to `Utilities -> GameObject Explorer -> Open`. This will open a new window:

<p align="center">
<img alt="Screenshot of the Multitool's GameObject Explorer UI." src="https://i.imgur.com/fuJRIyQ.png">
</p>

As you can see, there's a lot of ground to cover. On the left, we have a GameObject Type Selector, a Searchbase and Results tree, as well as an info-section on some properties of the file - Where the Pak is located, what it's name is, its Identifier (MapKey), etc. On the right, we have more info: Stats, Attributes, Icon, 3D Model, and any Model Files associated with it.

If you click on the dropdown and select a GameObject type, the Results tree on the left will fill up with unpacked objects of that type. As you navigate through these sections, clicking on the `(+)` next to an entry will open it up in the Right pane. You can filter your results with the Search bar, and easily see everything to do with the selected object.

### Effective Use of the Game Object Explorer
As long as you have the necessary game .paks unpacked, the GOE will automatically generate connections between things such as stats, icons, and translations in a hierarchal format. It is possible to search for GameObjects on multiple fields as well as within individual objects through the Stats tab property grid.

In order to use this feature, ensure that you have followed the following steps:

1. Unpack at least the English, Gustav, Icons, Models, Shared, and Textures paks (wait for all console windows to close and completion message to show before continuing)
2. Decompress (DO NOT DELETE .lsf FILES)
3. Index
4. Open the GameObject Explorer (will take 20+ minutes to organize gameobjects and build a cache)

If you don't follow the above steps exactly, it will generate an empty cache and display nothing. To troubleshoot, deleting the cache and reindexing will fix most issues.

### Using the Model Viewer
The model viewer tab allows you to view the model associated with a given object (characters, items, scenery, and TileConstructions). This process automatically converts the .GR2 file to a `.dae` collada file in the same directory. The Model Files tab will list the files used to generate the model; hovering over the name of a model will provide you with the full pak file path and clicking it will open both the containing folder to the file as well as the default program associated `.dae` files on your system ie. Notepad++.


<p align="center">
  <img src="https://camo.githubusercontent.com/d774c1ceebca3479a63fc60feaf7df9b833d387da887f14b3e03220f20690d12/68747470733a2f2f692e696d6775722e636f6d2f664a4f484256452e706e67" alt="Screenshot of the GameObject Explorer, showing the 3D Model tab in the Info pane for a Red Dragon">
</p>

---

[<img src="https://img.shields.io/badge/Back_To-General_Usage-orange?style=for-the-badge">](https://github.com/ShinyHobo/BG3-Modders-Multitool/wiki/General-Usage)