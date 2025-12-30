# Notes

I use [Obsidian](https://obsidian.md/) as it lets me build off my own files, but the flexibility Obsidian offers in the interface clashes with some of my behaviours. This lets me version control the things that I want to actually keep in-line or have visibility over, and ignore the files that I don't care about.

This repository sits above my vaults as I also run a cut down vault that my [Supernote Nomad](https://supernote.com/products/supernote-nomad) syncs to, and uses a [plugin](https://github.com/philips/supernote-obsidian-plugin) to easily process the notes. Keeping separation between `raw` and `processed` notes is quite important to me, so separate vaults prevent me from getting sidetracked when on either task.

After seeing the [Pebble Index](https://repebble.com/index) announcement with the tagline `External Memory For Your Brain`, that really felt like it captured what I use the contents here for. Not sure if I'll get use out of it, but the concept of quick raw notes that flow through systems within my control sounds great. Whether I'll wear it or just keep it near my electronics workstation I'm not sure, but I'll have to see how it goes with the watch first.

## Syncing

I use [Syncthing](https://syncthing.net/) to synchronise across platforms I use (currently NixOS/iOS/Android), but I ignore the `.obsidian` folder (this repository fills that gap). My NAS archives any sync changes to give me some history, and now I can just focus on my notes rather than wrangling git and forgetting to commit a note that I needed elsewhere.

## Obsidian Bases

Bases have finally filled the need that I had been cobbling together custom solutions to with [Dataview](https://github.com/blacksmithgu/obsidian-dataview), but I really wish that there was a `Save` button or similar for changes to the base views. I want my dedicated views to be consistent, but in the moment I may need to adjust things based on the task at hand. Locking them down in Git lets me reset the view to what I know that I want at any stage, and allows easy changes if I want something permanent.

## AI Use

So far every attempt I've made to use AI/LLM for productivity has cost me time in errors and hallucinations. Maybe some day it'll be useful, but if I can't trust something it currently has no place in my life, and the way LLM's work are inherently untrustworthy. I use linters to keep things aligned, LSP's to assist with code, and workflows to organise and automate what I need. I bootstrap common files from templates/repositories, or 3 way file diff views to try and avoid some copypasta (although there's always something that gets missed).

The only valid usecase I currently have for AI is a more natural sounding TTS that I feed templates filled with directly sourced data (eg. local equivalent of Apple's Personal Update with Siri), and I make use of CalDAV/RSS feeds to back that process. I also use it to sanity check parts lists for projects. I'll see if being able to run larger models on my [Framework Desktop](https://frame.work/au/en/desktop) changes any of this behaviour.

I'll happily argue the point as I find it fascinating what other people come up with to use it for, as long as you come into it knowing that you wont change my opinion on LLM's, but you may spark ideas for what I can improve upon. I've spent years refining my ability to build what I need both personally and professionally, but there's always room for improvement.
