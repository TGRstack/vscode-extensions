# TGRStack.com Extension Pack

A collection of extensions recommended by the author of TGRStack.com .

## Install

```ext install tgrstack.tgr-extension-pack```

Alternatively you can open the extensions panel and search for 'TGRStack extension'.

## Want to see your extension added?

Open a PR and I'd be happy to take a look.

https://github.com/TGRstack/vscode-extensions

**Enjoy!**

## RELEASE NOTES

### 2.2.0 -  Replaces MS.Tslint 1.0.0 which is broken back to `eg2.tslint`

- removes `ms-vscode.vscode-typescript-tslint-plugin`

### 2.0.0

- the tslint package has been deprecated and needs to be replaced with microsoft's
- added a number of other nice to have packages like `glean`!


## Includes

- `tgr-snippet-pack`
- `2gua.rainbow-brackets`
- `AlanWalk.markdown-toc`
- `anseki.vscode-color`
- `bierner.emojisense`
- `chrisdias.vscode-opennewinstance`
- `christian-kohler.npm-intellisense`
- `christian-kohler.path-intellisense`
- `chrmarti.regex`
- `cstechnologies.vscode-jest-runner`
- `DavidAnson.vscode-markdownlint`
- `edwardhjp.vscode-author-generator`
- `eg2.vscode-npm-script`
- `eg2.tslint`
- `enochc.copy-relative-path`
- `ephoton.indent-switcher`
- `fabiodam.vscode-console-wrapper`
- `fknop.vscode-npm`
- `ginfuru.ginfuru-vscode-jekyll-syntax`
- `idleberg.hopscotch`
- `ifaxity.onedark`
- `jkjustjoshing.vscode-text-pastry`
- `jmarzka.open-folder-in-new-instance`
- `joelday.docthis`
- `joshpeng.theme-onedark-sublime`
- `karigari.chat`
- `kisstkondoros.vscode-codemetrics`
- `kogai.regex-railroad-diagrams`
- `kumar-harsh.graphql-for-vscode`
- `lihui.vs-color-picker`
- `lukapetrovic.image-resizer`
- `mauve.terraform`
- `mechatroner.rainbow-csv`
- `mezzalab.vscode-annotations`
- `mike-co.import-sorter`
- `mikestead.dotenv`
- `mrmlnc.vscode-apache`
- `mrmlnc.vscode-duplicate`
- `mrmlnc.vscode-json5`
- `ms-vscode.node-debug2`
- `ms-vscode.Theme-MarkdownKit`
- `ms-vsliveshare.vsliveshare-audio`
- `ms-vsliveshare.vsliveshare-pack`
- `ms-vsliveshare.vsliveshare`
- `msjsdiag.debugger-for-chrome`
- `naumovs.color-highlight`
- `oderwat.indent-rainbow`
- `PeterJausovec.vscode-docker`
- `PKief.material-icon-theme`
- `qinjia.seti-icons`
- `sgtsquiggs.vscode-active-file-status`
- `shardulm94.trailing-spaces`
- `steoates.autoimport`
- `stevencl.addDocComments`
- `stuart.unique-window-colors`
- `tberman.json-schema-validator`
- `tgrstack.tgr-extension-pack`
- `tgrstack.tgr-snippet-pack`
- `tnaseem.theme-seti`
- `Tyriar.sort-lines`
- `vsmobile.vscode-react-native`
- `vtfn.stylint`
- `wayou.vscode-todo-highlight`
- `wix.glean`
- `wix.vscode-import-cost`
- `yzhang.markdown-all-in-one`

<!--
## Extensions Included

* [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) - Run npm scripts from the command palatte and validate the installed modules defined in `package.json`.
* [Search node_modules](https://marketplace.visualstudio.com/items?itemName=jasonnutter.search-node-modules) - Quickly search for node modules in your project. 
* [NPM IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - Adds IntelliSense for npm modules in your code. 
* [Path IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Autocompletes filenames in your code. 
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) - Adds real-time collaborative editing and debugging into VS Code. -->

## Publishing Instructions

mainly a reminder to myself for how to publish to MS.

```bash
# login to MS and create a new PAT
#   https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops#create-personal-access-tokens-to-authenticate-access
$ vsce login <publisher> # case sensitive
$ vsce publish
```
