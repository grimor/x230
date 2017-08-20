## Dotfiles

Nothing special, just the main config for my x230, on Void Linux.

* i3
* i3status
* rxvt-unicode
* vim 
* zsh 
* tmux 

A little note, all the packages installed are in `void_packages`, you can achieve the same result with the following command.

```
xbps-query -l | awk '{print $2}' | sed 's/-[0-9].*//' > void_packages
``` 

