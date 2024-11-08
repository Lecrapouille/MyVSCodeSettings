# Visual Studio Code Plugins

## Installation

- Install https://code.visualstudio.com/ or https://www.cursor.com/
- Copy the folder `vscode` as `.vscode` at your project root folder.

## List installed extensions

```
code --list-extensions
```

Install extensions from a given file:

```
for i in `cat extensions.txt`; do code --install-extension $i; done
```

Install / uninstal:

```
code --install-extension ms-vscode.cpptools
code --uninstall-extension ms-vscode.cpptools
```

## Folder .vscode for my personal project

Populate the compile_commands.json

```
bear --output .vscode/compile_commands.json -- make -j8
```

See: https://medium.com/@pranjalchanda08/sonarlint-for-c-c-with-makefile-support-on-vs-code-20b2021dec2

To install bear:

```
sudo apt-get install bear
```
