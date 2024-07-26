# Obslimian

![banner](https://raw.githubusercontent.com/fusobotic/Obslimian/main/1%20-%20Attachments/readme_banner.png)

## Setup

1. Download and install [git](https://git-scm.com/downloads)
2. Download and install [Obsidian](https://obsidian.md/)
3. Fork this repo (make it private if you don't want it public)
4. Copy the HTTPS URL from the `< > Code v` button dropdown
5. Open your command prompt (Windows) or your terminal (OSX/Linux) and navigate to where you'd like the vault to live using `cd [directory path]`
6. Clone to new directory using:
```sh
git clone [the url you copied]
``` 
7. Open the vault using Obsidian

## Folder Structure
A minimal [Zettelkasten](https://zettelkasten.de/introduction/) system:
1. Attachments - where your pasted images and other non-md files go
2. Templates - what your new Atoms will look like, default has tags and time created
3. Tags - use `[[wikilinks]]` and click the tag names to add new tags to this folder
4. Atoms - your individual notes go in here, use `ctrl+n` to create new ones

## Community Plugins
Less is more. Here is what's included:
- [Things](https://github.com/colineckert/obsidian-things) - since it looks nice by default and has some useful icons
- [Git](https://github.com/Vinzent03/obsidian-git) - can be used to sync but is better for automatic version history (backs up every minute)
- [QuickAdd](https://github.com/chhoumann/quickadd) - used to replace `ctrl+n` hotkey to make new Atoms with a template

Note: You may want to add [Remotely Save](https://github.com/remotely-save/remotely-save) if you'd like to sync your vault to mobile instead of using git. For best privacy and ownership I would recommend setting up your vault on a local NAS and referencing it there with a shared folder instead.

## Fonts
UI Sans Fonts:
- [Helvetica](https://font.download/font/helvetica-255)
- [Inter](https://fonts.google.com/specimen/Inter)
  
Body Text Serif Fonts:
- [Charter](https://practicaltypography.com/charter.html)
- [Gill Sans](https://font.download/font/gill-sans-std)
  
Code Snippet Monospace Fonts:
- [Jetbrains Mono](https://www.jetbrains.com/lp/mono/)
- [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

They're all free, just install whichever you prefer. You can change them up by reordering them in `Settings -> Appearance -> Fonts`. Restart obsidian for it to reload your available font families.

These fonts were selected specifically for their legibility, variations, and popularity. Most come recommended by [Butterick's Practical Typography](https://practicaltypography.com/). His guide is recommended further reading if you'd like better formatted web, app, and print designs.

I have assigned the same sans font from the UI for headings to give better coherence between the UI and the filenames. Serif is better suited for body text readability- and it looks better for writing in my humble opinion. You may disable this and make all heading text serif by toggling the `sans-heading.css` snippet in settings.
