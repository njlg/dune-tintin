# Dune Mud TinTin++ Helpers

These are TinTin++ scripts to help [Dune Mud](http://dunemud.com/) players.

## Setup

These are the steps you should use to start using these scripts / environment. These steps require that you already have created a character in the mud.

1. Copy `characters/example.tin` to a name that matches your character's name (e.g. `characters/george.tin`).
2. Edit the newly created file.
  * Replace `<Name>` with your character's name.
  * Replace `<Password>` with your character's password.
  * Change the `#read guilds/...` line to read whatever guild your character is associated with.
  * Put whatever other character specific configurations in this file.

## How to Use

If you have TinTin++ installed (e.g. Linux, BSD, OSX):
* Open a terminal (e.g. iTerm)
* Navigate to wherever you cloned this repository to
  * E.g. `cd ~/source/dune-tintin`
* Run `tt++ -r ./main.tt`

If you have WinTin++ installed (e.g. Windows):
* Clone or copy the files to where you installed WinTin++ (e.g. `C:\Program Files\WinTin++`).
* Run WinTin++
* Input `#read dune-tintin/main.tin`


## Folder Layout

* characters &mdahs; All character specific configurations
* guilds &mdahs; All guild specific configurations
* maps &mdahs; Maps for all locations. (coming soon)
* paths &mdahs; Paths for looping in certain areas. (coming soon)
