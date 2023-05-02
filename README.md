# VS Code Setup

My personal VS Code setup.

## Extensions

- [Astro](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode) : Support for Astro.
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks): Mark and jump to bookmarks.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker): Spell checker with programming languages awareness.
  - [French - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-french): French Dictionary for Code Spell Checker.
- [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug): Debug with Firefox from VS Code.
- [ES7 React/Redux/React-Native/JS snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets): Snippets for React.
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Lint JavaScript files with ESLint.
- [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme): GitHub theme.
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one): Improvements for Markdown support.
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint): Lint Markdown files with markdownlint.
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme): Icon theme with Material Design icons.
- [MDX](https://marketplace.visualstudio.com/items?itemName=unifiedjs.vscode-mdx): Support for MDX.
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense): Autocomplete npm modules in import statements.
- [Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff): Diff selections of text.
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense): Autocomplete file names.
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Format code with Prettier.
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager): Switch quickly between projects.
- [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck): Lint bash and sh files with ShellCheck.
- [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint): Lint CSS and Sass files with stylelint.
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree): Tree view of TODOs in workspace.
- [Transformer](https://marketplace.visualstudio.com/items?itemName=dakara.transformer): Additional text operations like sorting.
- [WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl): WSL support.
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml): Integration with Windows Subsystem for Linux (WSL).

## Settings

```json
{
  "cSpell.ignoreRegExpList": ["/\\w+([0-9]+\\w*)+/"],
  "cSpell.language": "en,fr",
  "cSpell.enableFiletypes": ["!json", "!mjs", "!cjs"],
  "diffEditor.renderSideBySide": false,
  "editor.minimap.enabled": false,
  "editor.fontFamily": "'DejaVu Sans Mono', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
  "editor.fontSize": 16,
  "editor.lineHeight": 20,
  "editor.guides.bracketPairs": true,
  "extensions.ignoreRecommendations": false,
  "files.trimTrailingWhitespace": true,
  "git.closeDiffOnOperation": true,
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
  "[mdx]": {
    "editor.wordWrap": "on"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "editor.linkedEditing": true,
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "todo-tree.general.tags": ["TODO", "NEXT", "STARTED", "WAIT", "DONE"],
  "todo-tree.highlights.defaultHighlight": {
    "fontWeight": "bold"
  },
  "todo-tree.highlights.customHighlight": {
    "TODO": {
      "foreground": "#bc4c00"
    },
    "NEXT": {
      "foreground": "#0969da"
    },
    "STARTED": {
      "foreground": "#8250df"
    },
    "WAIT": {
      "foreground": "#57606a"
    },
    "DONE": {
      "foreground": "#1a7f37"
    }
  },
  "projectManager.git.baseFolders": ["C:\\dev"],
  "projectManager.git.ignoredFolders": ["node_modules", "archives"],
  "redhat.telemetry.enabled": false,
  "bookmarks.keepBookmarksOnLineDelete": true
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
    "key": "tab",
    "command": "editor.toggleFold",
    "when": "editorLangId == 'markdown' && editorTextFocus && foldingEnabled"
  },
  {
    "key": "ctrl+k ctrl+l",
    "command": "-editor.toggleFold",
    "when": "editorTextFocus && foldingEnabled"
  },
  {
    "key": "ctrl+shift+alt+p",
    "command": "projectManager.listProjectsNewWindow"
  }
]
```

### Views and Commands

| Keybinding   | Command             |
| ------------ | ------------------- |
| Ctrl+Shift+P | Command Palette     |
| Ctrl+,       | Settings            |
| Ctrl+Shift+E | Explorer view       |
| Ctrl+Shift+G | Source control view |
| Ctrl+`       | Terminal panel      |

### Files and Navigation

| Keybinding                 | Command                                                                  |
| -------------------------- | ------------------------------------------------------------------------ |
| Ctrl+R                     | Open recent folders or files                                             |
| Shift+Alt+P                | Open a project (Project Manager extension)                               |
| Ctrl+P                     | Open a file by name                                                      |
| Ctrl+Tab or Ctrl+Shift+Tab | Select next or previous file in a list of opened files                   |
| Alt+Right or Alt+Left      | Go to next or previous edit location                                     |
| F12 or Ctrl+Click          | Go to the definition of a symbol                                         |
| Alt+F12                    | Peek definition of symbol                                                |
| Ctrl+F12                   | Go to implementation of a symbol                                         |
| Ctrl+Shift+O               | Go to a symbol in the current file by name (type : to group by category) |
| Ctrl+T                     | Go to a symbol in a file of the project by name                          |
| Shift+Alt+F12              | Find references                                                          |
| F8 or Shift+F8             | Go to next or previous problem                                           |
| Ctrl+Up or Ctrl+Down       | Scroll line up or down                                                   |

### Edition

| Keybinding                        | Command                                                                          |
| --------------------------------- | -------------------------------------------------------------------------------- |
| Ctrl+.                            | Quick fix and refactoring for the current problem                                |
| F2                                | Rename symbol                                                                    |
| Ctrl+Shift+Alt+(arrow key)        | Column (box) selection                                                           |
| Shift+Alt+Right or Shift+Alt+Left | Expand or shrink current selection                                               |
| Alt+Up or Alt+Down                | Move line up or down                                                             |
| Ctrl+Shift+K                      | Delete line                                                                      |
| Ctrl+Enter or Ctrl+Shift+Enter    | Insert line below or above                                                       |
| Ctrl+Space                        | Intellisense                                                                     |
| Shift+Alt+F                       | Format file                                                                      |
| Alt+Click                         | Add a cursor to the multiple cursors                                             |
| Ctrl+Alt+Down                     | Add cursor below to the multiple cursors                                         |
| Ctrl+Alt+Up                       | Add cursor above to the multiple cursors                                         |
| Ctrl+Alt+.                        | Add word to code spell checker workspace settings (Code Spell Checker extension) |

### Search

| Keybinding   | Command                                                              |
| ------------ | -------------------------------------------------------------------- |
| Ctrl+F       | Search in current editor (navigate results with Enter & Shift+Enter) |
| F3           | Go to next search result                                             |
| Shift+F3     | Go to previous search result                                         |
| Ctrl+H       | Replace in current editor                                            |
| Ctrl+Shift+F | Search all files in current folder                                   |

### Bookmarks

| Keybinding | Command                   |
| ---------- | ------------------------- |
| Ctrl+Alt+K | Toggle bookmark           |
| Ctrl+Alt+I | Toggle labeled bookmark   |
| Ctrl+Alt+L | Jump to next bookmark     |
| Ctrl+Alt+J | Jump to previous bookmark |
| Ctrl+Alt+O | List bookmarks            |
| Ctrl+Alt+U | List from all files       |

### Markdown

| Keybinding   | Command                                    |
| ------------ | ------------------------------------------ |
| Ctrl+Shift+V | Switch between Markdown editor and preview |
| Ctrl+K V     | Open preview on the side                   |
| Alt+Shift+F  | Format Markdown table                      |
| Tab          | Toggle fold of the current region          |
| Ctrl+B       | Toggle bold                                |
| Ctrl+I       | Toggle italic                              |
