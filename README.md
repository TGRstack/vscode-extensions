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

### 2.3.0 -  Last release of 2019

- replacing "extensionDependencies" w/ "extensionPack" option
- hopefully ms-vscode's tslint is stable now
- check [this diff](https://github.com/TGRstack/vscode-extensions/commit/24eb1d31bae10a42e72a3476194b7c2536defcb9#diff-b9cfc7f2cdf78a7f4b91a753d10865a2) for all the extension changes

### 2.2.0 -  Replaces MS.Tslint 1.0.0 which is broken back to `eg2.tslint`

- removes `ms-vscode.vscode-typescript-tslint-plugin`

### 2.0.0

- the tslint package has been deprecated and needs to be replaced with microsoft's
- added a number of other nice to have packages like `glean`!

## Includes

- `2gua.rainbow-brackets`
- `aaron-bond.better-comments`
- `AlanWalk.markdown-toc`
- `anseki.vscode-color`
- `apollographql.vscode-apollo`
- `bierner.emojisense`
- `bierner.markdown-emoji`
- `chrisdias.vscode-opennewinstance`
- `christian-kohler.npm-intellisense`
- `christian-kohler.path-intellisense`
- `chrmarti.regex`
- `codemooseus.vscode-devtools-for-chrome`
- `cstechnologies.vscode-jest-runner`
- `DavidAnson.vscode-markdownlint`
- `dbaeumer.vscode-eslint`
- `drKnoxy.eslint-disable-snippets`
- `eamodio.gitlens`
- `edwardhjp.vscode-author-generator`
- `eg2.vscode-npm-script`
- `enochc.copy-relative-path`
- `ephoton.indent-switcher`
- `euskadi31.json-pretty-printer`
- `fabiodam.vscode-console-wrapper`
- `felipecaputo.git-project-manager`
- `fknop.vscode-npm`
- `ginfuru.ginfuru-vscode-jekyll-syntax`
- `GitHub.vscode-pull-request-github`
- `idleberg.hopscotch`
- `ifaxity.onedark`
- `JakeWilson.vscode-placeholder-images`
- `jkjustjoshing.vscode-text-pastry`
- `jmarzka.open-folder-in-new-instance`
- `joelday.docthis`
- `johnpapa.vscode-peacock`
- `joshpeng.theme-onedark-sublime`
- `karigari.chat`
- `kevinkyang.auto-comment-blocks`
- `kisstkondoros.vscode-codemetrics`
- `kogai.regex-railroad-diagrams`
- `kumar-harsh.graphql-for-vscode`
- `Liangqin.quick-notes`
- `lihui.vs-color-picker`
- `lukapetrovic.image-resizer`
- `mauve.terraform`
- `mechatroner.rainbow-csv`
- `medzhidov.hex-rgba-converter`
- `mezzalab.vscode-annotations`
- `mike-co.import-sorter`
- `mikestead.dotenv`
- `mohsen1.react-javascript-to-typescript-transform-vscode`
- `mrmlnc.vscode-duplicate`
- `mrmlnc.vscode-json5`
- `ms-vscode.vscode-typescript-tslint-plugin`
- `msjsdiag.debugger-for-chrome`
- `msjsdiag.vscode-react-native`
- `naumovs.color-highlight`
- `oderwat.indent-rainbow`
- `OfHumanBondage.react-proptypes-intellisense`
- `oliversturm.fix-json`
- `paulmolluzzo.convert-css-in-js`
- `PKief.material-icon-theme`
- `qinjia.seti-icons`
- `quicktype.quicktype`
- `sgtsquiggs.vscode-active-file-status`
- `shardulm94.trailing-spaces`
- `SimonSiefke.svg-preview`
- `steoates.autoimport`
- `stevencl.addDocComments`
- `stuart.unique-window-colors`
- `tberman.json-schema-validator`
- `tgrstack.tgr-extension-pack`
- `tgrstack.tgr-snippet-pack`
- `tnaseem.theme-seti`
- `Tyriar.sort-lines`
- `vtfn.stylint`
- `waderyan.gitblame`
- `wayou.vscode-todo-highlight`
- `wix.glean`
- `wix.stylable-intelligence`
- `wix.vscode-import-cost`
- `YoshinoriN.current-file-path`
- `yzhang.markdown-all-in-one`
- `ZainChen.json`

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
