# Source Code #

We use Mercurial as the version control system and you need it to clone complete source code repositories. Use Mercurial on Linux (command line tools), or TortoiseHg on Windows (both GUI and command line tools).

See [Compiling Zombie:Reloaded](Compiling_Zombie_Reloaded.md) for information about compiling.

## Push access ##

Everyone are allowed to clone and download our source, but only authorized developers can push to our repositories. However, you are welcome to submit patches that we could verify and eventually implement.

To submit a patch:
  * use our [main support forum](http://forums.alliedmods.net/forumdisplay.php?f=132),
  * or [create an issue](http://code.google.com/p/zombiereloaded/issues/entry) in the issue tracker.

## Repositories ##

  * [zr-3.1](http://code.google.com/p/zombiereloaded/source/checkout?repo=zr-3-1) Current stable branch (3.1)
  * [zr-3.0-b2 (zr-3-0-b2)](http://code.google.com/p/zombiereloaded/source/checkout?repo=zr-3-0-b2) - Old branch (3.0 beta 2)
  * [zr-dev-base](http://code.google.com/p/zombiereloaded/source/checkout?repo=zr-dev-base) - Development branch
  * [zr-dev](http://code.google.com/p/zombiereloaded/source/checkout?repo=zr-dev) - (Obsolete!) Old development branch
  * [wiki](http://code.google.com/p/zombiereloaded/source/checkout?repo=wiki) - Wiki pages on this site

### zr-dev-base ###

**Browse repository:** http://code.google.com/p/zombiereloaded/source/list?repo=zr-dev-base

  * Pullable: **Yes**
  * Pushable: **Yes**

Main development branch. This is where the latest (experimental) changes are commited. Snapshots from this branch is NOT supported, and they may not even work. We also may do changes that break compatibility.

It's running on a new architecture made by Greyscale (see [smprojectbase](http://code.google.com/p/smprojectbase/)).

### zr-3.0-b2 ###

**Browse repository:** http://code.google.com/p/zombiereloaded/source/list?repo=zr-3-0-b2

  * Pullable: **Yes** (mirror is updated every 30 minutes)
  * Pushable: **No, this is a mirror** (push to equivalent at http://helgeby.no-ip.org/zrdev/hg/)

This is our current stable branch (beta 2 release). It will be updated with mostly bug fixes, but could also get new small features.

Snapshots of this branch should be considered stable, and can be used on main game servers.

### zr-dev (obsolete!) ###

**Browse repository:** http://code.google.com/p/zombiereloaded/source/list?repo=zr-dev

  * Pullable: **Yes**
  * Pushable: **No, it's a mirror** (push to equivalent at http://helgeby.no-ip.org/zrdev/hg/)

Old development branch. Do not use this one. It's only available for browsing old code.

We attempted to convert this to the new architecture, but because it was a mess we decided to start over in a new clean repository (zr-dev-base). We now only keep this so we can browse file and project history.