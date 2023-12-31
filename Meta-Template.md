# Meta Template
While the Multitool can generate a `meta.lsx` file, you may like to have a template for the file, for easy copy/pasting into your own projects.

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!-- 
  You'll want to change the following fields:
    - Author - Your Preferred Author Name
    - Description - A Description of your Mod
    - Folder - The Primary Folder used in your Mod - in this case, TemplateMod
    - Name - What to display in the Mod Manager
    - Tags - A semi-colon separated list of keywords for your mod
    - UUID - Generate this with the Modder's Multitool, any extension for your IDE, or at https://www.uuidgenerator.net/version4
    - Version64 - Both of them. BG3MM has a Version String Generator tool, under Tools -> Toggle Version Generator Window
-->

<save>
  <version major="4" minor="0" revision="0" build="49"/>
  <region id="Config">
    <node id="root">
      <children>
        <node id="Dependencies"/>
        <node id="ModuleInfo">
          <attribute id="Author" type="LSWString" value="Author Name"/>
          <attribute id="CharacterCreationLevelName" type="FixedString" value=""/>
          <attribute id="Description" type="LSWString" value="Mod Description Goes Here"/>
          <attribute id="Folder" type="LSWString" value="ModFolderName"/>
          <attribute id="GMTemplate" type="FixedString" value=""/>
          <attribute id="LobbyLevelName" type="FixedString" value=""/>
          <attribute id="MD5" type="LSString" value=""/>
          <attribute id="MainMenuBackgroundVideo" type="FixedString" value=""/>
          <attribute id="MenuLevelName" type="FixedString" value=""/>
          <attribute id="Name" type="FixedString" value="ModName"/>
          <attribute id="NumPlayers" type="uint8" value="4"/>
          <attribute id="PhotoBooth" type="FixedString" value=""/>
          <attribute id="StartupLevelName" type="FixedString" value=""/>
          <attribute id="Tags" type="LSWString" value="Template"/>
          <attribute id="Type" type="FixedString" value="Add-on"/>
          <attribute id="UUID" type="FixedString" value="faef6819-403e-460d-83f4-c8788a854773"/>
          <attribute id="Version64" type="int64" value="36028797018963968"/>
          <children>
            <node id="PublishVersion">
                <attribute id="Version64" type="int64" value="36028797018963968"/>
            </node>
            <node id="Scripts" />
            <node id="TargetModes">
              <children>
                <node id="Target">
                  <attribute id="Object" type="FixedString" value="Story"/>
                </node>
              </children>
            </node>
          </children>
        </node>
      </children>
    </node>
  </region>
</save>
```