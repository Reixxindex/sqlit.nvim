# sqlit.nvim

Neovim plugin for [sqlit](https://github.com/Maxteabag/sqlit) - a lazygit-style SQL TUI.

## Requirements

Install sqlit first:

```bash
# pipx
pipx install sqlit-tui

# uv
uv tool install sqlit-tui

# arch
yay -S sqlit
```

## Installation

### lazy.nvim

```lua
{
  "Maxteabag/sqlit.nvim",
  opts = {},
  keys = {
    { "<leader>D", function() require("sqlit").open() end, desc = "Database (sqlit)" },
  },
}
```

### Default configuration

```lua
{
  theme = "textual-ansi",  -- theme to use (textual-ansi inherits terminal colors)
  keymap = "<leader>D",    -- keymap to open sqlit (set to false to disable)
  desc = "Database (sqlit)", -- keymap description
  args = "",               -- additional CLI arguments
}
```

## Usage

- Press `<leader>D` to open sqlit in a floating terminal
- Or run `:Sqlit` command

## Terminal integration

The plugin automatically detects and uses:

1. [snacks.nvim](https://github.com/folke/snacks.nvim) terminal (if available)
2. [toggleterm.nvim](https://github.com/akinsho/toggleterm.nvim) (if available)
3. Falls back to a new tab with `:terminal`
