# Changelog

## [0.1.2](https://github.com/kanagawa-community/neovim/compare/0.1.1..0.1.2) - 2026-11-08

### Bug Fixes

- (**extra**) use each variant's ui colors in the tmTheme globals (#210) - ([94f4411](https://github.com/kanagawa-community/neovim/commit/94f441129a66186b60e9061627010284e1de0f19)) - [@sravioli](https://github.com/sravioli)
- (**extra**) use each variant's ui colors in the tmTheme globals - ([88c8396](https://github.com/kanagawa-community/neovim/commit/88c839600a1f0c4f73670f2fff9d4f2f280ad5c6)) - [@sravioli](https://github.com/sravioli)

### Documentation

- point the tmTheme extra at the bat port (#211) - ([7e8cec2](https://github.com/kanagawa-community/neovim/commit/7e8cec2217da0e220f780e0cebb2a828e794c0c5)) - [@sravioli](https://github.com/sravioli)
- point the tmTheme extra at the bat port - ([e783819](https://github.com/kanagawa-community/neovim/commit/e7838199d98b606b07d648e11a023af88ae8ee5f)) - [@sravioli](https://github.com/sravioli)
- update links to the moved shared docs (#207) - ([51b6def](https://github.com/kanagawa-community/neovim/commit/51b6def41bc2544ee92104ec82294f70544996c7)) - [@sravioli](https://github.com/sravioli)
- update links to the moved shared docs - ([f0ce4e1](https://github.com/kanagawa-community/neovim/commit/f0ce4e1d4ea3f549083d2c96f8766f124a23d57c)) - [@sravioli](https://github.com/sravioli)
- name the shared palette as the source of truth for colors (#206) - ([22ae82b](https://github.com/kanagawa-community/neovim/commit/22ae82b37711061efae07202310a9436560ace7b)) - [@sravioli](https://github.com/sravioli)
- reword the color palette section - ([ce05a31](https://github.com/kanagawa-community/neovim/commit/ce05a31bd546b5038bc408926690e93e79fd46cf)) - [@sravioli](https://github.com/sravioli)
- name the shared palette as the source of truth for colors - ([18074f2](https://github.com/kanagawa-community/neovim/commit/18074f2e793be1e66540bfdfe9eb492bc5cc0e6d)) - [@sravioli](https://github.com/sravioli)
- use the shared palette and add a contributing guide (#205) - ([a917608](https://github.com/kanagawa-community/neovim/commit/a917608e85ad12b6b5a33e6f4ddf440c23f25cd7)) - [@sravioli](https://github.com/sravioli)
- use the shared palette and add a contributing guide - ([de79ab8](https://github.com/kanagawa-community/neovim/commit/de79ab8e28a366310e5a54030eae49d2a778548c)) - [@sravioli](https://github.com/sravioli)

### Continuous Integration

- publish a release when its changelog pull request merges (#208) - ([8042813](https://github.com/kanagawa-community/neovim/commit/804281390e9c29abf00854eb9e6daf430220f1b7)) - [@sravioli](https://github.com/sravioli)
- publish a release when its changelog pull request merges - ([dcca953](https://github.com/kanagawa-community/neovim/commit/dcca9535af87fd265ed18cc34ed7de70fb5805b1)) - [@sravioli](https://github.com/sravioli)

### Refactoring

- remove the fish extra (#209) - ([a21b099](https://github.com/kanagawa-community/neovim/commit/a21b099e861400d59db189aed2f96f880393396b)) - [@sravioli](https://github.com/sravioli)
- remove the fish extra - ([8593f65](https://github.com/kanagawa-community/neovim/commit/8593f65910d1fdba437588e4c222c5208f24684f)) - [@sravioli](https://github.com/sravioli)

---

## [0.1.1](https://github.com/kanagawa-community/neovim/compare/0.1.0..0.1.1) - 2026-11-06

### Bug Fixes

- (**ci**) skip the release when HEAD is already tagged (#204) - ([46c5522](https://github.com/kanagawa-community/neovim/commit/46c552239b3da446e2a118fdbd84fe204c6a2dcd)) - [@sravioli](https://github.com/sravioli)
- (**ci**) skip the release when HEAD is already tagged - ([32f7fc3](https://github.com/kanagawa-community/neovim/commit/32f7fc3d7e11c2aa0b187c788ca5a0ca676ef7ab)) - [@sravioli](https://github.com/sravioli)

---

## [0.1.0](https://github.com/kanagawa-community/neovim/compare/38b31217f65245c4b8de86186332b0d7c91b32b1..0.1.0) - 2026-11-06

### Features

- (**CurSearch**) define CurSearch explicitly - ([53da2e8](https://github.com/kanagawa-community/neovim/commit/53da2e86a691435c0f1e56d6c01a425a776f8337)) - Tommaso Laurenzi
- (**HSLuvColor**) improvements to color manipulation - ([bf13f1b](https://github.com/kanagawa-community/neovim/commit/bf13f1bb92f80dd3774d943ef43fd80520c1098b)) - Tommaso Laurenzi
- (**TS**) add @text.diff.{add,delete} groups; fix #135 - ([a0c9e7c](https://github.com/kanagawa-community/neovim/commit/a0c9e7c7aab4a139196ec00e77787b0c8c3e2be4)) - Tommaso Laurenzi
- (**TSError**) remove TSError highlight - ([3691690](https://github.com/kanagawa-community/neovim/commit/3691690fe529918fc365a17cec250472ec544803)) - Tommaso Laurenzi
- (**cmdheight**) improve MsgSeparator on cmdheight=0 - ([899f2c9](https://github.com/kanagawa-community/neovim/commit/899f2c9311b35d9d05ca856411815a92407618fd)) - Tommaso Laurenzi
- (**cmp**) add Cmp highlights to be used in custom winhighlight - ([acf0f5d](https://github.com/kanagawa-community/neovim/commit/acf0f5d61236b416c804d649cd76db8390de9ae6)) - Tommaso Laurenzi
- (**compile**) make compile opt-in instead of opt-out - ([9025e02](https://github.com/kanagawa-community/neovim/commit/9025e022a9491bdf7f2c6485d431b03f9c1d0cc3)) - Tommaso Laurenzi
- (**compile**) opt-out of compilation; fix #106 - ([faeef98](https://github.com/kanagawa-community/neovim/commit/faeef985abd6f32cdc2e3c2cce89469060b9c74a)) - Tommaso Laurenzi
- (**compile**) compile all themes at once; refactor: add golbal _CURRENT_THEME - ([ffb2feb](https://github.com/kanagawa-community/neovim/commit/ffb2feb4ca5e117a0f0183b595f51d2e88245e36)) - Tommaso Laurenzi
- (**compile**) add compilation support - ([4bd81cd](https://github.com/kanagawa-community/neovim/commit/4bd81cd210c7a6cd7b6ccd8f471099d2d3d181f1)) - Tommaso Laurenzi
- (**config**) choose the theme for override colors - ([6d611cf](https://github.com/kanagawa-community/neovim/commit/6d611cfe97361843b46382367be0f699985a813e)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) (**config**) remove lesser options. + remove punct2; + special constructor for lua - ([f785b97](https://github.com/kanagawa-community/neovim/commit/f785b972320eeb14ef249db965a8924e7012a411)) - Tommaso Laurenzi
- (**config**) add dimInactive config key (bool) to darken the non-current - ([6b2b374](https://github.com/kanagawa-community/neovim/commit/6b2b37466c9702700aa47a364711222ddfabf6aa)) - Tommaso Laurenzi
- (**dap-ui**) add support for dap-ui - ([70d3139](https://github.com/kanagawa-community/neovim/commit/70d3139aaa8e59f3304ca7860e35fd6081b6caa5)) - Tommaso Laurenzi
- (**dragon**) improve dragon theme (still WIP) - ([f4286e1](https://github.com/kanagawa-community/neovim/commit/f4286e1cd5b6777518edf894b36848fc5c9f97f8)) - Tommaso Laurenzi
- (**editor**) highlight MsgArea depending on value of 'cmdheight' - ([7cede0a](https://github.com/kanagawa-community/neovim/commit/7cede0a885616bf5bd609e092f8ae0cc50cc7d25)) - Tommaso Laurenzi
- (**extras**) add alacritty kanagawa lotus theme - ([869b157](https://github.com/kanagawa-community/neovim/commit/869b1571b42432f3d34d5af10d99985e1766a407)) - Fadhil Muhammad
- (**extras**) add tmTheme auto generation - ([a6bd498](https://github.com/kanagawa-community/neovim/commit/a6bd498e97209a1b1edff554196b6396cec6960d)) - Vitaly
- (**extras**) add kanagawa_light.itermcolors - ([7815b34](https://github.com/kanagawa-community/neovim/commit/7815b342520eaec10100799be6242a02325c7fde)) - Levi
- (**extras**) add lotus and dragon flavors for foot - ([6f3cb79](https://github.com/kanagawa-community/neovim/commit/6f3cb7984187b01f92458d56834a60501bcb1a1c)) - dexzh
- (**extras**) update Alacritty color schemes - ([58876e3](https://github.com/kanagawa-community/neovim/commit/58876e397f1e4a96a99d89c3da36b5f6e73e77c4)) - S1M0N38
- (**extras**) Update alacritty themes - ([d685d3b](https://github.com/kanagawa-community/neovim/commit/d685d3b421b4a01eae4446059baa13dc5c97c562)) - hasecilu
- (**extras**) add kanagawa.tmTheme - ([7b411f9](https://github.com/kanagawa-community/neovim/commit/7b411f9e66c6f4f6bd9771f3e5affdc468bcbbd2)) - Vitaliy Kogogin
- (**extras**) improve tab foreground in kitty theme - ([c8af52c](https://github.com/kanagawa-community/neovim/commit/c8af52c95022f80931b8c042538db6c10e0245ec)) - Tommaso Laurenzi
- (**extras**) add Kanagawa_light kitty theme - ([04b8d49](https://github.com/kanagawa-community/neovim/commit/04b8d49c53996a453ddb3b5d00940f51ccc3dbbe)) - Tommaso Laurenzi
- (**extui**) add MsgSeparator fg color - ([27f1e11](https://github.com/kanagawa-community/neovim/commit/27f1e119f3a7e6d11d435a59e3262e6affda1f83)) - Tommaso Laurenzi
- (**highlights**) add FloatFooter hl - ([0a24e50](https://github.com/kanagawa-community/neovim/commit/0a24e504a3a278849ad0aef31cd6dd24c73ca3db)) - Tommaso Laurenzi
- (**highlights-plugins**) add Neogit; fix #139 - ([89d5ec4](https://github.com/kanagawa-community/neovim/commit/89d5ec496d371bfda5722612d33fd61d6b858279)) - Tommaso Laurenzi
- (**hl**) add cmpItemKindCopilot hl - ([f20c407](https://github.com/kanagawa-community/neovim/commit/f20c4074cc4e9504139d95f5311089036f0ec178)) - Tommaso Laurenzi
- (**hlgroups**) add FloatTitle hlgroup - ([d6145ea](https://github.com/kanagawa-community/neovim/commit/d6145eab30d77e304870f77d95d4992f22745553)) - Tommaso Laurenzi
- (**hlgroups**) improve highlights - ([50e7b43](https://github.com/kanagawa-community/neovim/commit/50e7b43552072696d26757aff5f6307e2ab5e3ea)) - Tommaso Laurenzi
- (**hlgroups**) better telescope doc/ws symbols - ([582df5b](https://github.com/kanagawa-community/neovim/commit/582df5b4f806c93cdc94b1df8234f56a30bba48a)) - Tommaso Laurenzi
- (**hlgroups**) remove default link filed when overriding hlgroups - ([6913a25](https://github.com/kanagawa-community/neovim/commit/6913a25c53917e6c610a976b1258ddea7bfb8431)) - Tommaso Laurenzi
- (**hlgroups**) improve nvim-cmp Variable highlight - ([00b44c5](https://github.com/kanagawa-community/neovim/commit/00b44c5c583337d709ed6aeb4c54dd3abfef2e2a)) - Tommaso Laurenzi
- (**hsl**) add color manipulation module - ([fdbfaa9](https://github.com/kanagawa-community/neovim/commit/fdbfaa942a367e5e3b333200da4f9d16c316a963)) - Tommaso Laurenzi
- (**hsluv**) switch to hsluv submodule and improve light theme - ([095a2cb](https://github.com/kanagawa-community/neovim/commit/095a2cb37a51b7f9d8b6e4763d78e4ae19f646b5)) - Tommaso Laurenzi
- (**kitty**) improve kitty (dark) theme - ([f3c1bb8](https://github.com/kanagawa-community/neovim/commit/f3c1bb8b6f67b26a2d39babf86d0807c4004c28e)) - Tommaso Laurenzi
- (**light_theme**) WIP first iteration of light theme - ([fa1c3c4](https://github.com/kanagawa-community/neovim/commit/fa1c3c4b01f526bf4deff33dd223b16289967911)) - Tommaso Laurenzi
- (**lsp**) add some missing types - ([bfba3e2](https://github.com/kanagawa-community/neovim/commit/bfba3e28faf3a9c1e9c887f191670d2cff321406)) - Tommaso Laurenzi
- (**lsp**) add some highlights for @lsp.typemod.*.injected - ([db50dd0](https://github.com/kanagawa-community/neovim/commit/db50dd0eae13a45b2dc5d7fc07e0cf53a801b08f)) - Tommaso Laurenzi
- (**lsp**) add typemod.function.readonly.javascript; fix #144 - ([6e89801](https://github.com/kanagawa-community/neovim/commit/6e898011e90e7c62a78889c0b3dfe6df54cc5c2d)) - Tommaso Laurenzi
- (**luap**) regex highlights for lua patterns - ([d0613a6](https://github.com/kanagawa-community/neovim/commit/d0613a6e6df5fa379e6e443755e292b6d89465a4)) - Tommaso Laurenzi
- (**markdown**) better markdown hl - ([0ad738e](https://github.com/kanagawa-community/neovim/commit/0ad738e7cc43514d35388c1caca13990d688aa5c)) - Tommaso Laurenzi
- (**neogit**) define neogit highlights; fix #63 - ([6ee9684](https://github.com/kanagawa-community/neovim/commit/6ee96842cbfe3b7ebf7a1c3fa9602c2a3f5fdf38)) - Tommaso Laurenzi
- (**notify**) improve nvim-notify highlights - ([a6f8ea1](https://github.com/kanagawa-community/neovim/commit/a6f8ea10900e8d891f9c93e0ed258f118010fb24)) - Tommaso Laurenzi
- (**notify**) add support for nvim-notify - ([1c36cda](https://github.com/kanagawa-community/neovim/commit/1c36cda43a90baef5028957f8c8a3def0c55b460)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) (**overhaul**) new features and improvements - ([d146b7e](https://github.com/kanagawa-community/neovim/commit/d146b7e32fa6049025cb808ff8f7c4718b0d4fcd)) - Tommaso Laurenzi
- (**palette**) add all colors - ([72775d9](https://github.com/kanagawa-community/neovim/commit/72775d9d1c55f57ae1cd06a397923a5f35041e94)) - Tommaso Laurenzi
- (**palette**) add bg_shades (default scheme) - ([fc2e308](https://github.com/kanagawa-community/neovim/commit/fc2e30820c73b0cf56bb0fb9e4a83dd8b90f9bf4)) - Tommaso Laurenzi
- (**plugins**) add SnacksProfiler and SnacksNotifier - ([6d2899c](https://github.com/kanagawa-community/neovim/commit/6d2899cccde7173673d38c8cc732e1438a7eb900)) - MatheusTT
- (**plugins**) snacks.nvim - ([46ef584](https://github.com/kanagawa-community/neovim/commit/46ef5842fe159a7d0ebce0e40807c0d247906ca2)) - MatheusTT
- (**plugins**) rainbow delimiters - ([8d85d0c](https://github.com/kanagawa-community/neovim/commit/8d85d0cf84345d4fa873a78f60b748705bfc3473)) - Aliaksandr Truš
- (**plugins**) mini.nvim - ([3ad4ea2](https://github.com/kanagawa-community/neovim/commit/3ad4ea25ff4202831d12712a570031fc200db94f)) - Evgeni Chasnovski
- (**plugins**) Trouble v3 - ([860e4f8](https://github.com/kanagawa-community/neovim/commit/860e4f80df71221d18bf2cd9ef1deb4d364274d2)) - Tommaso Laurenzi
- (**plugins**) add Aerial%KIND%Icon colors; consistent LSP kind colors for Cmp, Navic and Aerial - ([23ae977](https://github.com/kanagawa-community/neovim/commit/23ae977e5a46dbf976d051ad2b57f5ed789871d8)) - Tommaso Laurenzi
- (**plugins**) add Indent blankline v3 - ([d8552ee](https://github.com/kanagawa-community/neovim/commit/d8552ee27c777055ed38ea49277aa271214d45e9)) - WieeRd
- (**plugins**) add TreesitterContextLineNumber - ([129e817](https://github.com/kanagawa-community/neovim/commit/129e817c65a63b6d1f328670355b6780a2d4f36a)) - Tommaso Laurenzi
- (**plugins**) add NeoTreeIndentMarker - ([9cc07c5](https://github.com/kanagawa-community/neovim/commit/9cc07c5a98b2f14dc80a9f464334107cc4b6b497)) - Tommaso Laurenzi
- (**plugins**) add NeoTreeTabSeparator - ([6059509](https://github.com/kanagawa-community/neovim/commit/6059509ca8467dd2068a04bb0b286887e236685e)) - Tommaso Laurenzi
- (**plugins**) initial support for NeoTree - ([423370a](https://github.com/kanagawa-community/neovim/commit/423370ab6f94df48bcfb9090a6733b6e82b9beb0)) - Tommaso Laurenzi
- (**plugins**) hl for NvimTree window picker - ([00f4307](https://github.com/kanagawa-community/neovim/commit/00f4307d9eda1393cd32fc033fa720b0843eea87)) - Tommaso Laurenzi
- (**plugins**) better dashboard support - ([17a084f](https://github.com/kanagawa-community/neovim/commit/17a084fc27d7a908fef779dea6890fe9a8d0510d)) - Tommaso Laurenzi
- (**plugins**) add explicit background for nvim-notify - ([545c9a6](https://github.com/kanagawa-community/neovim/commit/545c9a6e8c34680c9d376d025e9c5afeeefa7d20)) - Tommaso Laurenzi
- (**plugins**) improve telescope and lazy - ([5ae029a](https://github.com/kanagawa-community/neovim/commit/5ae029a2aa291a757332897b75df27c26aa38241)) - Tommaso Laurenzi
- (**plugins-Telescope**) better selection and caret highlights - ([66aeaf7](https://github.com/kanagawa-community/neovim/commit/66aeaf7573253a847a02d56218b0d7f6cea7609e)) - Tommaso Laurenzi
- (**pumborder**) link pumborder to floatborder - ([aef7f5c](https://github.com/kanagawa-community/neovim/commit/aef7f5cec0a40dbe7f3304214850c472e2264b10)) - Tommaso Laurenzi
- (**readme**) add screenshot - ([718ea31](https://github.com/kanagawa-community/neovim/commit/718ea31b8b6a92b99f25c817ac150b44b45f857f)) - Tommaso Laurenzi
- (**semantic_highlights**) add "injected" groups - ([554a63e](https://github.com/kanagawa-community/neovim/commit/554a63e9649af5d1cbedcf5e81d912d4612e466b)) - mrtnvgr
- (**semantic_highlights**) add initial support for semantic tokens highlights - ([5781565](https://github.com/kanagawa-community/neovim/commit/57815655d7f7bc0b78c8a5b45de38db28aabfd58)) - Tommaso Laurenzi
- (**sway**) tidy up formatting - ([c200345](https://github.com/kanagawa-community/neovim/commit/c2003451a72d95f8a0f8a6addbc04d61219f9d44)) - Sam Boysel
- (**sway**) add config for Sway WM colors - ([0041c7e](https://github.com/kanagawa-community/neovim/commit/0041c7ea4e6dd0f39562a4902d93c864b44d4120)) - Sam Boysel
- (**tabline**) better TabLineSel background - ([cff7a76](https://github.com/kanagawa-community/neovim/commit/cff7a762dbaf9bc6aa5f9c1350362fe49f4263c4)) - Tommaso Laurenzi
- (**terminal**) added kanagawa themes for ghostty - ([2d9ae00](https://github.com/kanagawa-community/neovim/commit/2d9ae006b3b20a156e5eda23aaa65dc49deba10f)) - Ouassim Abdelmalek Ghribi
- (**terminal**) add kanagawa dragon alacritty theme - ([0e8ac7e](https://github.com/kanagawa-community/neovim/commit/0e8ac7ea8c4a8a4b1191b629f04c754fb356ff33)) - Nikhil
- (**terminal**) improve terminal colors, add kanagawa_dragon kitty theme - ([181e322](https://github.com/kanagawa-community/neovim/commit/181e3223512799d7248c70fa7249ab58a33d9906)) - Tommaso Laurenzi
- (**terminal_colors**) add vim.g.terminal_colors_{0,17}. fix #59 - ([04e868d](https://github.com/kanagawa-community/neovim/commit/04e868dc377fa6aef5da50d9816a43272896a863)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) (**themes**) rename themes, allow default (wave) to be set explicitly via :colo - ([1928e9c](https://github.com/kanagawa-community/neovim/commit/1928e9cbca28d9d6342c52a24d1242af8dd3cf2d)) - Tommaso Laurenzi
- (**themes**) add WIP Dragon Theme. Ejoy. _/º`&lt;~*~ - ([dda1b8c](https://github.com/kanagawa-community/neovim/commit/dda1b8c13e0e7588c014064e5e8baf7f2953dd29)) - Tommaso Laurenzi
- (**todo-comments**) better TS highlights for todo/warning/danger comments - ([6668ad6](https://github.com/kanagawa-community/neovim/commit/6668ad6e092e03e8d3f8b3a3184e05413df02247)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) (**tree-sitter**) use captures as hl-group names - ([631e0aa](https://github.com/kanagawa-community/neovim/commit/631e0aa4012924d1874ced20f9ed5c7175a5a94c)) - Tommaso Laurenzi
- (**treesitter**) better support for markup (latex) - ([497a5ea](https://github.com/kanagawa-community/neovim/commit/497a5eadf76bc57ab0d80d50a87ecc0e7535d72d)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) (**treesitter/lsp**) update to latest TS capture names - ([75be2b9](https://github.com/kanagawa-community/neovim/commit/75be2b90c135a6cdacf05826aeb44dcf0c95df3c)) - Tommaso Laurenzi
- (**ts**) improve ts captures highlights - ([fc414f7](https://github.com/kanagawa-community/neovim/commit/fc414f798f0bc0231dd8e7e01364e0524fb3c06e)) - Tommaso Laurenzi
- (**vim.o.background**) allow setting default/light theme via background option (this overrides config). - ([1b46ae8](https://github.com/kanagawa-community/neovim/commit/1b46ae8520667fbb46b35618d84beb6dfcf23b75)) - Tommaso Laurenzi
- (**winbar**) add winbar and winbarnc hl groups - ([97b96c6](https://github.com/kanagawa-community/neovim/commit/97b96c6d740161cb624ee8eae466b1e35782540e)) - Tommaso Laurenzi
- (**winseparator**) use darker color - ([40370df](https://github.com/kanagawa-community/neovim/commit/40370dfa8529e550f9588196e2e35a5bf93c6183)) - Tommaso Laurenzi
- add fzf-lua hightligh - ([530cfd3](https://github.com/kanagawa-community/neovim/commit/530cfd31c8b7d9b45076e7a5d133210d911ff6be)) - Aliaksandr Truš
- add zathura theme - ([1a9a505](https://github.com/kanagawa-community/neovim/commit/1a9a5058f3698413aef41a7c2d274d4e1bdd5018)) - Dinesh Kumar
- link @function.macro to Macro - ([76b68aa](https://github.com/kanagawa-community/neovim/commit/76b68aaefb7d6bcfad24d9be72cd05ae547a948b)) - dexzh
- add blink.cmp hlgroups - ([5c1a078](https://github.com/kanagawa-community/neovim/commit/5c1a0784b6a467457d85082d87445e9a888f4f15)) - Jonas Schneider
- add wezterm dragon config - ([9fa4052](https://github.com/kanagawa-community/neovim/commit/9fa4052454c699f7ca210fe431dd3e29d9c671f5)) - ramonvermeulen
- adds highlight group overrides for Neotest - ([73717ab](https://github.com/kanagawa-community/neovim/commit/73717ab0068ca51ea983e20ff80e8cd9a4ed3d91)) - Joshua Tye
- lightmode for windows_terminal.json - ([3d305cb](https://github.com/kanagawa-community/neovim/commit/3d305cb47de1ce9a7e99edb04295a4eb7f2171d1)) - Jacob Nguyen
- Alfred theme - ([b4df5ad](https://github.com/kanagawa-community/neovim/commit/b4df5ad19388b1709f87986aadae781ae3563f0a)) - Mitchell Hanberg
- add in support for Note - ([66f00dd](https://github.com/kanagawa-community/neovim/commit/66f00dd38fd7de738068942295c78acd9ce67ba7)) - Chris Kipp
- advertize themes to vim as separate colorschemes - ([bca5195](https://github.com/kanagawa-community/neovim/commit/bca5195db85c6f1b0a89eeca575eb61bfa151b41)) - Tommaso Laurenzi
- add color palette to readme - ([7118690](https://github.com/kanagawa-community/neovim/commit/7118690e5a0415407d9d0438a128365a73837282)) - Tommaso Laurenzi

### Bug Fixes

- (**Normal**) set Normal hl using vim.cmd; fix #52 - ([c0d318c](https://github.com/kanagawa-community/neovim/commit/c0d318c3c205e3d2e0dbe67dcd08106ebb1d0452)) - Tommaso Laurenzi
- (**TS**) text.diff.{add,delete} use vcs added/removed instead of diff hl - ([52ec9e6](https://github.com/kanagawa-community/neovim/commit/52ec9e690735f541b7b4d635605e0c0b1e045750)) - Tommaso Laurenzi
- (**TSVariable**) explicitly assing fg color - ([a6db779](https://github.com/kanagawa-community/neovim/commit/a6db77965a27ca893ea693d69cc3c152c000a627)) - Tommaso Laurenzi
- (**TSVariable**) link TSVariable to Normal instead of clearing - ([0673176](https://github.com/kanagawa-community/neovim/commit/067317613192a7a4f1b3455e5b69438ee504c013)) - Tommaso Laurenzi
- (**annotations**) fix background option annotation - ([a7db9f1](https://github.com/kanagawa-community/neovim/commit/a7db9f1794635332f2e74e85f0403953fc567efb)) - Tommaso Laurenzi
- (**background**) fix checking for explicit bg option - ([c387dd7](https://github.com/kanagawa-community/neovim/commit/c387dd78834fcd821cf85e57720be2ce6da1e815)) - Tommaso Laurenzi
- (**ci**) skip releases without a baseline tag and fail on cog errors - ([325f765](https://github.com/kanagawa-community/neovim/commit/325f765b7211dad9a9d88660dbc3c9a859927c38)) - [@sravioli](https://github.com/sravioli)
- (**command**) call load directly - ([246ac28](https://github.com/kanagawa-community/neovim/commit/246ac283e9cc90fa49bd4736144c1977ac0a9ee6)) - Tommaso Laurenzi
- (**compile**) also compile terminal colors - ([10527da](https://github.com/kanagawa-community/neovim/commit/10527dafc57c412a75a13d45325bc1ec6d5d0970)) - Tommaso Laurenzi
- (**compile**) compile to own directory - ([bd157a1](https://github.com/kanagawa-community/neovim/commit/bd157a17172b21f4292405e33583b32569962584)) - Tommaso Laurenzi
- (**compile-command**) trigger ColorScheme autocmd on compilation - ([ef1882b](https://github.com/kanagawa-community/neovim/commit/ef1882b21c84b4ccb1bd55cad7a38b7362ef2d18)) - Tommaso Laurenzi
- (**completion-menu**) remove foreground from PmenuSel (better integration with cmp) - ([c75b980](https://github.com/kanagawa-community/neovim/commit/c75b980bdd4ce97421071d81292f24ccdb39af6d)) - Tommaso Laurenzi
- (**config**) fix wrong error thrown if `theme` is set - ([d12d8fd](https://github.com/kanagawa-community/neovim/commit/d12d8fd5202ea69ec4e80b387439a59ae042e921)) - Tommaso Laurenzi
- (**config**) remove unused option - ([3b40289](https://github.com/kanagawa-community/neovim/commit/3b4028972651a156fa5b1c5daf608ba25c7e8aad)) - Tommaso Laurenzi
- (**dapui**) use explicit colors instead of links - ([fb733c1](https://github.com/kanagawa-community/neovim/commit/fb733c1043a462155b52cd97efd920f1dd72d33a)) - Tommaso Laurenzi
- (**extras**) typo - ([a6707c0](https://github.com/kanagawa-community/neovim/commit/a6707c04d8eedcaf5f47598af9ba37d23ff7623c)) - leviosa42
- (**extras**) move itermcolors file to correct location in 'extras' - ([45aeba8](https://github.com/kanagawa-community/neovim/commit/45aeba827e4976adacda22ccbb29469e357338c4)) - Levi
- (**extras**) rename [colors] to [colors-dark] for foot terminal - ([ab56921](https://github.com/kanagawa-community/neovim/commit/ab569219cfc8fad16539b4ec4d3007acdeb53406)) - dexzh
- (**extras**) revert broken suckless extension - ([002b624](https://github.com/kanagawa-community/neovim/commit/002b624d77b0a2f82005a82976a50cde637f8ad1)) - Tommaso Laurenzi
- (**extras**) fix bg of dragon kitty theme - ([bd27c98](https://github.com/kanagawa-community/neovim/commit/bd27c9835dad727f77c80f5c035f3b297b4f1e6a)) - Tommaso Laurenzi
- (**highlights**) fix nvimtree bg - ([4357138](https://github.com/kanagawa-community/neovim/commit/43571385fbe0b2006c1a2d7b5172154a822fa6b3)) - Tommaso Laurenzi
- (**highlights-plugins**) fix some CmpItemKind* referencing old TS highlights - ([48c5517](https://github.com/kanagawa-community/neovim/commit/48c5517c6e5854e9fad1b9359512996cabbfe481)) - Tommaso Laurenzi
- (**hlgroups**) symbol - ([01e88f9](https://github.com/kanagawa-community/neovim/commit/01e88f9e8af12c9bca069b12b66f17435b7fd099)) - Otávio Schwanck dos Santos
- (**hlgroups**) tag attribute color - ([131e665](https://github.com/kanagawa-community/neovim/commit/131e6652390ad649d13470ec488e6ec89f577ec5)) - Otávio Schwanck dos Santos
- (**hlgroups**) remove occurrences of color palette names - ([6852365](https://github.com/kanagawa-community/neovim/commit/68523659235d49ab407a33eb3539783ea1b1a2bf)) - Tommaso Laurenzi
- (**hlgroups**) use vim.tbl_extend to apply config styles - ([e5d940f](https://github.com/kanagawa-community/neovim/commit/e5d940f68872b829489b88fcd201694703c75d79)) - sanka047
- (**hlgroups**) set TSVariable fg to none - ([6bc6740](https://github.com/kanagawa-community/neovim/commit/6bc6740d62176bbc23be49484b909ab6f899a429)) - Tommaso Laurenzi
- (**hlgroups**) link NvimTreeNormal{,NC} to Normal{,NC} - ([4b454c1](https://github.com/kanagawa-community/neovim/commit/4b454c1d261ee1ba89d60d3ab87c4ccd4e1714fe)) - Tommaso Laurenzi
- (**hlgroups**) remove useless bg; fix #16 - ([e8a67ee](https://github.com/kanagawa-community/neovim/commit/e8a67ee2476f5d63c407eb957609e35881e0130f)) - Tommaso Laurenzi
- (**hlgroups**) fix sign/foldcolumn transparency #16 - ([fe85fe2](https://github.com/kanagawa-community/neovim/commit/fe85fe2456482ae902acac565c1b19937ef4d227)) - Tommaso Laurenzi
- (**hlgroups**) fix #14 wrong color name reference - ([48edfc7](https://github.com/kanagawa-community/neovim/commit/48edfc76cdeb6499d78ed4736eda19c5fb69c1ea)) - Tommaso Laurenzi
- (**hsluvcolor**) guard against 'NONE' colors - ([8e9ef29](https://github.com/kanagawa-community/neovim/commit/8e9ef295bf4116573887e9681ec06baa1550d1bc)) - Tommaso Laurenzi
- (**lsp**) link @lsp.type.comment semantic token to Comment hlgroup - ([229b927](https://github.com/kanagawa-community/neovim/commit/229b927acaa79f9a76c129952022c21f720e44e8)) - Tomas Gareau
- (**lsp**) explicit link @lsp.type.macro to Macro; fix #242 - ([54e7382](https://github.com/kanagawa-community/neovim/commit/54e738244128b10c286ab6b7cfa949b81b43e17e)) - Tommaso Laurenzi
- (**lsp**) extend typemod.function.readonly to all languages; fix #144 - ([963824e](https://github.com/kanagawa-community/neovim/commit/963824e979f33bf2b39838d9ea7a59467d34ec9b)) - Tommaso Laurenzi
- (**lsp**) remove lsp.type.comment hl - ([09a050b](https://github.com/kanagawa-community/neovim/commit/09a050be9b2eaec71bd1abf593343d2f8895b27f)) - Tommaso Laurenzi
- (**lualine**) Shall it be boatYellow2; fix #125 - ([d8800c3](https://github.com/kanagawa-community/neovim/commit/d8800c36a7f3bcec953288926b00381c028ed97f)) - Tommaso Laurenzi
- (**lualine**) visual used to be violet; fix #105 - ([ebc6013](https://github.com/kanagawa-community/neovim/commit/ebc6013af68f70b5999727d1a2e4395b29ea4735)) - Tommaso Laurenzi
- (**lualine**) fix lualine integration - ([1789033](https://github.com/kanagawa-community/neovim/commit/1789033803c32464c3eaf8c062f2d65ea236aa1d)) - Tommaso Laurenzi
- (**lualine**) fix lualine integration - ([5173878](https://github.com/kanagawa-community/neovim/commit/5173878eb6bea1bc50f01e143fc08db3c022cf6a)) - Tommaso Laurenzi
- (**methods**) remove specialized method theme color - ([207ebd2](https://github.com/kanagawa-community/neovim/commit/207ebd2c0ef953b559b5084e08b1d67bfec0da4e)) - Tommaso Laurenzi
- (**nvimtree**) link NvimTreeNormal to Normal; fix #103 - ([6b5df41](https://github.com/kanagawa-community/neovim/commit/6b5df4199b50e8324fe3141e98212bcfd99d09c6)) - Tommaso Laurenzi
- (**plugins**) add missing neogit highlights; fix #139 - ([172d858](https://github.com/kanagawa-community/neovim/commit/172d858162c4fdeca9cb2cab56eb4b8237af5df1)) - Tommaso Laurenzi
- (**plugins**) NeoTreeRootName remove italic - ([9d9733c](https://github.com/kanagawa-community/neovim/commit/9d9733ca8ec0c7f413df80fd7f55e802a9c2f8d7)) - Tommaso Laurenzi
- (**presets**) fix telescope preset - ([fde88c7](https://github.com/kanagawa-community/neovim/commit/fde88c7a86d2724276be35c4366722c773e9ba08)) - Tommaso Laurenzi
- (**readme**) add FloatTitle to transparent floats example - ([3c87bfa](https://github.com/kanagawa-community/neovim/commit/3c87bfacd5f51033bbeeb04f837c88f94861f6af)) - Tommaso Laurenzi
- (**readme**) fix typo - ([d0d7ada](https://github.com/kanagawa-community/neovim/commit/d0d7adac9835be022d4387199ebba4a27dbd9a9f)) - Tommaso Laurenzi
- (**themes**) fix theme names in colors.vim - ([4834f7c](https://github.com/kanagawa-community/neovim/commit/4834f7cf1063ce894c92c3c5db3d82f01f0d2db4)) - Tommaso Laurenzi
- (**transparency**) adapt FloatBorder background to transparency setting - ([cf19569](https://github.com/kanagawa-community/neovim/commit/cf19569cf02950932a660c164db974a592568ea2)) - Tommaso Laurenzi
- (**tree-sitter**) update descriptions, add markup.link (fix #225) - ([8ed74ad](https://github.com/kanagawa-community/neovim/commit/8ed74ada47d3138385c1a3df2b257c9a1f6182d0)) - Tommaso Laurenzi
- (**ts**) link @text.literal to String - ([6f692e3](https://github.com/kanagawa-community/neovim/commit/6f692e38ef2852ac146124ff9bcd28b8d8c1b1de)) - Tommaso Laurenzi
- (**winbar**) fix case Winbar* -> WinBar* - ([feab306](https://github.com/kanagawa-community/neovim/commit/feab3061e620d5656e25ba187e748a92e43ad580)) - Tommaso Laurenzi
- forgot link - ([a62355e](https://github.com/kanagawa-community/neovim/commit/a62355e3c4bb1b317cae3087142cfc22b2f09b5e)) - MatheusTT
- Align `g:colors_name` with the theme names in `/colors` - ([5717527](https://github.com/kanagawa-community/neovim/commit/57175273d24e8871b5a3dd5041c61a969b30ab98)) - wongxy
- correct blink.cmp completion kind highlights - ([19d9f23](https://github.com/kanagawa-community/neovim/commit/19d9f23556d264b5721e04035709acdb20599904)) - WieeRd
- sync nvim-cmp and blink.cmp highlights with pmenu - ([0f27d73](https://github.com/kanagawa-community/neovim/commit/0f27d73cb672ee48f013d56a9d297a5b338f5a83)) - WieeRd
- use EmmyLua-style code annotations - ([ed17aed](https://github.com/kanagawa-community/neovim/commit/ed17aed00a54d137e93674ffccb565012d6111d3)) - William Boman
- fallback to global config - ([2b65679](https://github.com/kanagawa-community/neovim/commit/2b656796170fbf6f8be8f0c94a02f4145c1eef0f)) - Tommaso Laurenzi
- update lualine extension for new way to get colors - ([0bea8e6](https://github.com/kanagawa-community/neovim/commit/0bea8e6d526d63b215ab51f68797ac835dcb01af)) - Tommaso Laurenzi
- make theme return a new table - ([4a3b95c](https://github.com/kanagawa-community/neovim/commit/4a3b95c92e2afc3b818141b19bb3cb32d0b90076)) - Tommaso Laurenzi
- add circles - ([d144c81](https://github.com/kanagawa-community/neovim/commit/d144c81f3428de1941f5f67247da887014393634)) - Tommaso Laurenzi
- colorcolumn highlight - ([07a540b](https://github.com/kanagawa-community/neovim/commit/07a540be01ecc91152bdbfe4785f1a02532e390d)) - Tommaso Laurenzi
- improve kitty tab contrast - ([b17eeb2](https://github.com/kanagawa-community/neovim/commit/b17eeb214febe2b7f5776da3f6de078529dfdaa4)) - Nikolay Rademacher

### Performance Improvements

- (**hlgroups**) improve borders background. - ([95462e9](https://github.com/kanagawa-community/neovim/commit/95462e91b82542a3d602bec5a2a54a35abe29728)) - Tommaso Laurenzi
- (**pmenu**) add missing popupmenu highlights - ([2f2c6cf](https://github.com/kanagawa-community/neovim/commit/2f2c6cfa9cf66d3b8b0db57a4301e8c5552215cb)) - Tommaso Laurenzi
- (**treesitter**) better hl color for @string.special.url - ([8c60549](https://github.com/kanagawa-community/neovim/commit/8c60549b8588e7dc7e9084f836b0471735d10bf6)) - Tommaso Laurenzi
- don't require color module where it is not needed - ([aa66e79](https://github.com/kanagawa-community/neovim/commit/aa66e795bf01afd13d23d3a8ec746631951bfc85)) - Tommaso Laurenzi

### Revert

- remove presets - ([d3de16c](https://github.com/kanagawa-community/neovim/commit/d3de16cba3be97ac4598f5030220adfa6120bf6f)) - Tommaso Laurenzi

### Documentation

- (**README**) adjust setup notes - ([12f07c5](https://github.com/kanagawa-community/neovim/commit/12f07c5d68ba6b09b53ab528de6df68e55b4cd9a)) - Tommaso Laurenzi
- (**README**) document theme may be changed via background option - ([5f1203f](https://github.com/kanagawa-community/neovim/commit/5f1203f4606e3208f6dd156c03f498d9fadcf1a8)) - Tommaso Laurenzi
- (**neovim**) refresh project README - ([5c0375c](https://github.com/kanagawa-community/neovim/commit/5c0375caa6eb5d060f00650de28214c6f9bc25f9)) - [@sravioli](https://github.com/sravioli)
- (**notes**) add notes about cmdheight and laststatus - ([99d9f72](https://github.com/kanagawa-community/neovim/commit/99d9f72122e92ba816c86e10ce8e97c555be99ba)) - Tommaso Laurenzi
- (**plugins**) update explicitly supported plugins list - ([52cfa27](https://github.com/kanagawa-community/neovim/commit/52cfa270317121672c1416c725361fa653684de0)) - Tommaso Laurenzi
- (**readme**) include common customizations; fix #112 - ([1934273](https://github.com/kanagawa-community/neovim/commit/193427320939d111845bd095b301d9d57e6f28f6)) - Tommaso Laurenzi
- (**readme**) update documentation for overrides - ([6a30cab](https://github.com/kanagawa-community/neovim/commit/6a30cab7b7c0184f06565e102420fc2b8ddaebdc)) - Tommaso Laurenzi
- (**themes**) example how to map 'background' to all three variants - ([ad3ddde](https://github.com/kanagawa-community/neovim/commit/ad3dddecd606746374ba4807324a08331dfca23c)) - Tommaso Laurenzi
- (**themes**) undisclose theme field option - ([40f4c4e](https://github.com/kanagawa-community/neovim/commit/40f4c4e3646b78c070a4722ff731e3b6d8f236c0)) - Tommaso Laurenzi
- state that the port derives from kanagawa.nvim (#202) - ([c3f07d2](https://github.com/kanagawa-community/neovim/commit/c3f07d2873f5391fb3fbfe1a33e57dda1126ad78)) - [@sravioli](https://github.com/sravioli)
- state that the port derives from kanagawa.nvim - ([2a8862d](https://github.com/kanagawa-community/neovim/commit/2a8862dc70439a32197c210743effc5340abdcef)) - [@sravioli](https://github.com/sravioli)
- remove bold from the variant list - ([6c69daa](https://github.com/kanagawa-community/neovim/commit/6c69daa4899667286cfbe29dcffab64b6586feef)) - [@sravioli](https://github.com/sravioli)
- shorten README attribution - ([93e7a8f](https://github.com/kanagawa-community/neovim/commit/93e7a8f08b153c1fabfa4086d0cdc2a48ef5313c)) - [@sravioli](https://github.com/sravioli)
- clarify Neovim authorship and spacing - ([5e1a964](https://github.com/kanagawa-community/neovim/commit/5e1a964f76376e7f6ad95eff5648f096e6e95db1)) - [@sravioli](https://github.com/sravioli)
- align Neovim README header - ([f62b41a](https://github.com/kanagawa-community/neovim/commit/f62b41a70d3dd12d371eeaf93ca90cacb6744d5a)) - [@sravioli](https://github.com/sravioli)
- remove hints about 'background' being unset; fix #279 - ([0cd490d](https://github.com/kanagawa-community/neovim/commit/0cd490da270ff8e627bc9edc7b6dd34ad929ae1a)) - Tommaso Laurenzi
- add example for transparent floating windows and float borders tips - ([b64c289](https://github.com/kanagawa-community/neovim/commit/b64c2897ab032f4a679f7ffe5081f15f5560b1ad)) - Tommaso Laurenzi
- fix syntax error in example configuration - ([1b30c48](https://github.com/kanagawa-community/neovim/commit/1b30c484b9d7fe3e2d7aa6618d738065920db027)) - Ryan Kuester
- update docs - ([ae189e0](https://github.com/kanagawa-community/neovim/commit/ae189e0b5b6ddb70356e301e4098ca57bf18a048)) - Tommaso Laurenzi
- update docs - ([cabb75e](https://github.com/kanagawa-community/neovim/commit/cabb75e4d54d9a99ac2b556f2c7a116d4b264538)) - Tommaso Laurenzi
- improve annotation - ([a994a63](https://github.com/kanagawa-community/neovim/commit/a994a63482175a7a7fa31fea9b0fd163d2ae69d1)) - Tommaso Laurenzi
- mention caveat of setting 'background' option - ([9a383a1](https://github.com/kanagawa-community/neovim/commit/9a383a16136256a4138ed5ce33dddf164e1f81a2)) - Tommaso Laurenzi

### Continuous Integration

- add the shared file checks (#203) - ([c5a54fc](https://github.com/kanagawa-community/neovim/commit/c5a54fc24618bfa7c85b0088cfe8845b88b078c7)) - [@sravioli](https://github.com/sravioli)
- add the shared file checks - ([7dd6892](https://github.com/kanagawa-community/neovim/commit/7dd68922852dd68dcd9152329fa7c6b45a429938)) - [@sravioli](https://github.com/sravioli)
- add cocogitto configuration and workflows (#201) - ([b1a2f91](https://github.com/kanagawa-community/neovim/commit/b1a2f918279b80501626876f69eb7643889079ec)) - [@sravioli](https://github.com/sravioli)
- add cocogitto configuration and workflows - ([42019aa](https://github.com/kanagawa-community/neovim/commit/42019aa3d9177c8d37a785e6db8f70a661c21b73)) - [@sravioli](https://github.com/sravioli)

### Refactoring

- (**compile**) cleaner path generation - ([88d4850](https://github.com/kanagawa-community/neovim/commit/88d485039f4a2251f006e932dcab0132443d73b1)) - Tommaso Laurenzi
- (**extras**) clean up alacritty themes - ([b5d990e](https://github.com/kanagawa-community/neovim/commit/b5d990efbde05dd39e24309929c0fce0cf8d7982)) - Oliver Kraitschy
- (**extras**) group extra themes under tool directory - ([83e377c](https://github.com/kanagawa-community/neovim/commit/83e377c22d1b4035798713fa85517fb34716984b)) - WieeRd
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) (**overhaul**) WIP deep refactor of theme colors - ([ff3ce26](https://github.com/kanagawa-community/neovim/commit/ff3ce261c0ca4bd478f6a22d7589de52651f78cc)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) (**theme**) theme -> background; add theme option to be used when bg is not specified - ([a2be0b1](https://github.com/kanagawa-community/neovim/commit/a2be0b1caa87250d317652fb16614dafa64e870c)) - Tommaso Laurenzi
- move hsluv to lib - ([9301686](https://github.com/kanagawa-community/neovim/commit/93016863980e01a8d4957f83838b87a76db2b778)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) use nvim_set_hl - ([dc51a23](https://github.com/kanagawa-community/neovim/commit/dc51a2385068083f324b28649cb41c5a7290dfa2)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) add theme support, rework setup routine - ([7c64f63](https://github.com/kanagawa-community/neovim/commit/7c64f63b4fb33c20a3f851097bfeb13093149de4)) - Tommaso Laurenzi
- ![BREAKING](https://img.shields.io/badge/BREAKING-red) rework color table and setup function - ([d1d785c](https://github.com/kanagawa-community/neovim/commit/d1d785c0a71f28f8f535c090f6bb22618f69dd4f)) - Tommaso Laurenzi

### Misc

- ![BREAKING](https://img.shields.io/badge/BREAKING-red) (**config**) remove check_config logic, but keep it for the future - ([5ff1359](https://github.com/kanagawa-community/neovim/commit/5ff1359ea1fa6aa30eedb2db75900b30378a3c17)) - Tommaso Laurenzi

### Style

- format the palette table with Prettier - ([81682ca](https://github.com/kanagawa-community/neovim/commit/81682caa89b03bc5ad0e53b34f60c76218ff712e)) - [@sravioli](https://github.com/sravioli)
