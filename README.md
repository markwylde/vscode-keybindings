Adding the following command to your vscode keybindings will push the up key and hit enter, essentially running the last command in the terminal.

keybindings.json
```
[{
  "key": "ctrl+enter",
  "command": "workbench.action.terminal.sendSequence",
  "args": {
    "text": "\u001b[A\u000D"
  }
}]
```
