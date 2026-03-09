# ezQWTF — a Modern QuakeWorld Team Fortress Client
Homepage: Coming Soon

Community discord: Coming Soon


This is the official client of the QuakeWorld Team Fortress Unification Project,
whose goal is to consolidate the sub-communities of QuakeWorld Team Fortress. 

The intent is to make it easy for newcomers, veterans, and returning players alike to simply launch 
a client and jump into a game. No third-party tools, no complex config setups, no hassle.

This is the right place to start playing QuakeWorld&reg; Team Fortress — the precursor
to Team Fortress Classic and Team Fortress 2.

Forked from ezQuake, ezQWTF combines the features of all modern QuakeWorld® clients, and adds
some quality-of-life improvements and TF-specific features. Experience the very first Team Fortress
game in all of its fast-paced, thrill-ridden glory in the modern age without adhering to any particular
community's setup process (which usually works on some servers, but not on others).

## ezQuake-specific Features

 * Modern graphics
 * [QuakeTV][qtv] support
 * Rich menus
 * Multiview support
 * Tons of features to serve latest pro-gaming needs
 * Built in server browser & MP3 player control
 * Recorded games browser
 * Customization of all possible graphics elements of the game including Heads Up Display
 * All sorts of scripting possibilities
 * Windows, Linux, MacOSX and FreeBSD platforms supported (SDL2).

## ezQWTF-specific Features

*this is mostly servering as a "to-do" - though much of this has already been completed, just not committed until further testing has been completed*

 * TF-only server lists
 * TF-specific conbacks and menu graphics
 * Integrated MVDSV launcher for quick server setup within the client itself
 * Built-in tutorials for new players
 * TF-specific keybinds located within Options menu
 * Configurable custom skin packs, texture packs, and model packs (similar to Minecraft's approach to resource packs)
 * Better mouse support in menus
 * Togglable verbose or GUI loading screens
 * CustomTF/ProzacTF custom class saving
 * CustomTF/ProzacTF custom class GUI buy menu (similar to Counter-Strike)
 * AttackersGoRed (AGR) support
 * FortressOne/QWTF.Live support
 * ...and much more to come!

The standalone client comes only with bare minimum of game media. If you want to
experience ezQWTF with modern graphics and other additional media including
custom configurations, maps, textures and more, try using QWTF Unification installer.

## Support

Discord coming soon.

If you have found a bug, please report it.

## Installation guide

To play Quakeworld you need the files *pak0.pak* and *pak1.pak* from the original Quake-game. Though the 
client can be downloaded as a standalone package and extracted to a directory of your choosing, the install 
executable (Windows only, for now) will detect any existing installation of Quake (original retail copy or 
digital Steam copy) and use this as the directory for installation.

You will also need a copy of [TF2.8](https://www.moddb.com/mods/team-fortress/downloads/team-fortress-28-release) 
at a minimum in order to connect to multiplayer servers.

### Install ezQWTF to an existing Quake-installation (standalone)
If you have an existing Quake-installation simply extract the ezQWTF executable and TF2.8 into your Quake-directory.

A typical error message when installing ezQuake into a pre-existing directory is about *glide2x.dll* missing.
To get rid of this error, remove the file *opengl32.dll* from your Quake directory.

### Install ezQWTF to an existing Quake-installation (installer) (Windows only)
If you have an existing Quake-installation, the installer will automatically extract the ezQWTF executable 
and TF2.8 into your Quake-directory. The full install also includes several updated models and texture packs
to help decrease download time for additional files upon connecting to a server.

If you have a digital copy of Quake purchased through Steam, the installer will automatically add a Library 
shortcut for QuakeWorld Team Fortress.

The installer will also rename/backup the file *opengl32.dll* in your Quake directory if detected.

If the installer detects an existing ezQuake setup within your Quake-directory, it will ask if you would like 
to use your existing ezQuake configuration, or if you would like to use the suggested defaults for ezQWTF specifically.

### Minimal clean installation
If you want to make a clean installation of ezQWTF you can do this by following these steps:

1. Create a new directory
2. Extract the ezQWTF-executable into this directory
3. Create 2 subdirectories called *id1* and *fortress*
4. Copy *pak0.pak* and *pak1.pak* into the *id1* subdirectory
5. Copy all files from TF28.zip into the *fortress* directory 

## Compiling

For a more in-depth description of how to build on all platforms, have a look at 
[BUILD.md](BUILD.md).

## Credits / Thanks

*(this is by no means a comprehensive list and will be updated as development continues)*

[QW Group](https://github.com/QW-Group)  
[ezQuake Team](https://ezquake.com/info/about.html#credits)  
My father, for introducing me to Team Fortress in Summer 1997, which became a life-long passion.  

## Nightly builds

Coming soon
