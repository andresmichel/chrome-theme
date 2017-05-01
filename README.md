# Chrome theme
Sublime Text 3 theme based on [Chrome for Chrome OS](http://sebastien-gabriel.com/work/chrome-cros).

## Installation

1. Download the [latest release](https://github.com/andresmichel/chrome-theme/releases/latest), extract and rename the directory to `Theme - Chrome`.
2. Move the directory inside your packages directory, `Preferences` > `Browse packages`.

## Activation
Open your preferences `Preferences` > `Setting - User` and add this lines:

```json
"color_scheme": "Packages/Theme - Chrome/Chrome.tmTheme",
"theme": "Chrome.sublime-theme"
```

### Recommended settings
```json
"caret_extra_bottom": 1,
"caret_extra_top": 2,
"caret_style": "blink",
"draw_white_space": "none",
"ensure_newline_at_eof_on_save": true,
"highlight_line": true,
"line_padding_bottom": 1,
"line_padding_top": 2,
"margin": 0,
"match_selection": false,
"scroll_past_end": false,
"show_definitions": false
```

### Optional settings
```json
"show_scroll_tabs": true,
"show_tabs_dropdown": true
```
