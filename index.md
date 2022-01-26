# Victoria II Tools and Guides for Modding

## [Victoria 2 Modding Server for futher questions and help](https://discord.gg/M7fZVQcCvA)

## Table of Contents

   * [Modding Bible](#modders-bible-of-events-and-decisions)**<br>
   * [Guide](#guides)**<br>
   * [Programs](#tools-and-programs)**<br>
   * [Editing Programs](#editors)**<br>
   * [General Practices](#general-practices)**<br>
   

## Modder's Bible of Events and Decisions
### [Effects Wiki](https://vic2.paradoxwikis.com/List_of_effects)
### [Scopes Wiki](https://vic2.paradoxwikis.com/List_of_scopes)
### [Conditions Wiki](https://vic2.paradoxwikis.com/List_of_conditions)
### [Modifier Effects Wiki](https://vic2.paradoxwikis.com/Modifier_effects)

## A list of different localization text keys
### [Localization Keys](https://forum.paradoxplaza.com/forum/threads/localization-text-key-list.946323/)

## Guides
### [BigWeevil's General Modding Guide](https://docs.google.com/document/d/1M6vrSN4sEgXID59jwGg3ATymU1gRu6qNEA4Fw_O1RQU/edit)
### [Radsterman's Advanced Modding Guide (Incomplete)](https://docs.google.com/document/d/1xjTbUN6P8EtvcHBbULupJm0VmREtyI4V0t2ORpFi4Jo/edit)
### [Manually Adding Provinces Guide](https://www.reddit.com/r/paradoxplaza/comments/3s6j0b/adding_new_provinces_to_victoria_2_a_miniguide/)
### [Creating New Units Types Guide](https://www.reddit.com/r/victoria2/comments/jh2qqb/a_guide_to_creating_new_units/)
### [New Religions Guide](https://forum.paradoxplaza.com/forum/threads/victoria-2-hod-creating-adding-new-religion.856476/post-19365249)
### [Multiplying Pops (Requires EMeditor)](https://stackoverflow.com/questions/64560449/trying-multiplying-numbers-on-a-line-starting-with-the-word-size-with-a-consta)
### [Assimilating Pops Via Event/Decisions Guide](https://www.reddit.com/r/victoria2/comments/k4kehk/how_to_assimilate_pops_by_event/)
## Emulation Guides
### [IF Emulation](https://eu3.paradoxwikis.com/IF_Emulation)
### [MetaRegions](https://eu3.paradoxwikis.com/Metaregions)

## Tools and Programs
### [Scenario Editor](https://sourceforge.net/projects/eug/files/Clausewitz%20Scenario%20Editor/Scenario_Editor_0.9.7.zip/download)
![alt text](https://github.com/JmanThunder/Victoria-2-Moddding-Tools-and-Guides/blob/main/pictures/how_to_use_scen.png)
### [Nation Establisher (Tag Maker)](https://forum.paradoxplaza.com/forum/threads/victoria-2-tag-creator.685792/)
### [Victoria 2 Utilities (includes the 2 above but outdated)](https://www.dropbox.com/s/f6p3sj0oz6qd5kk/Vic2%20Utilities.rar?dl=0)
#### The Victoria 2 Utilities include
#### -**Positions Editor**: Modify where things appear in each province
#### -**Validator: Check** problems in your mod
#### -**Scenario Editor**: Change province ownerships among many other things (see the picture above on getting it working)
#### -**MapChecker**: Checks that positions are in the right place and that provinces are in only one state (untested in 3.04, please ping me if it works)
#### -**POPAdjuster**: Clunky tool which increases POPs by multiplying them by a certain number. Can target based on type, religion, culture and province. For some people it might be better than editing by hand, though. If you have trouble getting it to work, delete vick_install.txt and start the tool again.
#### -**ProvinceOwnership**: A tool for editing province history files en masse: owners, controllers, cores and other things found in there. Makes ugly files, but they work.
#### - **TranslationCopier**: Only remotely useful if you plan on catering to people who play with French or German versions.
#### - **Nation Establisher**: A nice tool for making nations quickly if you don't like to do it by hand. Assumes that you're using the same kind of country files as vanilla (so it doesn't have extra reforms added by mods like HPM/HFM)
### [Economic Analyser](https://cdn.discordapp.com/attachments/794689679790309406/836637523647135844/Vic2ESA.rar)
### [Production Calculator](https://drive.google.com/file/d/1mOie1L1XjXxdvwggTP9csaLHpEUqu7fX/view?usp=sharing)
### [Victoria II Formating Tool](https://github.com/ze/v2format/releases)
### [Victoria II Mod Cleaner(makes mods more readable to Victoria 2)](https://github.com/ze/v2tools)
### [Terrain Editor](https://drive.google.com/file/d/165jAW8iTrUxv4XUEMUUw0mk_VBzyzatV/view?usp=sharing)
### [Missing Bracket Finder (when the validator says "line -1, column -1")](https://jmrchelani.github.io/missing-braces-finder/) 
### [Blank Map Maker](https://cdn.discordapp.com/attachments/791309512652226591/910351549690171452/ck2autoborder.7z)The tool requires[Processing3](https://processing.org/download)
### [Victoria 2 Province Creator](https://github.com/Cukla/VicII-Province-Creator/releases) and [Experimental Version (Can edit existing provinces but make break)](https://cdn.discordapp.com/attachments/933500881880616980/935323895681142834/Vic2_province_creator.zip)
![image](https://user-images.githubusercontent.com/53799051/151108543-09e4ebbd-dbc7-428d-b0a8-b914b184bc07.png)

## Editors
### Text editors
### [Notepad++](https://notepad-plus-plus.org/downloads/)
### [Sublime Text](https://www.sublimetext.com)
### [Visual Studios Code](https://code.visualstudio.com/)
### Image editors
### [Paint.net](https://www.dotpdn.com/downloads/pdn.html)
### [GIMP](https://www.gimp.org/downloads/)

## General Practices

### General Text Editing Practices
#### - *VERY IMPORTANT* Make sure all files are saved in Windows-1252 (or ANSI) character encoding. Many modern programs will save in UTF-8, which will result in odd characters. Reference for which characters can be displayed by Victoria II: https://en.wikipedia.org/wiki/Windows-1252
#### - Comment *every* item with at minimum the localisations of the item, so future modders know what is what.
#### - Use Spell and Grammar Checks
#### - Decision, modifiers, goods, items, etc. code should be in all lower case.
#### - Organize the content txt files in alphabetical order, when it makes sense to do so.
#### - Exception: Organize decisions and event chains together when they are related.

## Event Best Practices 
#### - When appropriate, use cultures / culture groups as limits rather than TAGs.
#### - Use localisation for event text rather than text in the code
#### - Use the following formats for localising your events:
####	title = "EVTNAME#########"
####	desc = "EVTDESC#########"
####	option A = EVTOPTA##########"
####	option B = EVTOPTB##########", etc.
#### - Keep events in each file either in numerical order or group order for event chains in each file
#### - Use Audax Validator after any edits
  
