# MagicPuddle - Make WSL

Here we will make an MPOS WSL Distribution for Windows 10.

## Prerequisites

* 1
* 2
* 3

## Setup Build Environment

We start by making our build directory if does not yet exist.

    > mkdir -p ~/.src/mpos/wsl/src

Then we change to that folder.

    > cd ~/.mprepos/wsl/src

Now we check to make sure we are in the folder we cahnged to.
To do that we issue the [common variable](../../../variables.md) command [PWD]() in powershell.

    > pwd

This should output something like this

    Path
    ----
    C:\Users\$USERNAME

on windows and like this

    $ pwd
    /home/mpuser/.mprepos/wsl/src

on WSL or a UNIX-like operating Systems.
