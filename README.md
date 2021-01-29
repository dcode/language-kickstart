# language-kickstart

This is a conversion of an Atom language file for Red Hat [kickstart](https://github.com/pykickstart/pykickstart/blob/master/docs/kickstart-docs.rst) files.

This was originally converted from [wgwoods](https://github.com/wgwoods/language-kickstart) kickstart language support

## Features

- highlighting of known commands and valid %package symbols
- %pre/%post scriptlets highlighted according to their --interpreter
- catches invalid password hashes and missing section %end
- intellisense auto-completion


## Release Notes

Users appreciate release notes as you update your extension.

### 0.0.1

Initial release of language-kickstart. If it breaks, you get to keep all the pieces. Sorry.


----

## Manual Installation

I'm not sure how difficult this will be to get published and updated to the vsc package repository, so for now you can clone this repo into your vscode extension folder.

```bash
mkdir -p ${HOME}/.vscode/extensions
cd ${HOME}/.vscode/extensions
git clone --depth=1 https://github.com/dcode/language-kickstart.git
```

Then reload vscode.
