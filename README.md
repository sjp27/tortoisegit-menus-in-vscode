# TortoiseGit Command Menus

This [VISUAL STUDIO CODE extension](https://marketplace.visualstudio.com/items?itemName=sjp27.tortoisegit-menus-in-vscode) adds menus in right-click menu of sidebar File-Explorer, to execute TortoiseGit commands. *(This is an absolutely ligthweight extension without including dependencies or binary files, instead a small plain `.js` file, which is just a wrapper to pass commands to TotroiseGit)*

Most commonly used [tortoise-git commands](https://tortoisegit.org/docs/tortoisegit/tgit-automation.html) are supported by this extension.


## Build

Run `npm i` and then `vsce package` (you need to have vsce installed by `npm install -g vsce`) and it produces .vsix package.

## Release Notes

### 1.0.0

Initial release.