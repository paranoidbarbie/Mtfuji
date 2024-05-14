# Mtfuji
Hyprland theme based on Mt Fuji , Light / Dark 

Copy paste the files inside to see the theme being reflected on your screen 

<p align="center">
<img src="https://github.com/paranoidbarbie/Mtfuji/blob/main/assets/mtfuji-day.png" style="max-height:500px"/>
</p>

<p align="center">
<img src="https://github.com/paranoidbarbie/Mtfuji/blob/main/assets/mtfuji-night.png" style="max-height:500px"/>
</p>

## To install the theme just copy paste the files inside the mtfuji direcotry to your ~/.config (works in arch, not sure about Nix).

 <p align="center">
   <h1/> Nvim Configuration </h1>
 </p>

> Run :Lazy to install all the nvim configs.
> [Read more about lazynvim](https://github.com/folke/lazy.nvim)

#### Preset nvim config
```
vim.cmd("set number")
vim.cmd("set tabstop=4")
vim.cmd("set shiftwidth=4")
vim.cmd("set softtabstop=4")
vim.cmd("set mouse=a")

```

#### To change to the dark theme 

> change this line ``` vim.cmd.colorscheme "tokyonight" ``` to ``` vim.cmd.colorscheme "fluromachine" ```
> Following the above line is the lualine setup ``` options = { theme = 'tokyonight' } `` change it to fluromachine too if you want to ig.

Know more about the themes [tokyonight](https://github.com/folke/tokyonight.nvim) && [fluoromachine](https://github.com/maxmx03/fluoromachine.nvim)

List of the rest of the plugins used 
[Lualine](https://github.com/nvim-lualine/lualine.nvim)
[Nvim Tree](https://github.com/nvim-tree/nvim-tree.lua)
[Lsp Zero](https://github.com/VonHeikemen/lsp-zero.nvim)
[Lsp Installer](https://github.com/williamboman/mason.nvim)
[Startup Nvim](https://github.com/startup-nvim/startup.nvim)
[Telescope](https://github.com/nvim-telescope/telescope.nvim)

#### Kindly check their docs to customise the themes and configs to make it your own. 














