# lookup-package

Lists all installed npm packages in the current project and makes them easily searchable with the combination of [fzf](https://github.com/junegunn/fzf) and the search engine [njt](https://njt.vercel.app/).

![](demo.gif)

# Dependencies

These tools **must** be installed to use this script:

- [fzf](https://github.com/junegunn/fzf) - command-line fuzzy finder
- [jq](https://github.com/stedolan/jq) - lightweight and flexible command-line JSON processor
- [npm](https://github.com/npm/cli) - node package manager

# Install

## Download

    curl -OL https://github.com/fools-mate/lookup-package/raw/main/lookup-package

## Make it executable

    chmod +x lookup-package

## Copy to somewhere in your path. E.g.:

    sudo mv lookup-package /usr/local/bin/
