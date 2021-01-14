# VS Code
Install vs code

#### Settings JSON
Make gitbash default terminal window in VS Code
- `Ctrl + (`) to open terminal
- `Ctrl + Shft + P` open command pallete
- search `Select Default Shell` and choose gitbash option

```
"terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe"

{
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "editor.formatOnSave": true
},
{
  "php.validate.executablePath": "C:\\xampp\php\php.exe"
},
{
  "todo-tree.highlights.defaultHighlight": {
    "foreground": "yellow",
    "background": "black"
  }
}
```
#### Extensions
- indent-rainbow
- Live Server
  - `alt + L and alt + O` launch live server

#### VS Shortcuts
- `ctrl + shft + P` open command pallete
- `ctrl ,` open settings
- `ctrl + /`comment out selection (html, css)
- `f2` rename variable and function simultaneously
- `shift + alt + left/right` expand selection
- `ctrl + g + number` to go to line
- `ctrl + l` select line
- `alt + up/down` move selection up or down
- `ctrl + space` evoke intellisense auto-suggest

#### HTML
- `&nbsp;` force space

#### Keybindings JSON
```
[
    {
        "key": "alt+w",
        "command": "editor.emmet.action.wrapWithAbbreviation",
        "when": "editorTextFocus && !editorReadonly"
    }
]
```

#### Emmet Shortcuts
- `!` html start doc

#### Chrome Dev Tools
- `ctrl + shift + I` developer tools
