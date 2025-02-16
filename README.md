# Shadow

A dark, muted colorscheme for [Neovim](https://github.com/neovim/neovim).

## Screenshots

![Screenshot](https://imgur.com/UihTWwk.png)

## Installation

Using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{
    "rjshkhr/shadow.nvim",
    priority = 1000,
    config = function()
        vim.opt.termguicolors = true
        vim.cmd.colorscheme("shadow")
    end,
}
```

Using [packer.nvim](https://github.com/wbthomason/packer.nvim):

```lua
use {
   "rjshkhr/shadow.nvim",
   config = function()
       vim.opt.termguicolors = true
       vim.cmd.colorscheme("shadow")
   end
}
```

## Supported Plugins

- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- [oil.nvim](https://github.com/stevearc/oil.nvim)
- [dressing.nvim](https://github.com/stevearc/dressing.nvim)
- [nvim-tree.lua](https://github.com/nvim-tree/nvim-tree.lua)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
