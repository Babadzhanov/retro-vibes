# Retro Vibes Theme [![Version](https://vsmarketplacebadge.apphb.com/version/babadzhanov.retro-vibes.svg)](https://marketplace.visualstudio.com/items?itemName=Babadzhanov.retro-vibes)

![RetroVibes](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/retro-vibes.png)

Feel the Vibes with this Retro style inspired Visual Studio Code Theme.

## Screenshots

![screenshot-1](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/screenshot-1.jpg)

![screenshot-2](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/screenshot-2.jpg)

![screenshot-3](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/screenshot-3.jpg)

## Install

Execute this command from the command line.

```bash
code --install-extension babadzhanov.retro-vibes
```

## How to get the most of color decorations

Turn on/off options in settings menu or settings.json

- Git decorations

> `git.decorations.enabled: true/false`

![git.decorations](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/git-decorations.jpg)

- Highlight modified tabs

> `workbench.editor.highlightModifiedTab: true/false`

![highlight-modified-tab](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/highlight-modified-tab.jpg)

- Problems decorations

> `problems.decorations.enabled: true/false`

![problems-decorations](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/problems-decorations.jpg)

- Overview ruler border (under scroll)

> `editor.overviewRulerBorder: true/false`

![overview-ruler](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/overview-ruler.jpg)

- Minimap

> `editor.minimap.enabled: true/false`

![minimap](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/assets/minimap.jpg)

## Tweaks

To tweak this theme a little bit you can go to settings.json and modify fields accordingly:\
(if you think a color can suit better to the overall vibe, please consider contributing down below)

### Workbench colors

``` json
"workbench.colorCustomizations": {
    "[Retro Vibes]": {
        "focusBorder": "#7c8bb0",
        "foreground": "#a0a8bb",
        "widget.shadow": "#29334490",
        ...
    }
}
```

### Syntax highlighting

``` json
"editor.tokenColorCustomizations": {
  "[Retro Vibes]": {
    "textMateRules": [
      {
        "scope": ["comment"],
        "settings": {
          "foreground": "#4b643e"
        }
      }
      ...
    ]
  }
}
```

### Semantic highlighting

``` json
"editor.semanticTokenColorCustomizations": {
    "[Retro Vibes]": {
        "rules": {
            "*.declaration": { "bold": true }
            ...
        }
    }
}
```

## Contributing

Please, report issues/bugs and suggestions [here](https://github.com/babadzhanov/retro-vibes/issues).

## Change log

You can take a look at the [change log](https://raw.githubusercontent.com/babadzhanov/retro-vibes/master/CHANGELOG.md).

## Old version

Old version of the theme can be found [here](https://marketplace.visualstudio.com/items?itemName=Babadzhanov.retro-vibes-old).

## License

[MIT](LICENSE) © [Simeon Babadzhanov](https://github.com/babadzhanov)
