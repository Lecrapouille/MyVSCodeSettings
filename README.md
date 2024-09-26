# Visual Studio Code Plugins

# List installed plugins

```
code --list-extensions
```

Instal plugins from a given file:

```
for i in `cat plugins.txt`; do code --install-extension $i; done
```

Install / uninstal:

```
code --install-extension ms-vscode.cpptools
code --uninstall-extension ms-vscode.cpptools
```
