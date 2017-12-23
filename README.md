# VS Code Setup

My personal VS Code setup.

For now, it has only been tested with Linux.

Backward compatibility will be broken often, so it's probably better to copy
snippets from this repository than to fork it.

## Cloning the repository

The following commands remove all existing VS Code user settings
and replace them with the settings of the `vs-code-setup` repository.

```shell
rm -drf ~/.config/Code/User
git clone https://github.com/magoyette/vs-code-setup.git ~/.config/Code/User
```

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
