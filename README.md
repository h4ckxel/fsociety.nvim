<div align="center" width=50%>

# F S O C I E T Y NVIM

<img src="/images/menu-dash.png">

</div>

<div align="center">

`fsociety.nvim - NeoVim Setup`
`Custom NVIM by h4ckxel`

`Inspired by Mr. Robot`

</div>

---

## 🕶️ ABOUT FSOCIETY.NVIM

`fsociety.nvim` is a **NeoVim configuration** crafted for those who want their editor to feel like part of a hacker’s terminal — inspired by the aesthetics of **Mr. Robot**, **underground hacking groups**, and **minimalist cyber environments**.

Forget bloated IDEs and GUI editors. This is a setup for people who think in terminals, breathe in shells, and live between config files.

---

## 🎯 KEY OBJECTIVES

- Clean, fast, distraction-free
- Cyberpunk aesthetics: dark mode, blood red, greys, no neon
- ASCII Art Dashboard inspired by **fsociety**
- Designed for fast access to files, buffers, configs, terminals
- Minimal plugins, maximum impact

---

## 🛠️ CORE FEATURES

### ⚡ Aesthetic

- **ASCII banner:** Custom "fsociety" with quote on dashboard
- Transparent / terminal-native looks

### 📂 Project Navigation

- **fzf** for files, text search, live grep, buffers, sessions

### 🎨 UI

- **Lualine** statusline: Hacker styled HUD look
- No clutter, no icons overkill
- Nerd Font ready
- Clean, muted colors — no rainbow nonsense

### 🧑‍💻 Development Ready

- LSP installed via **LazyExtras**:
  - Python, C, C++, Java, Web (HTML/CSS/JS)
- **nvim-cmp** for autocompletion (buffers, path, LSP, snippets)
- Treesitter highlighting for modern syntax precision
- Git integration with **gitsigns.nvim**

### 🐚 Terminal Integration

- ToggleTerm for scratchpads (hack-friendly terminal in buffer)

---

## 💾 INSTALLATION INSTRUCTIONS

### ⚙ Prerequisites

- **LazyVim** ([Installation](https://www.lazyvim.org/installation))
- Neovim >= **0.9.0** (needs to be built with **LuaJIT**)
- Git >= **2.19.0** (for partial clones support)
- a [Nerd Font](https://www.nerdfonts.com/)(v3.0 or greater) (**optional, but needed to display some icons**)
- [lazygit](https://github.com/jesseduffield/lazygit) (optional)
- a C compiler for `nvim-treesitter`. See [here](https://github.com/nvim-treesitter/nvim-treesitter#requirements)
- curl for [blink.cmp](https://github.com/Saghen/blink.cmp) (completion engine)
- for [fzf-lua](https://github.com/ibhagwan/fzf-lua) (**_optional_**)
  - **fzf**: [fzf](https://github.com/junegunn/fzf) (**v0.25.1 or greater**)
  - **live grep**: [ripgrep](https://github.com/BurntSushi/ripgrep)
  - **find files**: [fd](https://github.com/sharkdp/fd)
- a terminal that support true color and undercurl:
  - [kitty](https://github.com/kovidgoyal/kitty) (**Linux & Macos**)
  - [wezterm](https://github.com/wezterm/wezterm) (**Linux, Macos & Windows**)
  - [alacritty](https://github.com/alacritty/alacritty) (**Linux, Macos & Windows**)
  - [iterm2](https://iterm2.com/) (**Macos**)

### 📥 Setup

```bash
# Clone the fsociety.nvim repo
git clone https://github.com/h4ckxel/fsociety.nvim/nvim ~/.config/nvim

# Launch Neovim
nvim
```

First run will install plugins via `lazy.nvim` automatically.

---

## 📂 FILE STRUCTURE OVERVIEW

```
~/.config/nvim
├── lua/
│   ├── config/               # Options, keymaps, autocommands
│   ├── plugins/              # Plugin setups
├── spell/                    # Custom files .txt
├── .neoconf.json
├── init.lua                  # Entry point
├── lazy/lock.json
├── lazyvim.json
├── LICENSE
├── stylua.toml
└── README.md                 # This file
```

---

## 🚀 KEYBINDINGS OVERVIEW (Dashboard)

| Action             | Key |
| ------------------ | --- |
| 🔍 Find File       | `f` |
| 📄 New File        | `n` |
| 🔎 Find Text       | `g` |
| 📂 Recent Files    | `r` |
| ⚙️ Config          | `c` |
| 🕑 Restore Session | `s` |
| 🛠️ Lazy Plugins    | `x` |
| 🔃 Lazy            | `l` |
| ❌ Quit            | `q` |

---

## 📦 INCLUDED PLUGINS (Minimalist, Efficient)

| Plugin           | Purpose                    |
| ---------------- | -------------------------- |
| `fzf`            | Fuzzy finder               |
| `alpha-nvim`     | Start screen / dashboard   |
| `lualine`        | Statusline aesthetic       |
| `treesitter`     | Better syntax highlighting |
| `gitsigns`       | Git inline signs           |
| `toggleterm`     | Terminal integration       |
| `LazyExtras`     | Manage LSP / Linters       |
| `nvim-lspconfig` | LSP configurations         |
| `cmp-nvim-lsp`   | Completion                 |
| `which-key`      | Keybinding cheatsheet      |
| `lazy.nvim`      | Plugin management          |

---

## ⚡ USAGE TIPS

| Action                   | Command        |
| ------------------------ | -------------- |
| Update Plugins           | `:Lazy update` |
| Check LSP Status         | `:LspInfo`     |
| Search Files             | `<leader>ff`   |
| Live Grep                | `<leader>fg`   |
| Open Terminal Scratchpad | `<C-\\>`       |
| Toggle File Explorer     | `<leader>e`    |

---

## 🧑‍🎤 RECOMMENDED TERMINAL SETUP (if you want hacker look)

- **Terminal:** Kitty / Alacritty / WezTerm
- **Shell:** ZSH with `powerlevel10k` or `starship`
- **Font:** Hack Nerd Font Mono / JetBrains Mono NF
- **Compositor:** Picom for transparency
- **WM:** Hyprland / Sway / BSPWM
- **Colors:** Desert in Nvim / Nord / Dracula (adjusted to fsociety red)

---

## 📝 INSPIRATION & CREDITS

- **Mr. Robot / fsociety**
- [Gentleman.Dots](https://github.com/Gentleman-Programming/Gentleman.Dots) (Framework inspiration)
- **LazyVim ecosystem**
- **HackTheBox, OWASP, Arch Wiki**
- Minimalist and Unixphile dotfile culture

---

## 📜 LICENSE

This configuration is open-source under the **MIT License**.
Feel free to fork, modify, use, and share.

---

## 💀 FINAL WORD

```text
Control is an illusion.
Hack the planet.
Own your tools, own your mind.
```

<div align="center">

━━━━━━━━━━━━━━━━ H A C K T H E P L A N E T ━━━━━━━━━━━━━━━━

</div>

