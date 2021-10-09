# VS Code Setup

My personal VS Code setup.

## Extensions for all operating systems

| Extension | Description |
| --------- | ----------- |
|[Bash IDE](https://marketplace.visualstudio.com/items?itemName=mads-hartmann.bash-ide-vscode&ssr=false#overview)|Language server for Bash.|
|[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)|Mark and jump to bookmarks.|
|[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)|Spell checker with programming languages awareness.|
|[Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug)|Debug with Firefox from VS Code.|
|[Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)|Editor for Docker files and integration with Docker containers.|
|[edamagit](https://marketplace.visualstudio.com/items?itemName=kahole.magit)|Magit for VS Code.|
|[ES7 React/Redux/React-Native/JS snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)|Snippets for React.|
|[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)|Lint JavaScript files with ESLint.|
|[French - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-french)|French Dictionary for Code Spell Checker.|
|[GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)|GitHub theme.|
|[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)|Improves Git History and Git Blame support in VS Code.|
|[Hugo Language and Syntax Support](https://marketplace.visualstudio.com/items?itemName=budparr.language-hugo-vscode)|Syntax highlight for Hugo Templates.|
|[markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)|Lint Markdown files with markdownlint.|
|[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)|Icon theme with Material Design icons.|
|[npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)|Run nom commands and verify installed version of NPM packages.|
|[npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)|Autocomplete npm modules in import statements.|
|[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)|Autocomplete file names.|
|[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)|Format code with Prettier.|
|[ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)|Lint bash and sh files with ShellCheck.|
|[stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)|Lint CSS and Sass files with stylelint.|
|[Transformer](https://marketplace.visualstudio.com/items?itemName=dakara.transformer)|Additional text operations like sorting.|

## Settings

```json
{
  "cSpell.ignoreRegExpList": [
    "string"
  ],
  "cSpell.language": "en,fr",
  "editor.minimap.enabled": false,
  "editor.fontFamily": "'DejaVu Sans Mono', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
  "editor.fontSize": 16,
  "editor.lineHeight": 20,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "extensions.ignoreRecommendations": false,
  "files.trimTrailingWhitespace": true,
  "gitlens.currentLine.enabled": false,
  "gitlens.hovers.currentLine.over": "line",
  "gitlens.codeLens.enabled": false,
  "gitlens.statusBar.enabled": false,
  "gitlens.hovers.enabled": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "telemetry.telemetryLevel": "off",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "workbench.colorTheme": "GitHub Dark",
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
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
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
| Alt+Mouse                   | Open editors split horizontally    |
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

|  Keybinding      | Command                                               |
| ---------------- | ----------------------------------------------------- |
| Ctrl+Space       | Intellisense                                          |
| Ctrl+Shift+Space | Show current completion signature                     |
| Ctrl+Shift+O     | Go to symbol in current file                          |
| Ctrl+T           | Go to symbol in workspace                             |
| Alt+F12 or F12   | Go to definition                                      |
| Ctrl+Shift+F10   | Peek definition                                       |
| Shift+F12        | Go to References                                      |
| Ctrl+G           | Navigate to a specific line in current file           |
| Ctrl+K Ctrl+I    | Show hover at cursor                                  |
| Ctrl+Shift+I     | Format file                                           |
| Shift+Alt+O      | Organize imports                                      |
| F2               | Rename symbol at cursor                               |
| Ctrl+.           | Code actions (refactoring and fixes)                  |
| Shift+Alt+Right  | Expand selection                                      |
| Shift+Alt+Left   | Shrink selection                                      |
| Alt+Click        | Add a cursor                                          |
| Ctrl+Shift+L     | Select all occurrences of the currently selected text |
| Shift+Alt+Mouse  | Box selection                                         |
| Alt+Ctrl+K       | Toggle bookmark                                       |

### Magit Keybindings

|  Keybinding  | Command          |
| ------------ | ---------------- |
| Alt+X G      | Magit status     |
| Alt+X Alt+G  | Magit file popup |
| Alt+X Ctrl+G | Magit dispatch   |
| ?            | Magit help       |

### JavaScript and TypeScript Keybindings

|  Keybinding | Command                                          |
| ----------- | ------------------------------------------------ |
| Ctrl+Alt+R  | JavaScript, TypeScript and React snippets search |

### Markdown Keybindings

|  Keybinding  | Command                         |
| ------------ | ------------------------------- |
| Ctrl+Shift+V | Switch between code and preview |
| Ctrl+K V     | Preview side-by-side            |
