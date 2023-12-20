
**Default programs**

* **Window Manager**: i3-gaps
* **Window Manager**: bspwm
* **Terminal**: Alacritty
* **Status Bar**: Polybar
* **Shell**: Oh My Zsh 
* **App Launcher**: Rofi
* **System Info**: Neofetch
* **Text Editor**: Neovim
* **Hotkey Daemon**: sxhkd
* **Notifications**: dunst
* **PDF Reader**: zathura
* **Screenshot Tool**: maim
* **Image Viewer**: feh
* **Video Player**: mpv
* **Music Player**: cmus
* **ls**: exa 

**Optional Programs**

* **Fuzzy Search**: fzf
* **File Manager**: nnn
* **Image Viewer**: sxiv
* **Music Daemon**: mpd
* **Music Player**: ncmpcpp
* **find**: fd
* **grep**: ripgrep
* **curl**: httpie
* **cat**: bat

### Installation

This little script will install a collection of command line tools, two window managers, and a terminal emulator. Installation is easy:

1. Install Arch Linux and make sure you have `base-devel` and `git` packages.
2. `git clone https://github.com/tonijarjour/autorice.git .dotfiles`
3. `cd .dotfiles` (You **must** be inside the cloned directory)
4. `sh install.sh`
5. Restart your computer after the script finishes.

keybindings
**Global**

* `mod return` to start a Terminal.
* `mod space` to use the app launcher.
* `mod h,j,k,l` to move between windows.
* `mod 1,2,3...` to move between workspaces.
* `mod shift h,j,k,l` to swap window positions.
* `mod shift 1,2,3...` to send a window to a workspace.
* `mod alt w` to load a new random wallpaper.
* `mod printscreen` to select an area to capture. 
* `printscreen` to take a screenshot.
* `mod left click` to move a floating window.
* `mod right click` to resize windows.
* `mod escape` to reload the hotkey config.

**bspwm**

* `mod arrow keys` to move a floating window in bspwm.
* `mod w` to close a window in bspwm.
* `mod alt r` to restart bspwm.
* `mod alt q` to quit out of bspwm.
* `mod s,t,f,m` to make a window stack (float), tile, fullscreen, monocole in bspwm.
* `mod c` to cycle through windows in bspwm.
* `mod alt h,j,k,l` to make a window larger in bspwm.
* `mod shift alt h,j,k,l` to make a window smaller in bspwm.

**i3**

* `mod shift r` to restart i3.
* `mod shift c` to reload i3 config.
* `mod shift e` to quit out of i3.
* `mod shift q` to close a window in i3.
* `mod semicolon,v` to split a window horizontally, vertically in i3.
* `mod f` to toggle fullscreen in i3.
* `mod shift space` to toggle a window to float or tile in i3.
* `mod c` to toggle focus between floating and tiled windows in i3.
* `mod r` to enter resize mode in i3.
* `mod h,j,k,l` to shrink and grow a window (while in resize mode) in i3.

