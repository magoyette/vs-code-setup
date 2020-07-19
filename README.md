# VS Code Setup

My personal VS Code setup.

## Extensions for all operating systems

| Extension | Description |
| --------- | ----------- |
| [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) | Mark and jump to bookmarks. |
| [Calva](https://marketplace.visualstudio.com/items?itemName=betterthantomorrow.calva) | Clojure and ClojureScript support. |
| [clj-kondo](https://marketplace.visualstudio.com/items?itemName=borkdude.clj-kondo) | Lint Clojure and ClojureScript files with clj-kondo. |
| [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) | Debug with Chrome from VS Code. |
| [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug) | Debug with Firefox from VS Code. |
| [ES7 React/Redux/React-Native/JS snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) | Snippets for React. |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | Lint JavaScript files with ESLint. |
| [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) | Support for .gitignore files. |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | Improves Git History and Git Blame support in VS Code. |
| [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) | Lint Markdown files with markdownlint. |
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) | Icon theme with Material Design icons. |
| [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) | Run nom commands and verify installed version of NPM packages. |
| [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) | Autocomplete npm modules in import statements. |
| [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | Autocomplete file names. |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | Format code with Prettier. |
| [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) | Quick access to switch between projects. |
| [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) | Remote extension for Docker. |
| [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh) | Remote extension for SSH servers. |
| [Remote - SSH: Editing Configuration Files](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh-edit) | Editor for SSH configuration files. |
| [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck) | Lint bash and sh files with ShellCheck. |
| [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint) | Lint CSS and Sass files with stylelint. |
| [Transformer](https://marketplace.visualstudio.com/items?itemName=dakara.transformer) | Additional text operations like sorting. |

## Extensions for Windows

| Extension | Description |
| --------- | ----------- |
| [Remote - WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl) | Remote extension for the Windows Subsystem for Linux. |

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
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
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

### Calva Keybindings

All commands are prefixed with Calva.

|  Keybinding               | Command                                        |
| ------------------------- | ---------------------------------------------- |
| Ctrl+Alt+C Ctrl+Alt+J     | Jack-in                                        |
| Ctrl+Alt+C Enter          | Load current namespace and deps                |
| Ctrl+Alt+C Ctrl+Alt+N     | Load current namespace in REPL                 |
| Ctrl+Alt+C E              | Eval current form inline                       |
| Ctrl+Alt+C Space          | Eval current top level form inline             |
| Ctrl+Alt+C Ctrl+Alt+E     | Eval current form in REPL                      |
| Ctrl+Alt+C Ctrl+Alt+Space | Eval current top level form in REPL            |
| Ctrl+Alt+C C              | Eval current form and add as comment           |
| Ctrl+Alt+C Space          | Eval current top level form and add as comment |
| ESC                       | Hide eval results                              |
| Ctrl+Alt+C Ctrl+C         | Copy last evaluation results                   |
| Ctrl+Alt+C S              | Select current form                            |
| Alt+Up / Alt+Down         | Navigate REPL history                          |
| Alt+Enter (Enter at eol)  | Submit and print results from REPL             |
| Ctrl+Alt+C T              | Run tests from current namespace               |
| Ctrl+Alt+C Shift+T        | Run all tests                                  |
| Ctrl+Alt+C Ctrl+Alt+T     | Run current test                               |
| Ctrl+Alt+C Ctrl+T         | Run previously failing tests                   |

#### Paredit Deletion Keybindings

|  Keybinding   | Command                                           |
| ------------- | ------------------------------------------------- |
| Backspace     | Delete 1 char backward without unbalancing a form |
| Delete        | Delete 1 char forward without unbalancing a form  |
| Alt+Backspace | Delete 1 char backward                            |
| Alt+Delete    | Delete 1 char forward                             |

#### Paredit Selection Keybindings

|  Keybinding  | Command          |
| ------------ | ---------------- |
| Ctrl+W       | Expand selection |
| Ctrl+Shift+W | Shrink selection |

#### Paredit Edition Keybindings

|  Keybinding      | Command                            |
| ---------------- | ---------------------------------- |
| Ctrl+Right       | Slurp forward the closing bracket  |
| Ctrl+Left        | Barf forward the closing bracket   |
| Ctrl+Shift+Left  | Slurp backward the opening bracket |
| Ctrl+Shift+Right | Slurp forward the opening bracked  |
