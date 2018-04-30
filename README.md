[![Version](https://vsmarketplacebadge.apphb.com/version/mischah.relaxed-theme.svg)](https://marketplace.visualstudio.com/items?itemName=mischah.relaxed-theme)

# Relaxed Theme for Visual Studio Code

> A relaxed VS Code theme to take a more relaxed view of things.

![Screenshot: JSX](https://gitcdn.xyz/repo/Relaxed-Theme/vscode-theme-relaxed/master/images/screenshot-jsx.png)

<details>
  <summary>Screenshot: Sass</summary>
  <p>&nbsp;</p)>
  <img src="https://gitcdn.xyz/repo/Relaxed-Theme/vscode-theme-relaxed/master/images/screenshot-sass.png" alt="Screenshot: Sass">
</details>

<details>
  <summary>Screenshot: HTML</summary>
  <p>&nbsp;</p)>
  <img src="https://gitcdn.xyz/repo/Relaxed-Theme/vscode-theme-relaxed/master/images/screenshot-html.png" alt="Screenshot: HTML">
</details>

## Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Relaxed`
3. Click **Install** to install it.
4. Click **Reload** to reload the your editor
5. Code > Preferences > Color Theme > **Relaxed**

## I don't like something

First, this theme is new so if something is funky, please open an issue.

These are the things we have control over. If you would like to change something, you can either open a PR and see if I'd like it added, or override the colours in your own settings.json file.

<https://code.visualstudio.com/docs/getstarted/theme-color-reference>

### Contributing

#### Get up and running straight away

* Fork, Clone and open this repository in VS Code
* Press `F5` (Debug > Start Debugging )to open a new window with your extension loaded.
* Open `File > Preferences > Color Themes` and pick the »Relaxed« color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Inspect TM Scopes` command from the Commmand Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) .

#### Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.
* When editing workbench colors, it's easiest to test the colors in the settings under `workbench.colorCustomizations` and `workbench.tokenColorCustomizations`. When done, run the `Generate Color Theme From Current Settings` command to generate an updated content for the color theme definition file.

#### Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [theme](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers#_adding-a-new-color-theme) documentation.

#### Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.

## Related

* [Relaxed-Terminal](https://github.com/Relaxed-Theme/Relaxed-Terminal) - A relaxed terminal theme. For iTerm, Hyper, the macOS Terminal and a bunch of others.

## License

Please be aware of the licenses of the components we use in this project.
Everything else that has been developed by the contributions to this project is under [MIT License](LICENSE).
