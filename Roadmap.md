With the "1.0" release behind us, now is a good time to look towards the future. We typically look out 6 to 12 months, establish a set of themes we want to work towards, and then schedule work each milestone supporting those themes. VS Code will continue to ship monthly and we'll make progress against each of the following themes during each iteration.

## Improve the Getting Started Experience

It should be quick and natural to customize VS Code to the way you work so that you can quickly get started working on your code.

* Help to configure key bindings, themes, common settings on first run of VS Code
* Ability to create new and populated Workspaces from within VS Code
* [ ] :runner: "Open in VS Code" from a git repository

## Eliminate Adoption Blockers

VS Code is a young product and there still missing features and experiences that you are asking for and that we want to deliver.

* [x] [Tabs](https://github.com/Microsoft/vscode/issues/224)
* [x] [Integrated Terminal](https://github.com/Microsoft/vscode/issues/143)
* [x] [Move error list from Quick Box to a panel](https://github.com/Microsoft/vscode/issues/6679)
* [x] [Indent guides](https://github.com/Microsoft/vscode/issues/2192)
* [x] Global Replace
* [ ] :runner: [Support for VIM style key bindings](https://github.com/Microsoft/vscode/issues/3600)
* [ ] :runner: Temp file storage when editor is closed 
* Multiple folders inside a single workspace
* [ ] :runner: Editor layout (e.g. horizontal split)
* [x] Search performance improvements file list/contents
* [ ] :runner: Workbench theming, e.g.,[support icons in explorer](https://github.com/Microsoft/vscode/issues/211)
* [Accessibility](https://github.com/Microsoft/vscode/issues/6583) 
* [ ] Improved settings and configuration experiences

## Improved Extension creation, discovery and management

We want to make it easy for developers to create extensions and for users to discover extensions. And, once you have discovered a set of extensions, we want to make it easy for you to manage them.

* [x] [In product extension management experience](https://github.com/Microsoft/vscode/issues/637)
* [ ] Improved extension recommendation experience
* [ ] :runner: Support for disabling an extensions vs. uninstall
* [X] Update all extensions and keep all extensisons up-to-date actions
* [ ] :runner: Support for "extension packs”, collections of extensions and settings
* [x] Improved documentation for [language based extensions](http://code.visualstudio.com/docs/extensions/language-support)
* Improve the [Marketplace](https://marketplace.visualstudio.com/vscode) experience for discovering and installing extensions

For extension developers:

* SDK: Improve extension README authoring and quality
* Expand the core VS Code extensibility APIs
 - [x] Menu contributions
 - [x] File Icon sets
 - [ ] :runner: Support for extensions to programmatically update settings files
* Expand the diagnostics experience and API to support additional debugging scenario requirements, such as
 - [x] [attach to process](https://github.com/Microsoft/vscode/issues/6569)

Monaco Editor
- [x] We will also make it easy to [consume and ship the core code editor ("Monaco")](https://github.com/Microsoft/vscode/issues/446) as a library.

## TypeScript, JavaScript, and Node development

We will continue to improve our code editing and navigation experiences by partnering with the TypeScript team on the Salsa language service. We will also continue to enhance our end-to-end debugging experiences for Node applications.

* Work with the TypeScript team on the JavaScript language service which powers our JavaScript and TypeScript editing experiences to:

  * [ ] :runner: Suggest imports of .d.ts files to enable IntelliSense "out of the box"
  * Angular IntelliSense
  * [ ] Suggest project configuration files (`jsconfig.json`, `tsconfig.json`)
  * [ ] Show errors for the entire project and not only the file that is currently edited.

* [x] Node Debugger: Step over uninteresting (generated) code
* Improved npm support and help to keep the `package.json` consistent with the installed node modules

## Engineering Items

We will continue to improve the engineering of VS Code itself and add items as needed:
* Improve crash logging
* Improve crash diagnostics (e.g. client side log).

## Summary

These are examples of just some of the work we will be focusing on in the next 6 to 12 months. We will provide much more detail in each of our [monthly iteration plans](https://github.com/Microsoft/vscode/wiki/Iteration-Plans) so follow along and let us know what you think!
