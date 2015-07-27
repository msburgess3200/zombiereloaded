# Installing Zombie:Reloaded #

## Install Plugin Requirements ##

Before adding files from Zombie:Reloaded, make sure you have the following requirements installed:
  * [Metamod:Source](http://sourcemm.net/) 1.8.6+
  * [SourceMod](http://sourcemod.net/) 1.4.0+
  * [SDK Hooks extension](http://forums.alliedmods.net/showthread.php?t=106748) 2.0+

This guide doesn't cover how to install the above requirements. See their documentation for more instructions.

Though, SDK Hooks is easily installed by just extracting the contents into the "cstrike" folder on the dedicated server and all files should go in the correct folders.

**Note:** Verify that both Metamod:Source and SourceMod is running before continuing by typing these commands in the server console: "meta version" and "sm version". If both give version information it's working, if not go through installation instructions again and verify that everything is in the correct place.

## Install Zombie:Reloaded ##

Zombie:Reloaded is installed in two phases. It has the main release and a patch with updates and fixes. The original release no longer work out-of-box, so the patch is required.

  1. Download the main release: http://code.google.com/p/zombiereloaded/downloads/detail?name=zombiereloaded-3.0.0-b2.zip
  1. The folder structure in the release is prepared for the dedicated server. Extract the contents of the main release into the "cstrike" folder on the dedicated server.
  1. Due to the release being old, delete the following files on the server. These are obsolete and no longer used:
    * cstrike/addons/sourcemod/extensions/zrtools.ext.dll
    * cstrike/addons/sourcemod/extensions/zrtools.ext.so
    * cstrike/addons/sourcemod/gamedata/plugin.zombiereloaded.txt
  1. Get the latest patch from the [downloads page](http://code.google.com/p/zombiereloaded/downloads/list) and extract its content into the "cstrike" directory on the dedicated server. Allow it to overwrite extisting files so the old release will be updated.
  1. Start the dedicated server and verify that Zombie:Reloaded is running by typing this command in the server console: "zr\_version".

If Zombie:Reloaded isn't running check the SourceMod error logs at cstrike/addons/sourcemod/logs/. Look for messages from zombiereloaded.smx.

## Manual ##

The manual describes configuration details of every feature in Zombie:Reloaded. It's recommended to look through it to get to know details about the features and how to configure them.

The manual is located in zrdocs/zr\_manual.htm in the latest patch. Make sure you have a look at it before reporting problems.