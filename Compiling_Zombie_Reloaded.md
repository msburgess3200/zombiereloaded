# Compiling Zombie:Reloaded #

The source is both available in release packages and in our repositories.

The original source (in our repositores) require some scripts to prepare the code for compilation.
We use these scripts to put version and build information in the plugin.

Our repositories contains a stan-alone environment with compiler and tools included. Source code in
the release packages are prepared for compilation, but don't include the compiler.

## Compiling source from release packages ##

(ToDo)

## Using our build scripts ##

### Requirements ###

To compile using our scripts you need the following:
  * [Mercurial](http://mercurial.selenic.com/) (linux) or [TortoiseHG](http://tortoisehg.bitbucket.org/) (windows)
  * Make (linux)
  * [Zombie:Reloaded Source Code Repositories](Source.md)


### Getting the source ###

**Windows:**
  1. Optional: Make a new folder where you want the source.
  1. Right click in that folder and select TortoiseHG > Clone.
  1. Enter the source address of the repository you want to clone. Example: https://zr-3-0-b2.zombiereloaded.googlecode.com/hg/
  1. Enter the destination folder where you want the source. This should be a new empty folder (it will be created if it doesn't exist). By default this is the folder you right clicked in.
  1. Click "Clone".

**Linux:**
  1. Optional: Make a new folder where you want the source.
  1. Run the command "hg clone _source_ _destination_" where _source_ and _destination_ is the source address and destination folder. Example: hg clone https://zr-3-0-b2.zombiereloaded.googlecode.com/hg/ zr-3.0-b2


### Compiling ###

**Windows:** Run the compile.bat script.

**Linux:** Use the Makefile with the command "make". When recompiling remember to run "make clean" first, the old files aren't overwritten.

When compiling is done, the plugin binary is located in the build folder.

### Building a release package (linux only) ###

We have a build.sh script for building and preparing a complete release package. This will do everything, from compiling to making a zip archive.

**Syntax:** `./build.sh [--patch <base rev>]`

| **Parameter** | **Description** |
|:--------------|:----------------|
| --patch       | Optional. Builds a patch release containing only plugin binary, docs and files changed since the specified base revision. |
| _base rev_    | Base revision number/id to use. |

**Example:**

This will build a patch four our beta 2 release: `./build.sh --patch 755f95b0981b`

Once the build is completed the zip file will be located in the release folder.