# Common Variables

Variables in GNU/Linux and UNIX based [operating systems](/os/OperatingSystem.md)

###### * *MPOS default variables are used for examples where applicable.*

## Profile Variables

    HOSTNAME     = magicpuddle
    OSTYPE       = archlinux
    LANG         = EN
    TZ           = Eastern
    SHELL        = /usr/bin/zsh
    MANPATH      = /var/man
    USER         = mpos
    HOME         = /home/mpos
    MAIL         = /var/spool/mail/mpos
    TERM         = alacrity
    HISTFILESIZE = .histfile
    EDITOR       = vim
    GRAPHICAL_EDITOR = code-insider

###### * *$DISPLAY is set to:0.0 first display of the logged-in machine.*

    DISPLAY = :0.0

## Common Use Variables

These variables are used mainly by an interactive terminal session, scripts, apps, and documentation or manuals.

  ***NOTE*** - *Variables can help with the portability of scripts but may not be recommended.*

    PWD = path to the current directory

Try in a shell

    $ echo $PWD

the output of this command should be

    $ /home/mpos

if you are in the **$HOME** directory of the *mpos* user.

