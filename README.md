# My AstroNvim config

NOTE: This project is now archived, as AstroNvim has moved to version 3. You can find my new config [here](https://github.com/sergeant-savage/astronvim3-config). 

This is my AstroNvim config. It contains my personal preferences for my development environment.

## Installation

This requires:
- Neovim
- Some technical know-how (Optional)

First, follow these instructions to install AstroNvim.

Make a backup of your current nvim folder like so:

`mv ~/.config/nvim ~/.config/nvim.bak`

Clean neovim folders (Optional but recommended)
```
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

Now, clone the repository and run Neovim to initialize AstroNvim
```
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
nvim
```

Once AstroNvim is installed, clone this repository to `~/.config/nvim/lua`

`git clone https://github.com/sergeant-savage/astronvim-config ~/.config/nvim/lua/user`

Then, open Neovim and run `:PackerSync`.

Lastly, restart Neovim. You should now have a copy of my setup.
