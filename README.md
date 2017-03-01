# Awesome VS Code
Some changes to make VS Code Awesome

## Setup CLI usage
1. `cmd + shift + p` in VSCode and look for `Install code command in PATH` (This allow us to open a file in terminal using the `code` command)
2. `git config --global core.editor "code -n -w"` in terminal after doing `1.`, that will set VSCode as the default editor for Git commands.
3. On iTerm2, go to **Profiles > Default > Advanced > Semantic History**, select **Run command** from the list, then add `/usr/local/bin/code -g \1:\2`, this will allow you to `cmd + click` on a file:line on a stack trace and open it on VSCode

## Settings
`cmd + ,` to display VSCode settings. Default settings will show in the left, your custom settings will show in the right.
Just copy the desired changes from `vscode_settings.json` into your custom settings.