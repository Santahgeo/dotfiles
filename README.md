# Santahgeo's Dotfiles For Bspwm
I am u/Siurzu & GodHand Siurzu
_________________________________________________________________________________________________________________________________________________________

# Info:

Window Manager: BSPWM

Bar: Polybar

Launcher Rofi

Distro: Arch Linux

Gtk Theme: ~~Gruvbox~~ Colloid Dark (I changed my Gtk theme, as you can see in my Pywal Screenshots)

Colorscheme: Gruvbox (I edited up a little to flow with some of my wallpapers)

Music Player: MPD/Ncmpcpp

Main Web Browser: Firefox with Gnome Empathy theme

File Manager: Nemo

Icons: Tele Icon Circle

_________________________________________________________________________________________________________________________________________________________

# Pre-Installation:

Arch Linux: sudo pacman -S polybar bspwm picom sxhkd rofi dunst kitty cava feh ttf-meslo-nerd-font-powerlevel10k

Ubuntu: sudo apt install polybar bspwm picom sxhkd rofi dunst kitty cava feh

Fedora: sudo dnf install polybar bspwm sxhkd rofi dunst kitty cava feh 

# ***Optional: Donwloading picom-ibhagwan-git for blurring.***

Arch: yay -Syu picom-ibhagwan-git

**Fedora and Ubuntu Users can read https://github.com/yshui/picom/blob/next/README.md#build to see how to build the package.**

_________________________________________________________________________________________________________________________________________________________
# Make sure you install Iosveka Nerd Fonts 2.0 for icons to work on polybar. This could be found at: https://sourceforge.net/projects/nerd-fonts.mirror/files/v2.0.0/
# Also install Melso-Nerd-Fonts if you want the correct fonts to work in Kitty.
_________________________________________________________________________________________________________________________________________________________
# Make your directories if needed:

mkdir ~/.config/bspwm

mkdir ~/.config/polybar

mkdir ~/.config/dunst

mkdir ~/.config/kitty

mkdir ~/.config/cava

mkdir ~/.config/sxhkd

mkdir ~/.fonts

mkdir ~/.config/picom

mkdir ~/Pictures/Wallpapers
________________________________________________________________________________________________________________________________________________________

# Applying Dotfiles:

cp ~/dotfiles/Wallpapers/life.png ~/Pictures/Wallpapers

cp ~/dotfiles/bspwm/bspwmrc ~/.config/bspwm ***(Optional If you want to use my bspwm configurations)*** 

cp ~/dotfiles/sxhkd/sxhkdrc ~/.config/sxhkd ***(Optional If you want to use my keybinds configurations)*** 

cp ~/dotfiles/dunst/dunstrc ~/.config/dunst

cp ~/dotfiles/kitty/kitty.conf ~/.config/kitty

cp ~/dotfiles/picom/picom.conf ~/.config/picom

cp ~/dotfiles/polybar ~/.config/polybar

cp ~/dotfiles/cava/config ~/.config/cava


sudo cp ~/dotfiles/Rofi/orgin.rasi ~/usr/share/rofi/themes

________________________________________________________________________________________________________________________________________________________

# Optional Stuff:
- Using Pywal to make you polybar and terminal flow better with your wallpaper. Use this for consitant themeing
- 
# Credits:

Rofi Configuration: https://github.com/yuky2020/rofi-themes

Neofetch Configuration: https://github.com/Chick2D/neofetch-themes

Gtk Theme: https://www.gnome-look.org/p/1681313

Cursor Theme: https://www.gnome-look.org/p/1831077

Kitty Theme Based On: Dexpota Kitty Themes (Gruvbox-Dark) /\ https://github.com/dexpota/kitty-themes#gruvbox-dark
(I just added some transparency to it and different font)

Firefox Theme: https://github.com/rafaelmardojai/firefox-gnome-theme

Color Scheme Orginal Source: https://github.com/morhetz/gruvbox

Icom Themes: https://github.com/vinceliuice/Tela-circle-icon-theme
_________________________________________________________________________________________________________________________________________________________
- Alternetive Stuff
Gtk Theme: https://github.com/vinceliuice/Colloid-gtk-theme (The Gtk Theme Im using as a now) 

_________________________________________________________________________________________________________________________________________________________

# Screenshots:
![1](https://user-images.githubusercontent.com/109631397/180031227-edc16dc9-f647-4bda-8feb-df85ade3edab.png)

![Screenshot from 2022-07-19 18-37-35](https://user-images.githubusercontent.com/109631397/179865883-8fca5407-0f73-42e0-ac8f-09b1c731fdfc.png)
![Screenshot from 2022-07-20 11-10-10](https://user-images.githubusercontent.com/109631397/180031250-c79aaf3b-b602-4c4f-aa37-7ee9567ea1e5.png)
![Screenshot from 2022-07-19 18-37-17](https://user-images.githubusercontent.com/109631397/180031302-fe6f59ea-9fb7-4d6e-a5ba-976de2dd3d52.png)
________________________________________________________________________________________________________________________________________________________

# Pywal:

To use Pywal just do: 
- wal -i /path/to/wallpaper 
- (You can see a exampe in one of my screenshots
- ____________________________________________________________________________________________________________________________________________________
# Issues With Pywal:

# Pywal Not applying colorscheme when I login back into bspwm! How to fix this? :
- Open the terminal and type
- cat ~/.cache/wal/colors.Xresources
- Open ~/.Xresources in your file editor of chose.
- Copy what the output of cat ~/.cache/wal/colors.Xresources is and copy it to you ~/.Xresources

If you don't have a Xresources file do: mkdir ~/.Xresources
- If you wont to use my default polybar colorscheme, delete everything in the ~/.Xresources file.

# Pywal Not Applying to kitty
- Open your [shell]rc file and put 
- cat ~/.cache/wal/sequences
- At the end of it.

# Examples:
![Screenshot from 2022-07-25 19-38-09](https://user-images.githubusercontent.com/109631397/180898151-a909c470-37c8-43b6-b27a-f448d12a4d20.png)

![Screenshot from 2022-07-25 19-36-45](https://user-images.githubusercontent.com/109631397/180898155-d406b36e-ad18-4416-b5e7-b82ff3458044.png)


# Pywal Screenshots:
![Screenshot from 2022-07-25 18-59-26](https://user-images.githubusercontent.com/109631397/180895056-da05f0d1-e3e1-4297-9060-cb68ac6fd4f9.png)

![Screenshot from 2022-07-25 19-00-07](https://user-images.githubusercontent.com/109631397/180895069-1c2601af-72db-43f8-978d-3c2a03663fdd.png)

![Screenshot from 2022-07-25 19-06-42](https://user-images.githubusercontent.com/109631397/180895232-02f798a8-9818-4e70-98b3-bfbbfcc0bcfc.png)




