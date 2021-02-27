# MagicPuddle - WSL

There is a WSL version of MPOS in the Windows App Store,
you are encouraged to build your own. More on the subject can be found in the MagicPuddle [Documentation](wsl-make-wsl.md).

## Windows Subsystem For Linux

### Enable WSL

To enable [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10) or WSL for short.
Open Windows Powershell and execute the following.

    > dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

### Enable VM

    dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

### WSL 2

Download and run the [Linux kernel update](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi) package.

Set WSL2 as your default version

    wsl --set-default-version 2

## Install A Distribution

### MPOS WSL

    > winget install mpos-wsl

### Kali WSL

    > winget install kali
