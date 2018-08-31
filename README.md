# Konphig
Config files for safe keeping 😏

This repo contains various configuration files so they don't have to be recreated. They are designed for Linux environments but most will work in MacOS as well.

## Overview
 * [BASH](https://github.com/wcarhart/Konphig#bash)
 * [git](https://github.com/wcarhart/Konphig#git)
 * [vim](https://github.com/wcarhart/Konphig#vim)
 * [tmux](https://github.com/wcarhart/Konphig#tmux)
 
### BASH
The BASH configurations contain the general `.bashrc` and `.bash_profile` files, but also:
 * `.bash_functions` - **60+ COOL BASH FUNCTIONS!** - file for BASH functions ([see here](https://github.com/wcarhart/Konphig/blob/master/functions.md) for separate BASH function documentation)
 * `.bash_aliases` - file for BASH aliases
 * `.bash_variables` - file for BASH variables

`BASH` configurations adhere to the following architecture:
```
.bashrc
| | | |
| | | .bash_profile
| | .bash_functions  (where functions are saved)
| .bash_aliases      (where aliases are saved)
.bash_variables      (where variables are saved)
```

### git
Basic `git` configurations, also including some helpful `git` aliases.

### vim
Basic setup for `vim`.

### tmux
Single setting for `tmux`.
