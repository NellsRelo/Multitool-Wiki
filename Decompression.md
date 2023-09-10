# File Decompression

<img alt="Screenshot of the Application Dialog for Decompressing Files" src="https://i.imgur.com/J7Zjy42.png" align="right">

When the Multitool has finished Unpacking the game files, there are still files that can't be worked with directly, with extensions like `.lsf`, `.lsb`, or `.loca`. Fortunately, the Multitool can decompress these files into editable `.lsx` and `.xml` files. To do this, press the button labelled `Decompress Files` on the main Multitool window. You'll see this dialog prompt open. Hit `Yes`, and wait for it to finish processing the unpacked files for decompression.

Once it's complete, every decompressed file will be editable, and have a filename that looks like `Filename.lsf.lsx`, `Filename.loca.xml`, or similar. The text after the first `.` indicates the original extension, while the text after the second `.` indicates the new decompressed extension. This filename structure is especially important, as when you go to package a mod, any files with this filename structure will be converted to their original extension.

---

[<img src="https://img.shields.io/badge/Back_To-General_Usage-orange?style=for-the-badge">](https://github.com/ShinyHobo/BG3-Modders-Multitool/wiki/General-Usage)