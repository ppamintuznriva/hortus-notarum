---
{"dg-publish":true,"permalink":"/gardening/how-to-connect-zotero-7-to-obsidian-mac-os/","created":"2024-09-30T09:11:48.620+08:00","updated":"2024-10-01T08:44:03.800+08:00"}
---


Note: This is assuming you already have both Zotero 7 and Obsidian installed on your machine. Please take note that these instructions werqe made on MacOS. Also, this was supposed to have more images but Netlify has decided to give me nothing but grief this morning.

**Why do this?** Connecting Zotero to Obsidian helps create a more seamless research workflow, where your highlights, notes, metadata, etc. can be easily exported from the former to the latter. This also facilitates keeping your Reading Notes in one place, and lets you make your own concept notes as you read so you can more easily identify themes and connections as you read. This is just one way of doing so, and as you get more familiarized with your workflow, you will be able to make it as complex or simple (simple is better) as you need.

## On Zotero: Better BibTeX for Zotero Plugin
1. [Download](https://github.com/retorquere/zotero-better-bibtex/releases/tag/v6.7.238) the Better BibTeX for Zotero plugin (The file extension is .xpi)
2. Follow the [Installation Instructions](https://retorque.re/zotero-better-bibtex/installation/) for Zotero. 

**What this does:** BBT generates unique 'citation keys' for each reference saved on Zotero (they will start with an '@') and facilitates exportation to Obsidian. More info on the [Retorque](https://retorque.re/zotero-better-bibtex/index.html) website.

## Step 2: On Obsidian: Zotero Integration Plugin

1. Save the [ZI Template](https://drive.google.com/file/d/1xiPVCoDMWQTC4p2AQZTNqjsUrE098JVZ/view?usp=sharing) onto your Obsidian vault. Download it from the link and drag it into your file explorer/Templates folder.
2. If you haven't yet, go to Obsidian Settings and activate Community Plugins. Click 'Browse' and search for 'Zotero Integration', then install and enable the plugin. The next step is to modify the plugin options.

At this point, you can also set hotkeys for Zotero Integration if you like. Click on the 'Hotkeys' button on the left sidebar, search for your Zotero Integration commands and set your desired hotkeys (I like 'Cmd + Ctrl + Z' but you can also use 'Cmd + Ctrl + C' if you're coming from Google Docs and are used to that shortcut).

3. Set the following for the plugin options/settings. 

4. Open the Command Palette by pressing 'Cmd + P' on Mac then search for the plugin's commands (the Name you set in the options. In this case, it is '📖 Reading Note'). Clicking on it will bring up a search bar for Zotero. Look for the reference you need and select it to create your Reading Note.


...and that is it, you're done (for now)!

