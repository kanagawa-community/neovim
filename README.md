<p align="left">
  <img src="kanagawa@2x.png" align="left" width="180" alt="Kanagawa logo">
</p>

<h3>Kanagawa for <a href="https://github.com/neovim/neovim">Neovim</a></h3>

<p>Inspired by Katsushika Hokusai's <em>The Great Wave off Kanagawa</em>.</p>
<p>
  <a href="https://www.star-history.com/?repos=kanagawa-community%2Fneovim&type=date&legend=bottom-right"><img src="https://img.shields.io/github/stars/kanagawa-community/neovim?colorA=1f1f28&colorB=7e9cd8&style=for-the-badge"></a>
  <a href="https://github.com/kanagawa-community/neovim/issues"><img src="https://img.shields.io/github/issues/kanagawa-community/neovim?colorA=1f1f28&colorB=ffa066&style=for-the-badge"></a>
  <a href="https://github.com/kanagawa-community/neovim/graphs/contributors"><img src="https://img.shields.io/github/contributors/kanagawa-community/neovim?colorA=1f1f28&colorB=98bb6c&style=for-the-badge"></a>
</p>

<p align="center">
  <h2 align="center"><img alt="Preview" src="https://user-images.githubusercontent.com/36300441/222913073-22b95f11-8c08-4b2b-867c-19072c921de1.png" width=1000></h2>
</p>

<p align="center">
  <a href="https://www.w3.org/TR/WCAG21/#contrast-minimum"><img src="https://img.shields.io/badge/WCAG_2.1_|_AA-756891?logo=w3c&logoColor=fff&style=for-the-badge"></a>
</p>

This is a community-maintained home for Kanagawa. It began as a fork of [rebelot/kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim), the original theme by [@rebelot](https://github.com/rebelot). Ports for other applications are collected in the [kanagawa-community](https://github.com/kanagawa-community) organization.

## Features

- Supports [Neovim](https://github.com/neovim/neovim/) latest
- Three variants: `wave`, `dragon` and `lotus`
- Extensive support for TreeSitter and popular plugins
- [Compiled](#compile) Lua bytecode for fast startup
- Contrast meets [WCAG 2.1 AA](#accessibility)

## Installation

with Neovim 0.12's `vim.pack`

```lua
vim.pack.add { { src = "https://github.com/kanagawa-community/neovim", name = "kanagawa" } }
```

[lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{ "kanagawa-community/neovim", name = "kanagawa", priority = 1000 }
```

[packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use { "kanagawa-community/neovim", as = "kanagawa" }
```

## Requirements

- Neovim latest
- Truecolor terminal support
- Undercurl terminal support (optional)

## Usage

```vim
colorscheme kanagawa
```

```lua
vim.cmd.colorscheme "kanagawa"
```

## Configuration

There is no need to call `setup` if the defaults work for you.

```lua
require("kanagawa").setup({
  compile = false,             -- enable compiling the colorscheme
  undercurl = true,            -- enable undercurls
  commentStyle = { italic = true },
  functionStyle = {},
  keywordStyle = { italic = true },
  statementStyle = { bold = true },
  typeStyle = {},
  transparent = false,         -- do not set background color
  dimInactive = false,         -- dim inactive window `:h hl-NormalNC`
  terminalColors = true,       -- define vim.g.terminal_color_{0,17}
  colors = {                   -- add/modify theme and palette colors
    palette = {},
    theme = { wave = {}, lotus = {}, dragon = {}, all = {} },
  },
  overrides = function(colors) -- add/modify highlights
    return {}
  end,
  theme = "wave",              -- load "wave" theme
  background = {               -- map the value of 'background' option to a theme
    dark = "wave",           -- try "dragon"!
    light = "lotus",
  },
})

-- setup must be called before loading
vim.cmd.colorscheme "kanagawa"
```

> [!NOTE]
> If you enable compilation, run `:KanagawaCompile` after every config change, then restart Neovim.

> [!NOTE]
> Kanagawa reads `'laststatus'` and `'cmdheight'`. Set them **before** calling `setup`.

## Themes

| Variant  | Description                          |
| -------- | ------------------------------------ |
| `wave`   | Default. Warm, dark.                 |
| `dragon` | Darker, for late-night sessions.     |
| `lotus`  | Light, for daytime.                  |

Switch themes in one of three ways:

- Set `theme` in `setup` to the variant you want.
- Use the `background` option. Changing `vim.o.background` picks the theme mapped in `background`.
- Load a variant directly:

  ```lua
  vim.cmd.colorscheme "kanagawa-wave"
  vim.cmd.colorscheme "kanagawa-dragon"
  vim.cmd.colorscheme "kanagawa-lotus"
  ```

  or

  ```lua
  require("kanagawa").load("wave")
  ```

## Customization

Kanagawa has two kinds of colors:

- **Palette colors** are raw RGB hex values with names that describe the color (for example `sumiInk1`).
- **Theme colors** are named by their job (for example `ui.bg` or `syn.type`).

A palette defines every available color. A theme maps palette colors to theme colors. One palette color can be used in many places.

You can change either one with `config.colors`:

```lua
require("kanagawa").setup({
  colors = {
    palette = {
      -- change all usages of these colors
      sumiInk0 = "#000000",
      fujiWhite = "#FFFFFF",
    },
    theme = {
      -- change usages for one theme, or for all of them with `all`
      wave = {
        ui = {
          float = { bg = "none" },
        },
      },
      dragon = {
        syn = { parameter = "yellow" },
      },
      all = {
        ui = { bg_gutter = "none" },
      },
    },
  } ,
})
```

Palette names are in [`lua/kanagawa/colors.lua`](lua/kanagawa/colors.lua). Theme usage is in [`lua/kanagawa/themes.lua`](lua/kanagawa/themes.lua).

### Overriding highlight groups

Use `overrides` to change any highlight group, including groups from other plugins. The values match `:h nvim_set_hl`.

```lua
require("kanagawa").setup({
  overrides = function(colors)
    return {
      -- static color
      String = { fg = colors.palette.carpYellow, italic = true },
      -- theme colors update when you switch themes
      SomePluginHl = { fg = colors.theme.syn.type, bold = true },
    }
  end,
})
```

### Common customizations

#### Remove gutter background

```lua
colors = {
  theme = {
    all = {
      ui = { bg_gutter = "none" },
    },
  },
}
```

#### Transparent floating windows

```lua
overrides = function(colors)
  local theme = colors.theme
  return {
    NormalFloat = { bg = "none" },
    FloatBorder = { bg = "none" },
    FloatTitle = { bg = "none" },
  }
end,
```

## Integration

### Get palette and theme colors

```lua
-- colors for the current theme
local colors = require("kanagawa.colors").setup()
local palette_colors = colors.palette
local theme_colors = colors.theme

-- colors for a specific theme
local wave_colors = require("kanagawa.colors").setup({ theme = "wave" })
```

### Terminal integration

Example: switch the Kitty theme when Kanagawa changes background.

```lua
vim.api.nvim_create_autocmd("ColorScheme", {
  pattern = "kanagawa",
  callback = function()
    if vim.o.background == "light" then
      vim.fn.system("kitty +kitten themes Kanagawa_light")
    elseif vim.o.background == "dark" then
      vim.fn.system("kitty +kitten themes Kanagawa_dragon")
    else
      vim.fn.system("kitty +kitten themes Kanagawa")
    end
  end,
})
```

## Compile

Kanagawa can precompute your configuration and store the result as Lua bytecode. Enable it with `compile = true` and run `:KanagawaCompile` after changes.

## Accessibility

Kanagawa keeps a `4.5:1` contrast ratio, which meets [WCAG 2.1 Level AA](https://www.w3.org/TR/WCAG21/#contrast-minimum).

## Extras

Terminal, editor and other app themes live in [`extras/`](extras/). Ports to other applications are moving into the [kanagawa-community](https://github.com/kanagawa-community) organization.

## Contributing

- Report bugs and request features in this repo's issues.
- Upstream issues are tracked here too, marked `upstream`. Please link to the original thread when you work on one.
- Pull requests are welcome. Keep the original author's commit when you merge a PR.
- For changes to palette colors, explain the reason in the PR.

## Acknowledgements

- [rebelot](https://github.com/rebelot/kanagawa.nvim) (Tommaso Laurenzi), original author
- [Tokyonight](https://github.com/folke/tokyonight.nvim)
- [Gruvbox](https://github.com/morhetz/gruvbox)
- [Catppuccin](https://github.com/catppuccin/nvim)
- [Affinity Designer](https://affinity.serif.com/designer/)

## Maintainers

- [sravioli](https://github.com/sravioli)

## License

MIT. See [LICENSE](LICENSE).
