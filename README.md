# Upgrade your command line

## If you are on Windows

If you're not familiar with the command-line, or have only installed things with executables (.exe/.msi), some of the installation instructions might seem overwhelming.
If you're on Windows, I recommend looking for the *Winget* instructions. It's a package manager similar to brew (mac-os) or apt (linux).

For some of the tools here, you need to configure your shell to use it. If you use Powershell on Windows, that typically means adding something to a config file (usually) found at:

`~\Documents\PowerShell\Microsoft.PowerShell_profile.ps1`

Note that this file might not exists, if you have not customized you shell already. 
Look [here](https://learn.microsoft.com/en-us/powershell/scripting/learn/shell/creating-profiles?view=powershell-7.6#how-to-create-your-personal-profile) to learn how to create this file. 

## Nerd Fonts

To get the most out of many of the these tools, you should have a [Nerd Font](https://www.nerdfonts.com/#home) installed on your system.
They can be downloaded here: 

https://www.nerdfonts.com/font-downloads

Just pick whichever one you like (I use FiraCode Nerd Font). 
You might need to tell you terminal emulator to use that font.

## Terminal

You also need a terminal capable of rendering Nerd Fonts. I use [Alacritty](#Alacritty).

### Windows Terminal

On Windows, you can use [Windows Terminal](https://github.com/microsoft/terminal#installing-windows-terminal-canary), which is available from the [Microsoft Store](https://aka.ms/terminal). 

### Alacritty



## Navigation

### Zoxide

Zoxide is an alternative/supplement to the *cd* command. It keeps track of folders you have visited, and uses fuzzy finding to make navigating you system **alot** easier.
Installion and usage instructions can be found in the official repo:

https://github.com/ajeetdsouza/zoxide#installation

It uses *fzf* for fuzzy finding, so you also need that: 
https://github.com/junegunn/fzf#windows-packages

## Prompt

### Starship

[Starship](https://starship.rs) is a very customizable prompt (similar to [OhMyPosh](https://ohmyposh.dev/)).

Installation and configuration instructions can be found on the official website:

https://starship.rs/#quick-install

Note that you need a [Nerd Font](https://www.nerdfonts.com/#home) installed.


