# bash-powerline

Powerline for Bash in pure Bash script.

![bash-powerline](https://raw.github.com/iddinev/bash-powerline/master/screenshots/bash-powerline_my_material_light.png)
![bash-powerline](https://raw.github.com/iddinev/bash-powerline/master/screenshots/bash-powerline_my_material_dark.png)

The screenshots are produced using my version of the terminal material theme.  
The original material theme can be found here:  
[terminal.sexy](https://terminal.sexy/#JjI47O_xJjI4_5gAi8NK_8EHA6n06R5jAJaIz9jcN0dP_6dNnMxl_6AAgdT6rRRXJqaa7O_x)  
[tlatsas/xcolors](https://github.com/tlatsas/xcolors)  
XFCE terminal version of my material theme:  
[iddinev/material](https://github.com/iddinev/MyMaterial)

This fork is based on
[riobard/bash-powerline](https://github.com/riobard/bash-powerline), please refer to its README for more
information.

I've included some personal modifications/additions:
- Simpler (not reliable on fancy fonts) symbols.
- Modular look - easy for extension and copy-pasting around - paths/time/dates.
- Additional sections: tmux, date, OS flavour, root/user, hostname.
- Colors are picked to work ok with both dark and light themes (solarized and my material mentioned above).

## Installation

Download the Bash script

    curl https://raw.githubusercontent.com/iddinev/bash-powerline/master/.bash-powerline > ~/.bash-powerline

And source it in your `.bashrc`

    source ~/.bash-powerline

