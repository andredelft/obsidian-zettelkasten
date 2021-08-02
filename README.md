# Zettelkasten

Setup for using the Zettelkasten system in Obsidian. Based on: https://www.knowledgeworker.blog/p/how-to-take-smart-notes-in-obsidian

## Setup

Install the [`obsidian-citation-plugin`](https://github.com/hans/obsidian-citation-plugin), by going to 'Settings' > 'Community plugins' (turn Safe mode OFF) > 'Browse'. Follow the instructions on the [plugin homepage](https://github.com/hans/obsidian-citation-plugin) to setup a CSL JSON export of the relevant library, and make sure to output this in `_meta/library.json`.

## Usage

This vault includes 'literature notes', 'permanent notes' and 'index notes' which are kept in the corresponding folders `literature/`, `zettelkasten/` and `index/`. Hotkeys (for mac) and templates are set up to create each one of these notes:

* New bibliography note: <kbd>ctrl</kbd> + <kbd>C</kbd>
	* Inline citation: <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>C</kbd>
* New permanent note: <kbd>ctrl</kbd> + <kbd>Z</kbd>.
* New index note: <kbd>cmd</kbd> + <kbd>N</kbd> (new file), <kbd>cmd</kbd> + <kbd>T</kbd> (apply template), <kbd>Enter</kbd>

If you want to track these notes using git, make sure to delete the `.gitignore` files in each folder.
