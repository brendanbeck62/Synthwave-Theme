# vscode-theme

## How To Use
1. Clone the repo, and place `synthwave-0.0.1.vsix` into the vscode extensions directory:
    - Windows %USERPROFILE%\.vscode\extensions
    - macOS ~/.vscode/extensions
    - Linux ~/.vscode/extensions
2. In vscode, go to the extensions tab on the side bar, and click the 3 dots
3. At the bottom of the menu, select `Install from VSIX`
4. Navigate to your vscode extensions directory, and select `synthwave-0.0.1.vsix`
5. If it does not immedietely change your theme, select the extension and click "Set Color Theme", then hit enter


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
