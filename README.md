# My VS Code Theme

My Custom VSCode Theme inspired by Dalton Menezes' [Aura Theme](https://github.com/daltonmenezes/aura-theme)
and CodingPhase's [VS Code Style](https://github.com/codingphasedotcom/codingphase-style-vs-code).

### Sample Screenshot

![Sample](sample.png)

### How to use

1. Open up a Terminal
2. Install vsce package

   `npm install -g vsce`

3. Package the theme

   `vsce package`

4. Install the theme

   `code --install-extension [name_of_packaged_theme].vsix`

   Example:

   `code --install-extension my-vscode-theme-0.0.1.vsix`
