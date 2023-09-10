# Indexing and Searching Files
The Multitool provides a handy file search function for its unpacked files, which requires indexing the Unpacked Files to be effective. In this section, we'll learn how to index files, and how to use the Index Search.

<img alt="Screenshot of the Multitool UI's File Indexing section when active." src="https://i.imgur.com/y1jyfIQ.png" align="right">

### Indexing Files

Indexing files is a simple task, so let's take a look at what you need to do:

1. In Multitool's Menubar, select `Utilities -> Index -> Index Files`

You'll see a progress bar appear, simliar to the image on the right, pointing to the amount of files being processed, along with an estimate of how long is left before the Indexing process is completed. Once it's done, the progress bar and time estimate will disappear. You'll want to update this each time you unpack the game files, which is why it's recommended to unpack all the game files at once is space allows, rather than doing it piecemeal.

### Index Search
The Index Search is a powerful tool, making use of the Index you've created. It has several filtering options, the ability to quickly open files, and  fast search mode. After taking a look at the image below, we'll take a look at each of these features:

<p align="center">
  <img alt="Screenshot of the Multitool's Index Search Feature" src="https://i.imgur.com/PhaSeTN.png">
</P>

#### Searching the Index
To Search your Index, type in something you want to find in the game files in the the Search Bar. In the example above, I've input `PACT_BLADE`. The section below the search bar will show a clickable list of each file found that contains the keyword we've searched for. When you hover over or click on one of the files, a preview of each time the string has been found in that file will display on the right. You can press the `Open` button above it to quickly open the file in a Text Editor or IDE.

Note that this keyword can be anything - an ID, a function name, even a random string.
#### Filtering
In the dropdown next to the `Search Files` button, you'll find a wide array of filetypes you can filter your search by. By default, it will show results from all file types, but if you know what specific filetypes you're looking for (for example - you want to know every use of the `PACT_BLADE` status within the `.khn` files), you can untick the options in the dropdown.

An easy way to deselect every filetype, if you want to narrow your filtering down quickly, is to tick and untick the `Select All` option, which will then untick every option in the dropdown.
#### Quick Search Mode
Next to the Filtering Dropdown, there's a Checkbox with an Up arrow icon next to it. This Checkbox controls the speed and accuracy of your search. If you want to get results faster, tick the box. In doing so, you won't always get every result you would have without the feature, but the search will go much more quickly.

---

[<img src="https://img.shields.io/badge/Back_To-General_Usage-orange?style=for-the-badge">](https://github.com/ShinyHobo/BG3-Modders-Multitool/wiki/General-Usage)