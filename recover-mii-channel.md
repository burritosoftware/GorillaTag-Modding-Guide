# Recover Your Lost or Corrupted Mii Channel

This page will guide you through the process of restoring your Mii Channel to a working state.

### What You Need

> - A working [Homebrew installation](introduction) on Wii U side
> - This release of [FTPiiU Everywhere](http://wiiubru.com/appstore/#/app/fpiiu-cbhc)
> - The latest release of [Python](https://www.python.org/downloads/)
> - An FTP client such as [FileZilla](https://filezilla-project.org/download.php?type=client)
> - <a href="../files/overwrite-wiiu-titlehash.py" download>This Python script</a>

### Instructions

> 1. Extract the `fpiiu-cbhc.zip` file to the root of your SD Card
> 1. Install FileZilla on your computer
> 1. Install Python on your computer

### Recovering The Channel

!> If you are using a system update blocking method, please [remove it](unblock-updates).

> 1. Power on your Wii U and launch the CFW of your choice (Mocha, Haxchi or CBHC)
> 1. Launch the Homebrew Launcher and FTPiiU Everywhere
> 1. Launch FileZilla on your computer
> 1. In FileZilla, type in the IP address displayed by your Wii U in the `Host` field at the top of the window and click on `Quickconnect`
> 1. Navigate to `/slccmpt01/title/00010002`
> 1. Delete the `48414341` folder
> 1. On your computer, double click the previously downloaded `.py` file
> 1. Type in your Wii U's IP address and press Enter
> 1. Wait for it to finish what it's doing
>  - If an `err.log` file has been generated, please visit us in **#wiiu-assistance** on [Nintendo Homebrew Discord](https://discord.gg/C29hYvh)
> 1. Exit FTPiiU Everywhere and the Homebrew Launcher
> 1. Launch the System Settings
> 1. Perform a System Update

You should now have a working Mii Channel.

?> You can now re-enable your [system update blocking method](block-updates).