# Extras
Customize other extensions to match the theme.

## Bracket Pair Colorization
If you have `Bracket Pair Colorization` enabled, you need to do the following to get Bifrost colors for your brackets and similar symbols:

1. Hit `Ctrl+Shift+P` (Windows) / `Cmd+Shift+P`(Mac) and open `Preferences: Open User Settings (JSON)`

2. Paste the following code there:

```
"editor.bracketPairColorization.enabled": true,
"workbench.colorCustomizations": {
    "editorBracketHighlight.foreground1": "#eaf2fa",
    "editorBracketHighlight.foreground2": "#b595fb",
    "editorBracketHighlight.foreground3": "#ff978a",
    "editorBracketHighlight.foreground4": "#24f7a6",
    "editorBracketHighlight.foreground5": "#fb65c0",
    "editorBracketHighlight.foreground6": "#ffeb95",
    "editorBracketHighlight.unexpectedBracket.foreground": "#fd604b",
},
```
## Better Comments
If you use the [Better Comments](https://github.com/aaron-bond/better-comments) extension, I recommend customizing the colors like this in your User Settings JSON:

```
{
    "better-comments.tags": [
        {
            "tag": "!",
            "color": "#fd604b",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "?",
            "color": "#b595fb",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "//",
            "color": "#737f83",
            "strikethrough": true,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "todo",
            "color": "#ffeb94",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "*",
            "color": "#24f7a6",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        }
    ]
}
```
---
### Additional extensions
If you are using extensions that you think would look good with colors from the Bifrost Theme, please get in touch and I will look into it :-)