# Synthwave Theme

## Download

1. Download the vsix file <a href="https://brendanbeck.com/synthwave-theme">HERE</a> and place in the vscode extensions directory:
    - Windows `%USERPROFILE%\.vscode\extensions`
    - macOS and Linux `~/.vscode/extensions`
2. In vscode, go to the extensions tab on the side bar, and click the 3 dots
3. At the bottom of the menu, select `Install from VSIX`
4. Navigate to your vscode extensions directory, and select `Synthwave-Theme.vsix`
5. If it does not immedietely change your theme, select the extension and click "Set Color Theme", then hit enter

## Colors
 - Magenta: #fc4384
 - Orange: #ff8b56
 - Dark Grey: #646464
 - Light Grey: adadad#
 - Light Blue: #97f8ff
 - Red: #ff3957
 - Purple: #b973fa
 - Green: #04f54d


## Resources
#### List of all VSCode tokens:</br>
https://gist.github.com/lol-russo/1c7a0b958be4b9434c5a120f24d5e7c3

#### Command to view a specific token in VSCode:</br>
`Developer: Inspect Editor Tokens and Scopes`

## How to create Theme
1. Edit the json in /themes
2. run `vsce package`
3. cp synthwave-0.0.1.vsix ~/.vscode/extensions/
4. in vs code, uninstall extension and re-compile
