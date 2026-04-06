# eva24 — starship prompt theme

> a starship prompt config built around the eva24 color palette.

[what is starship?](#what-is-starship) • [requirements](#requirements) • [quick start](#quick-start) • [what the prompt shows](#what-the-prompt-shows) • [colors](#colors)

---

## what is starship?

[starship](https://starship.rs) is a cross-shell prompt — it replaces the default shell prompt with something configurable and context-aware. it works on fish, bash, zsh, and others without changing your shell.

---

## requirements

- [starship](https://starship.rs) installed
- a [nerd font](https://www.nerdfonts.com/font-downloads) set in your terminal (for icons and glyphs)
- kitty, ghostty, or any terminal emulator that supports true color

---

## quick start

**step 1 — install starship**

```bash
curl -sS https://starship.rs/install.sh | sh
```

**step 2 — enable it in your shell**

for fish:
```bash
# add to ~/.config/fish/config.fish
starship init fish | source
```

for bash:
```bash
# add to ~/.bashrc
eval "$(starship init bash)"
```

for zsh:
```bash
# add to ~/.zshrc
eval "$(starship init zsh)"
```

**step 3 — apply the config**

```bash
curl -o ~/.config/starship.toml https://raw.githubusercontent.com/anoscetia/eva24/main/starship.toml
```

or copy it manually — paste the contents of `starship.toml` from this repo into `~/.config/starship.toml`.

open a new terminal. done.

---

## what the prompt shows

```
user@hostname   directory   branch   git status
❯
```

| segment | color | what it means |
|---|---|---|
| `user@hostname` | rei blue `#81bbeb` | who you are and what machine you're on |
| `directory` | eva01 purple `#b487d5` | current folder (truncated to 3 levels) |
| `git branch` | gold `#f6c177` | active git branch — only shows inside a git repo |
| `git status` | asuka `#eb6f92` | repo state — shows symbols when there's something to act on |
| `❯` | purple / red on error | command prompt — red means the last command failed |

**git status symbols:**

| symbol | meaning |
|---|---|
| `?` | untracked files (not yet added) |
| `!` | modified files |
| `+` | staged files (added, not committed) |
| `✘` | deleted files |

the `cmd_duration` segment (gold badge) appears automatically when a command takes more than 2 seconds to run.

---

## colors

the full eva24 palette used in this config:

| name | hex | role |
|---|---|---|
| base | `#1a1a1a` | background |
| rei | `#81bbeb` | user/hostname segment |
| eva01 | `#b487d5` | directory segment, prompt character |
| gold | `#f6c177` | git branch, command duration |
| asuka | `#eb6f92` | git status, error state |
| foreground | `#ffffff` | text |

the full palette (including the 16 terminal colors) lives in `eva24.conf` — a kitty theme file you can use separately.

---





