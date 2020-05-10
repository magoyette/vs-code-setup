# VS Code Setup

My personal VS Code setup.

For now, it has only been tested with Linux.

## Dependencies

[jq](https://stedolan.github.io/jq/) must be available from the Linux path.
jq is used to merge the JSON settings.

## Installing the extensions

`install-extensions` is a script that install the extensions listed in
the file `extensions`.

``` shell
chmod a+x install-extensions
./install-extensions
```

## Refreshing the list of extensions

The script `save-extensions` will save a list of the extensions currently
installed in the `extensions` file.

``` shell
chmod a+x save-extensions
./save-extensions
```

## Applying the settings on VS Code

`apply-settings` will merge the settings of this repository with the settings
of VS Code (stored in `~/.config/Code/User/settings.json`).

## Retrieve the settings from VS Code

`save-settings` will retrieve the settings of VS Code (stored in
`~/.config/Code/User/settings.json`) and save them in this repository.

## Extensions

| Extension | Description |
| --------- | ----------- |
| [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) | Mark and jump to bookmarks. |
| [Calva](https://marketplace.visualstudio.com/items?itemName=betterthantomorrow.calva) | Clojure and ClojureScript support. |
| [clj-kondo](https://marketplace.visualstudio.com/items?itemName=borkdude.clj-kondo) | Lint Clojure and ClojureScript files with clj-kondo. |
| [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) | Debug with Chrome from VS Code. |
| [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug) | Debug with Firefox from VS Code. |
| [ES7 React/Redux/React-Native/JS snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) | Snippets for React. |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | Lint JavaScript files with ESLint. |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | Improves Git History and Git Blame support in VS Code. |
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) | Icon theme with Material Design icons. |
| [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) | Lint Markdown files with markdownlint. |
| [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) | Run nom commands and verify installed version of NPM packages. |
| [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) | Autocomplete npm modules in import statements. |
| [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | Autocomplete file names. |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | Format code with Prettier. |
| [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) | Quick access to switch between projects. |
| [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck) | Lint bash and sh files with ShellCheck. |
| [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint) | Lint CSS and Sass files with stylelint. |

## Keybindings

See the [Keybindings](keybindings.md).