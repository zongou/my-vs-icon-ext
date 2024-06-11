# My Icon Theme

[API](https://code.visualstudio.com/api/extension-guides/file-icon-theme)

## Get up and running straight away

- Press `F5` to open a new window with your extension loaded.
- Open `File > Preferences > Color Themes` and pick your color theme.
- Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Install your extension

- To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
- To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

## Enable this fonticon theme

```json
  "workbench.iconTheme": "seti-based",
  "editor.fontLigatures": true,
  // "editor.fontFamily": "'VictorMono NFM', 'Droid Sans Mono', 'monospace', monospace",
  "editor.fontFamily": "'FiraCode Nerd Font Mono', 'Droid Sans Mono', 'monospace', monospace",
```
