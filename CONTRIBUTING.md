# Contributing to Kanagawa for Neovim

Thanks for helping. This plugin follows the
[Kanagawa community contributing guide](https://github.com/kanagawa-community/.github/blob/main/.github/CONTRIBUTING.md),
which explains conventional commits, the checks every pull request runs, and how
changes are reviewed. This page covers only what is specific to this plugin.

## Where to report what

- Problems with the theme in Neovim, such as wrong colors, poor contrast, a
  missing plugin highlight, or a missing variant, belong in this repository's
  [issue tracker](https://github.com/kanagawa-community/neovim/issues).
- Problems in Neovim itself belong with the
  [Neovim project](https://github.com/neovim/neovim/issues).
- Changes to the colors themselves belong in the shared
  [palette](https://github.com/kanagawa-community/.github/blob/main/PALETTE.md),
  which is the source of truth for every port. Open an issue in the
  [.github repository](https://github.com/kanagawa-community/.github/issues) so
  every port stays in step, then update `colors.lua` and `themes.lua` here to
  match.

## Colors

Take colors from the shared palette and follow the
[style guide](https://github.com/kanagawa-community/.github/blob/main/STYLE-GUIDE.md).
Do not sample colors from screenshots or add new ones. Every change must work in
Wave, Dragon, and Lotus.

## Working on this plugin

- `lua/kanagawa/colors.lua` defines the palette colors, and
  `lua/kanagawa/themes.lua` maps them to the roles of each variant. Both follow
  the shared palette, so do not change a color value here on its own.
- `lua/kanagawa/highlights/` holds the highlight groups for the editor, syntax,
  Tree-sitter, LSP, and plugins.
- To try a change, add your checkout to the runtime path and load a variant:

  ```lua
  vim.opt.runtimepath:prepend("/path/to/neovim")
  vim.cmd.colorscheme("kanagawa-wave") -- or kanagawa-dragon, kanagawa-lotus
  ```

- `extras/` is generated from the theme. After changing colors, regenerate it
  from the plugin directory:

  ```sh
  nvim --headless "+lua require('kanagawa.extra').setup()" +qa
  ```

## Pull requests

- Keep each pull request to one change, and include a screenshot of each variant
  it affects.
- Update the README when options or usage change.
