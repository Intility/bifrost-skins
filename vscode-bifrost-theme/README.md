[Intility Bifrost Theme](#intility-bifrost-theme)

# Intility Bifrost Theme 
This is a color theme for Visual Studio Code inspired by the [Intility Bifrost Design System](https://bifrost.intility.com/). 

___
## Installation
Open VS Code and search for `Intility Bifrost` in the Extensions pane, and then intall and activate the color theme. 

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
The theme should work with any font/typeface, but I recommend installing and using [Jetbrains Mono](https://www.jetbrains.com/lp/mono/). Once the font is installed, just open `Settings` in VS Code, search for `Font` and add `JetBrains Mono` to the front of the list.

___
## Screenshot
![Theme screenshot](https://intility.no/wp-content/uploads/2022/12/screenshot.png)
___
## Credit
This theme was made using a online tool for creating VS Code themes, as well as manually assigning colors.

The tool used can be found [here](https://themes.vscode.one/).

___
## Feedback
There are a lot of bits and pieces that can and have been colored in VS Code by this theme, and I anticipate some bugs and/or less-than-optimal color usage. If you are using the theme and want to either report a bug/potential color issue and/or give other feedback on the theme, please [get in touch](msteams://teams.microsoft.com/l/chat/0/0?users=august.gaukstad@intility.no) with me *(the link opens a chat with me in Microsoft Teams)*.

**Happy coding! :)**

___
## Todo
+ Convert theme for use with Visual Studio