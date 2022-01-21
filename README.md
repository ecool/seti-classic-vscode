# Info
This is a port of the Atom theme `seti-classic`, which is also a fork of the original `seti-ui`, for VSCode.

This does not include the seti-icons because that is already included in VSCode.

![Screenshot](images/screenshot.png)

# Terminal
- `terminus` prezto prompt from my fork of [prezto](https://github.com/ecool/prezto)

# Extensions Used
- [snippets-viewer](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.snippets-viewer)

# Settings
```json
"editor.bracketPairColorization.enabled": true,
"editor.guides.bracketPairs": true,
"editor.guides.highlightActiveBracketPair": false,
"editor.guides.bracketPairsHorizontal": false,
```

# Font
`FiraCode Nerd Font` from [Nerd Fonts](https://www.nerdfonts.com)

## Font Settings
```json
"editor.fontFamily": "'FiraCode Nerd Font', Consolas, 'Courier New', monospace",
"editor.fontLigatures": "'ss02', 'ss03', 'ss05', 'ss07', 'zero'",
"editor.fontSize": 18,
"editor.fontWeight": 400,
```

## Languages Tested
- C / C++
- C#
- EditorConfig
- F#
- CSS
- HTML / XML
- JavaScript / TypeScript
- Java
- JSON
- Python
- ZSH

# Known Issues
- Currently there seems to be some weird interaction between Semantic Highlighting and the VSCode File Changes Side-by-Side view. [VSCode Issue](https://github.com/microsoft/vscode/issues/126722)

## See:
- [seti-classic](https://github.com/vermotr/seti-classic)
- [seti-classic-syntax](https://github.com/vermotr/seti-classic-syntax)
- [seti-ui](https://github.com/jesseweed/seti-ui)
- [seti-syntax](https://github.com/jesseweed/seti-syntax)
