---
title: My iOS Shortcuts
focus: docs
type: project
tags: []
created: 2026-01-01
updated: 2026-01-01
archived: false
---

# My Shortcuts

These are intended to be quick and dirty, to get things out of my head as quickly as possible, and then processed and fleshed out when I'm in front of a computer.

## Functions

These support other shortcuts, would like a better way to handle markdown related steps but this is good enough for now.

### Markdown metadata

https://www.icloud.com/shortcuts/4ef77f7b10d54dee912f25937f465c8d

This sets up the same as my [default](templates/default) template, but doesn't close the block to allow more specific shortcuts to add metadata.

### Markdown filename

https://www.icloud.com/shortcuts/012066bd55a7485db9332df022b162ff

This just formats the current date + time to save the note to.

### Is music playing?

https://www.icloud.com/shortcuts/ad0b348fd6604b2099ea1bc74fc43b06

Would love a better way to detect music playing locally, but the second delay on music specific shortcuts isn't too noticeable.

## Obsidian specific shortcuts

All of these depend on the [Markdown metadata](#Markdown%20metadata) and [Markdown filename](#Markdown%20filename) functions.

### Save note

https://www.icloud.com/shortcuts/07b3d7b2bed54870a6d58a413fed8c63

Like the [default](templates/default) template, saves to my `unsorted` notes folder. Either takes input from being shared to, or will prompt for text.

### Save bookmark

https://www.icloud.com/shortcuts/c3ad3edc82d94eb2aeccbb8c46f38f25

Like the [bookmark](templates/bookmark) template, saves to my `bases/bookmarks` folder. Takes input from being shared to, from a link on the clipboard, or prompts to scan a QR code. Prompts to create a QR code, copy, or save to the note for the link that was provided, as I use this to share links with others or open QR codes in the appropriate browser.

### Save song

https://www.icloud.com/shortcuts/7952f19bdab44e16af79a7e1b3efa0d4

Also depends on [Is music playing?](#Is%20music%20playing?).

Like the [song](templates/song) template, saves to my `bases/songs` folder. Takes input from either the currently playing song, or tries to Shazam what's playing. Only Apple Music seems to work for the currently playing, but I don't save songs playing from [Amperfy](https://github.com/BLeeEZ/amperfy) as they are already from my own library.

### Save task

https://www.icloud.com/shortcuts/6ca997a240e14d6fb93db3b333c5df61

Like the [task](templates/task) template, saves to my `bases/tasks` folder. Asks for text input, as well as a priority number (1-10).
