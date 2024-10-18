# Readme
Welcome to my Starforged Starter Vault!  I set this up to play Starforged in a way that fits me best.

## Change Log

### v0.1
- [x] Updated README.md
- [x] Upgraded plugins to latest version (Dataview, Templater, Inline Scripts)
- [x] Changed to a standard structure
- [x] Updated script references to (Characters->1.2_Character, Progress->1.3_Progress, Clocks->1.4_Clocks, Assets->6_Assets, Moves->5_Moves)
- [x] Implement "Failures" track
- [x] https://web.archive.org/web/20120917234510/http://bitdrift.com/post/4534738938/fork-your-own-project-on-github
- [ ] https://help.obsidian.md/Obsidian+Sync/Set+up+Obsidian+Sync
- [x] Add new plugins: Copilot, Advanced Tables, Git
- [x] Create .gitignore file in root
- [x] Create .gitignore files in subdirectories?
- [ ] 



## Setting up Git for vault backup
Follow the instructions here...
- https://publish.obsidian.md/git-doc/Installation

## Modifying Table4one
You will need the following tools.
- Obsidian
- git

How to modify Table4One.
1. Create a new branch from 'main'. Name it the task you're going to do. (i.e. installing_plugins, adding_Force_attribute, updating_copilot)
2. Check-out the new branch
3. Make your changes and test the changes.
5. Add the files that you have changed to the 'staged' commit.
6. Commit the changes with a comment.
7. Push the changes to github.com
8. Merge the changes into the main branch.
9. Delete the new branch.

## Fonts
For the headings, I'm using [Xolonium font](https://www.fontspace.com/xolonium-font-f17644) and [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans) as the interface font.

## Plugins
This vault only works with the [Dataview](https://github.com/blacksmithgu/obsidian-dataview), [Templater](https://github.com/SilentVoid13/Templater), and most importantly: [Inline Scripts](https://github.com/jon-heard/obsidian-inline-scripts) plugins. I have included Copilot, Git (for backup), and Advanced Tables.

## CSS Snippet
The `snippets.css` file contains all the folder icons, color coding of new callout boxes, title and header fonts, fixing the tasks so they don't strike through when marked, and an inversion code so that the SVG files will invert black/white based on light/dark mode.

## Design Goals
Here were some specific design goals:

1. **Never Leave the Journal:** I usually play solo-rpgs by writing long-form like in a story.  For that reason, I wanted to minimize the number of times I'd have to leave the journal entry of the current play session.  Inline Scripts allows me that freedom in all but a few cases (like creating a new vow).
   
2. **Minimize the Number of Reference Windows:** Starforged has a lot more fiddly bits than Ironsworn which has really slowed down my play.  I wanted to eliminate the friction by not having to sort through tons of reference windows or menus.  To help with that, you can call a move reference directly into the journal and can access the oracles from an inline script.  My workspace is a journal on the left, with the character sheet on the top-right and other reference note (like a move or oracles) on the bottom-right.
   
3. **Make Mechanics Distinct from Story:** One of the things I've always done playing in a word processor is to have the mechanics as separate callouts so that you can see clearly what is fiction and what is game play.  Therefore, nearly any inline script you call here will give results in a callout which can be unfolded for more details.

### No Map?
I didn't do anything to set up a sector map because I never play with a map.  There are other Obsidian vaults out there for Ironsworn and Starforged which you can use as a template for maps if you'd like.

## Folder Structure
1. **Characters:** All the Inline Scripts shortcut commands require that the Characters folder structure remain as it is now.  Any character with stats that you need to access through moves should be in this folder.

2. **Images:** All images are pulled from the Images folder.  You can add additional folders and images, but don't change the structure of the images currently there.

3. **Progress:** Any thing that will have a progress track must go in the Progress folder.  This includes combat tracks, vows, bonds with NPCs, etc.


## Support Folder
This folder contains all the Inline Script shortcut files.  If you are making your own shortcut files, add them here.

## Templates Folder
The Templates folder is necessary for creating new files with progress tracks.  However, the Oracle, Move, and Asset templates were only used for importing JSON data and can safely be removed.  You can also add any other templates to this file that you would like the Templater plugin to have access to.

## Credits
All original Assets, Moves, and Oracles are from [Dataforged](https://github.com/rsek/dataforged), the official Starforged repository. Starsmith: Expanded Oracles, Starsmith: Mecha Merc assets, and Starsmith: Assets are my original works (available in PDF and print form on [DriveThruRPG](https://www.drivethrurpg.com).)

Image, Map, and Stethoscope icons from [Lucide](https://lucide.dev/)

All other icons from [game-icons.net](https://game-icons.net) by Delapouite, et. al.

This set-up only works with the [Dataview](https://github.com/blacksmithgu/obsidian-dataview), [Templater](https://github.com/SilentVoid13/Templater), and most importantly: [Inline Scripts](https://github.com/jon-heard/obsidian-inline-scripts) plugins.
