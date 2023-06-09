# Dotfiles 2.0!

This project is the result of many hours of ricing to make the perfect Xmonad setup

(at least for my standards).

## UPDATE
I am no longer using this setup so it will not be updated anymore.
If you are intersted in my more updated setup please check out my other repository. [buttery-picom](https://github.com/allusive-dev/buttery-picom)

NOTE:

This does not contain a full install. I want my own install to be as peronal as possible since I put weeks into making this and learning how to configure everything. HOWEVER if you want something similar to mine please check out [Axarva](https://github.com/Axarva/dotfiles-2.0)s configuration which is what mine is based off.

I have linked some files like my wallpaper, neofetch image, kitty and picom configurations. 

There is a quick guide on how to setup your terminal like mine so feel free to check that out

## Index

- [Screenshots](https://github.com/Alllusive/dotfiles-2.0/edit/main/README.md#screenshots)

- [Info](https://github.com/Alllusive/dotfiles-2.0/edit/main/README.md#info)

- [Packages](https://github.com/Alllusive/dotfiles-2.0/edit/main/README.md#extra-packages)

- [Installation](https://github.com/Alllusive/dotfiles-2.0/edit/main/README.md#installation)


## Screenshots
![desktop](https://user-images.githubusercontent.com/99632976/224847936-71419083-59f4-4f63-b3c5-4f332d624904.png)
![finale of the desktops FULL](https://user-images.githubusercontent.com/99632976/226474866-cc6a4e7b-759b-4524-ad3a-a04ce7233100.png)


## Info
This configuration is based off [Axarva](https://github.com/Axarva/dotfiles-2.0)s rice with quite a few alterations.

THIS CONFIGURATION IS FOR ARCH LINUX ONLY!!! (might work for arch-based systems but untested).

This rice is configured for dual monitors stacked vertically, However it should work with any layout as long as you are willing to configure the tint2conf to fix any graphical issues.


## Extra Packages

- Cava (Terminal Music Visualizer)

- zsh terminal with [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and the [auto-suggestions](https://github.com/zsh-users/zsh-autosuggestions) plugin.

- neofetch

- Librewolf (better firefox)

- *to be expanded*

## Installation

If you just want to get my terminal here are the instructions:

1. Install kitty `sudo pacman -S kitty`

2. Download this github repository or use `git clone https://github.com/Alllusive/dotfiles-2.0` (requires `git`)

3. If downloaded from the repo, unzip the file.

4. Copy the kitty folder to `~/.config`

5. You should now have a `kitty` folder in `~/.config`

6. If you have your own font, you will need to edit the kitty.conf with your own font, otherwise make sure to install JetBrains Mono with `sudo pacman -S ttf-jetbrains-mono`

7. Install picom `sudo pacman -S picom`

8. Copy `picom.conf` from `dotfiles-2.0/picom-simple` into `~/.config`

9. If you want window rounding, Open the file in a text editor and uncomment `corner-radius = 12;`

10. Using your window/desktop managers config, setup to run `picom` at startup.

11. Make sure to change your default terminal for your WM/DE to kitty.

12. Enjoy!

