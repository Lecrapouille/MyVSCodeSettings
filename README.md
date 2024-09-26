# Visual Studio Code Plugins

## List installed plugins

```
code --list-extensions
```

Install plugins from a given file:

```
for i in `cat plugins.txt`; do code --install-extension $i; done
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
