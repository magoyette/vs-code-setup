# VS Code Setup

My personal VS Code setup.

## Extensions for all operating systems

| Extension | Description |
| --------- | ----------- |
| [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) | Mark and jump to bookmarks. |
| [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) | Debug with Chrome from VS Code. |
| [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug) | Debug with Firefox from VS Code. |
| [ES7 React/Redux/React-Native/JS snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) | Snippets for React. |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | Lint JavaScript files with ESLint. |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | Improves Git History and Git Blame support in VS Code. |
| [Hugo Language and Syntax Support](https://marketplace.visualstudio.com/items?itemName=budparr.language-hugo-vscode) | Syntax highlight for Hugo Templates. |
| [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) | Lint Markdown files with markdownlint. |
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) | Icon theme with Material Design icons. |
| [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) | Run nom commands and verify installed version of NPM packages. |
| [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) | Autocomplete npm modules in import statements. |
| [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | Autocomplete file names. |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | Format code with Prettier. |
| [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck) | Lint bash and sh files with ShellCheck. |
| [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint) | Lint CSS and Sass files with stylelint. |
| [Transformer](https://marketplace.visualstudio.com/items?itemName=dakara.transformer) | Additional text operations like sorting. |

## Settings

```json
{
  "editor.minimap.enabled": false,
  "editor.fontFamily": "'DejaVu Sans Mono', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
  "editor.fontSize": 16,
  "editor.lineHeight": 20,
  "files.trimTrailingWhitespace": true,
  "telemetry.enableCrashReporter": false,
  "workbench.enableExperiments": false,
  "telemetry.enableTelemetry": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",
  "workbench.editor.enablePreview": false,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "gitlens.currentLine.enabled": false,
  "gitlens.hovers.currentLine.over": "line",
  "gitlens.codeLens.enabled": false,
  "gitlens.statusBar.enabled": false,
  "gitlens.hovers.enabled": false,
}
```

## Keybindings

### Navigation Keybindings

|  Keybinding                 | Command                            |
| --------------------------- | ---------------------------------- |
| Ctrl+Shift+P                | Command palette                    |
| Ctrl+P                      | Quick open (can use file@symbol)   |
| Ctrl+TAB and Ctrl+Shift+Tab | Cycle through opened files         |
| Ctrl+Shift+M                | Errors and Warnings                |
| Ctrl+F                      | Search opened files                |
| Ctrl+Shift+F                | Search workspace                   |
| Alt+Mouse                   | Open editors splitted horizontally |
| Ctrl+1, Ctrl+2 ...          | Switch between editors             |
| Ctrl+F4                     | Close active editor                |
| Ctrl+PageDown               | Go to right editor                 |
| Ctrl+PageUp                 | Go to left editor                  |

### Views Keybindings

|  Keybinding    | Command             |
| -------------- | ------------------- |
| Ctrl+B         | Toggle sidebar      |
| Ctrl+Shift+G G | Source Control view |

### Code Keybindings

|  Keybinding      | Command                                              |
| ---------------- | ---------------------------------------------------- |
| Ctrl+Space       | Intellisense                                         |
| Ctrl+Shift+Space | Show current completion signature                    |
| Ctrl+Shift+O     | Go to symbol in current file                         |
| Ctrl+T           | Go to symbol in workspace                            |
| Alt+F12 or F12   | Go to definition                                     |
| Ctrl+Shift+F10   | Peek definition                                      |
| Shift+F12        | Go to References                                     |
| Ctrl+G           | Navigate to a specific line in current file          |
| Ctrl+K Ctrl+I    | Show hover at cursor                                 |
| Ctrl+Shift+I     | Format file                                          |
| Shift+Alt+O      | Organize imports                                     |
| F2               | Rename symbol at cursor                              |
| Ctrl+.           | Code actions (refactorings and fixes)                |
| Shift+Alt+Right  | Expand selection                                     |
| Shift+Alt+Left   | Shrink selection                                     |
| Alt+Click        | Add a cursor                                         |
| Ctrl+Shift+L     | Select all occurences of the currently selected text |
| Shift+Alt+Mouse  | Box selection                                        |
| Alt+Ctrl+K       | Toggle bookmark                                      |

### JavaScript and TypeScript Keybindings

|  Keybinding | Command                                          |
| ----------- | ------------------------------------------------ |
| Ctrl+Alt+R  | JavaScript, TypeScript and React snippets search |

### Markdown Keybindings

|  Keybinding  | Command                         |
| ------------ | ------------------------------- |
| Ctrl+Shift+V | Switch between code and preview |
| Ctrl+K V     | Preview side-by-side            |
