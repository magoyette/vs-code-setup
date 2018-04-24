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
of VS Code (stored in ~/.config/Code/User/settings.json).

## Retrieve the settings from VS Code

`save-settings` will retrieve the settings of VS Code (stored in
~/.config/Code/User/settings.json) and save them in this repository.
