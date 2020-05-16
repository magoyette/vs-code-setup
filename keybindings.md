# Keybindings

## Navigation Keybindings

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

## Views Keybindings

|  Keybinding    | Command             |
| -------------- | ------------------- |
| Ctrl+B         | Toggle sidebar      |
| Ctrl+Shift+G G | Source Control view |

## Code Keybindings

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

## JavaScript and TypeScript Keybindings

|  Keybinding | Command                                          |
| ----------- | ------------------------------------------------ |
| Ctrl+Alt+R  | JavaScript, TypeScript and React snippets search |

## Markdown Keybindings

|  Keybinding  | Command                         |
| ------------ | ------------------------------- |
| Ctrl+Shift+V | Switch between code and preview |
| Ctrl+K V     | Preview side-by-side            |

## Calva Keybindings

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

### Paredit Deletion Keybindings

|  Keybinding   | Command                                           |
| ------------- | ------------------------------------------------- |
| Backspace     | Delete 1 char backward without unbalancing a form |
| Delete        | Delete 1 char forward without unbalancing a form  |
| Alt+Backspace | Delete 1 char backward                            |
| Alt+Delete    | Delete 1 char forward                             |

### Paredit Selection Keybindings

|  Keybinding  | Command          |
| ------------ | ---------------- |
| Ctrl+W       | Expand selection |
| Ctrl+Shift+W | Shrink selection |

### Paredit Edition Keybindings

|  Keybinding      | Command                            |
| ---------------- | ---------------------------------- |
| Ctrl+Right       | Slurp forward the closing bracket  |
| Ctrl+Left        | Barf forward the closing bracket   |
| Ctrl+Shift+Left  | Slurp backward the opening bracket |
| Ctrl+Shift+Right | Slurp forward the opening bracked  |
