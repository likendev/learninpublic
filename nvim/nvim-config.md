# Neovim Config

## Documentations
- vim.o = native vim config
- vim.opt = allow lua style configuration (more flexible)

## Configurations
```lua
-- always have scrolling line buffer
vim.opt.scrolloff = 8

-- Set line length marker
vim.opt.colorcolumn = "80"
```

## Keymaps
```lua
-- To move the highlighted line up and down
vim.keymap.set('v', 'J', ":m '>+1<CR>gv=gv")
vim.keymap.set('v', 'K', ":m '<-2<CR>gv=gv")

-- To remain cursor on beginning when removing linebreak
vim.keymap.set('n', 'J', 'mzJ`z')

-- Allow search term to stay in the middle
vim.keymap.set('n', 'n', 'nzzzv')
vim.keymap.set('n', 'N', 'Nzzzv')

-- Paste without losing buffer
vim.keymap.set('x', '<leader>p', '\"_dP')

```
