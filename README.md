# config-cmux

[Ghostty](https://ghostty.org/) terminal themes designed to pair with [Cursor](https://cursor.com/) IDE color schemes.

Some dark variants are based on [ydkulks/cursor-dark.nvim](https://github.com/ydkulks/cursor-dark.nvim).

## Themes

| Theme | Description |
|-------|-------------|
| **cmux-light** | Matches Cursor IDE light palette |
| **cmux-midnight** | Dark midnight variant |
| **cmux-night** | Dark night variant |
| **cursor-light** | Warm, earthy light theme inspired by Cursor |
| **cursor-night** | Dark companion to cursor-light |

The `cursor-light` / `cursor-night` pair supports Ghostty's automatic light/dark switching:

```
theme = light:cursor-light,dark:cursor-night
```

## Installation

Copy a theme file to your [Ghostty themes directory](https://ghostty.org/docs/config#theme) and set it in your config:

```sh
cp themes/<theme-name> ~/.config/ghostty/themes/
```

Then in `~/.config/ghostty/config`:

```
theme = <theme-name>
```
