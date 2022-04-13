# VS Code Setup

My personal VS Code setup.

## Extensions

- [Bash IDE](https://marketplace.visualstudio.com/items?itemName=mads-hartmann.bash-ide-vscode&ssr=false#overview): Language server for Bash.
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks): Mark and jump to bookmarks.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker): Spell checker with programming languages awareness.
- [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug): Debug with Firefox from VS Code.
- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker): Editor for Docker files and integration with Docker containers.
- [edamagit](https://marketplace.visualstudio.com/items?itemName=kahole.magit): Magit for VS Code.
- [ES7 React/Redux/React-Native/JS snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets): Snippets for React.
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Lint JavaScript files with ESLint.
- [French - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-french): French Dictionary for Code Spell Checker.
- [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme): GitHub theme.
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Improves Git History and Git Blame support in VS Code.
- [Hugo Language and Syntax Support](https://marketplace.visualstudio.com/items?itemName=budparr.language-hugo-vscode): Syntax highlight for Hugo Templates.
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint): Lint Markdown files with markdownlint.
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme): Icon theme with Material Design icons.
- [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script): Run nom commands and verify installed version of NPM packages.
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense): Autocomplete npm modules in import statements.
- [Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff): Diff selections of text.
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense): Autocomplete file names.
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Format code with Prettier.
- [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv): Syntax highlight for CSVs and TSVs.
- [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck): Lint bash and sh files with ShellCheck.
- [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint): Lint CSS and Sass files with stylelint.
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree): Tree view of TODOs in workspace.
- [Transformer](https://marketplace.visualstudio.com/items?itemName=dakara.transformer): Additional text operations like sorting.

## Settings

```json
{
  "cSpell.ignoreRegExpList": ["/\\w+([0-9]+\\w*)+/"],
  "cSpell.language": "en,fr",
  "editor.minimap.enabled": false,
  "editor.fontFamily": "'DejaVu Sans Mono', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
  "editor.fontSize": 16,
  "editor.lineHeight": 20,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "extensions.ignoreRecommendations": false,
  "files.trimTrailingWhitespace": true,
  "git.closeDiffOnOperation": true,
  "gitlens.currentLine.enabled": false,
  "gitlens.hovers.currentLine.over": "line",
  "gitlens.codeLens.enabled": false,
  "gitlens.statusBar.enabled": false,
  "gitlens.hovers.enabled": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "telemetry.telemetryLevel": "off",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "workbench.colorTheme": "GitHub Light Default",
  "workbench.editor.enablePreview": false,
  "workbench.enableExperiments": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "files.trimTrailingWhitespace": false
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "editor.linkedEditing": true
}
```

## Keybindings (for Windows)

```json
[
  {
    "key": "ctrl+alt+i",
    "command": "bookmarks.toggleLabeled"
  },
  {
    "key": "ctrl+alt+o",
    "command": "bookmarks.list"
  },
  {
    "key": "ctrl+alt+u",
    "command": "bookmarks.listFromAllFiles"
  },
  {
    "key": "ctrl+alt+oem_period",
    "command": "cSpell.addWordToWorkspaceSettings"
  },
  {
    "key": "capslock",
    "command": "editor.toggleFold",
    "when": "editorTextFocus && foldingEnabled"
  },
  {
    "key": "ctrl+k ctrl+l",
    "command": "-editor.toggleFold",
    "when": "editorTextFocus && foldingEnabled"
  }
]
```

### Commands

| Keybinding   | Command         |
| ------------ | --------------- |
| Ctrl+Shift+P | Command Palette |
| Ctrl+,       | Settings        |

### Navigation

| Keybinding                 | Command                                                                  |
| -------------------------- | ------------------------------------------------------------------------ |
| Ctrl+P                     | Open a file by name                                                      |
| Ctrl+Tab et Ctrl+Shift+Tab | Select a file in a list of opened files                                  |
| Alt+Left                   | Go to previous edit location                                             |
| Alt+Right                  | Go to next edit location                                                 |
| F12 or Ctrl+Click          | Go to the definition of a symbol                                         |
| Alt+F12                    | Peek definition of symbol                                                |
| Ctrl+F12                   | Go to implementation of a symbol                                         |
| Ctrl+Shift+O               | Go to a symbol in the current file by name (type : to group by category) |
| Ctrl+T                     | Go to a symbol in a file of the project by name                          |
| Shift+Alt+F12              | Find references                                                          |

### Views and panels

| Keybinding     | Command             |
| -------------- | ------------------- |
| Ctrl+B         | Toggle sidebar      |
| Ctrl+Shift+E   | Explorer view       |
| Ctrl+Shift+G G | Source control view |
| Ctrl+Shift+M   | Problems panel      |
| Ctrl+Shift+X   | Extensions view     |
| Ctrl+`         | Terminal panel      |

### Problems and refactoring

| Keybinding | Command                                           |
| ---------- | ------------------------------------------------- |
| F8         | Go to next problem                                |
| Shift+F8   | Go to previous problem                            |
| Ctrl+.     | Quick fix and refactoring for the current problem |
| F2         | Rename symbol                                     |

### Edition

| Keybinding                 | Command                  |
| -------------------------- | ------------------------ |
| Ctrl+Shift+Alt+(arrow key) | Column (box) selection   |
| Shift+Alt+Left             | Shrink current selection |
| Shift+Alt+Right            | Expand current selection |
| Alt+Up or Alt+Down         | Move line up or down     |
| Ctrl+Shift+K               | Delete line              |
| Ctrl+Enter                 | Insert line below        |
| Ctrl+Shift+Enter           | Insert line above        |
| Ctrl+Up or Ctrl+Down       | Scroll line up or down   |

### Search

| Keybinding   | Command                                                              |
| ------------ | -------------------------------------------------------------------- |
| Ctrl+F       | Search in current editor (navigate results with Enter & Shift+Enter) |
| F3           | Go to next search result                                             |
| Shift+F3     | Go to previous search result                                         |
| Ctrl+H       | Replace in current editor                                            |
| Ctrl+Shift+F | Search all files in current folder                                   |

### Code

| Keybinding  | Command      |
| ----------- | ------------ |
| Ctrl+Space  | Intellisense |
| Shift+Alt+F | Format file  |

### Multiple Cursors

| Keybinding    | Command          |
| ------------- | ---------------- |
| Alt+Click     | Add cursors      |
| Ctrl+Alt+Down | Add cursor below |
| Ctrl+Alt+Up   | Add cursor above |

### Folding

| Keybinding | Command                           |
| ---------- | --------------------------------- |
| Caps Lock  | Toggle fold of the current region |

### Git

| Keybinding | Command                   |
| ---------- | ------------------------- |
| F7         | Go to next difference     |
| Shift+F7   | Go to previous difference |

### Markdown

| Keybinding   | Command                                    |
| ------------ | ------------------------------------------ |
| Ctrl+Shift+V | Switch between Markdown editor and preview |
| Ctrl+K V     | Open preview on the side                   |
| Alt+Shift+F  | Format Markdown table                      |

### Bookmarks

| Keybinding | Command                   |
| ---------- | ------------------------- |
| Ctrl+Alt+K | Toggle bookmark           |
| Ctrl+Alt+I | Toggle labeled bookmark   |
| Ctrl+Alt+L | Jump to next bookmark     |
| Ctrl+Alt+J | Jump to previous bookmark |
| Ctrl+Alt+O | List bookmarks            |
| Ctrl+Alt+U | List from all files       |

### Code Spell Checker

| Keybinding | Command                         |
| ---------- | ------------------------------- |
| Ctrl+Alt+. | Add words to workspace settings |

### edamagit

| Keybinding   | Command          |
| ------------ | ---------------- |
| Alt+X G      | Magit Status     |
| Alt+X Alt+G  | Magit File Popup |
| Alt+X Ctrl+G | Magit Dispatch   |
| Shift+É      | Magit Help       |
