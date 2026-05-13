# marginalia

dark theme for [obsidian](https://obsidian.md), extending the visual language of [fyrr.me](https://fyrr.me)

## preview

<img width="1814" height="1058" alt="prev1" src="https://github.com/user-attachments/assets/943d62cd-8b9b-4635-81fc-9b83d1fd4918" />
<img width="952" height="832" alt="screenshot 2026-05-13 at 09 28 23" src="https://github.com/user-attachments/assets/22956d44-3ee1-4267-b4e7-52069aaf3b18" />
<img width="2332" height="1614" alt="screenshot 2026-05-13 at 09 25 23" src="https://github.com/user-attachments/assets/1aaf4e87-60d8-4b97-953c-253a777b63f1" />

## install

### from source

1. clone this repo
2. copy the folder into `<vault>/.obsidian/themes/marginalia/`
3. copy the `assets/` folder containing the fonts into the same location
4. in obsidian, open `settings → appearance → themes` and pick **marginalia**

## fonts

ships with two custom fonts, loaded locally from `assets/`:

- [medodica](https://www.dafont.com/medodica.font) — body text, interface, h2–h6
- [im fell english](https://fonts.google.com/specimen/IM+Fell+English) — h1, display

monospace falls back to the system stack (`ui-monospace`, `sf mono`, `menlo`, `consolas`).

## palette

### backgrounds
| role | hex |
|---|---|
| base | `#0a0a0a` |
| surface | `#1a1a1a` |
| border | `#222222` |
| copyright | `#2a2a2a` |

### text
| role | hex |
|---|---|
| text | `#e8e8e8` |
| secondary | `#aaaaaa` |
| muted | `#9a9a9a` |
| subtle | `#666666` |

### accents
| role | hex |
|---|---|
| now (soft blue) | `#81bbeb` |
| cyan (primary) | `#6dd5d5` |
| thoughts (violet) | `#a78bfa` |
| spirituality (light amber) | `#f6c177` |
| amber (deep) | `#c9a84c` |
| ost (rose) | `#eb6f92` |
| contact (magenta) | `#e58fce` |
| uses (sage) | `#9ccfa4` |

### headings
| level | accent |
|---|---|
| h1 | now |
| h2 | thoughts |
| h3 | spirituality |
| h4 | ost |
| h5 | uses |
| h6 | contact |

### callouts
| type | accent |
|---|---|
| note | cyan |
| info | now |
| tip / success | uses |
| question | thoughts |
| quote | amber |
| warning | spirituality |
| failure / danger / bug | ost |
| example / todo | contact |
| abstract / summary / tldr | muted |
