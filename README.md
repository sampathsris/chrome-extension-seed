# `chrome-extension-seed`

A seed repository to build a [Chrome Extension](https://developer.chrome.com/docs/extensions/mv3/) compatible with [Manifest version 3.0](https://developer.chrome.com/docs/extensions/mv3/intro/).


## How to Start

1. Fork the repo, or,

    ```
    git clone https://github.com/sampathsris/chrome-extension-seed.git your-repo
    cd your-repo/
    git remote set-url origin <your repo url>
    git branch -M main
    git push origin main
    git push --all
    ```

    Really, just fork!
2. Change the `package.json` and `src/mannifest.json` to your liking. This includes chaging names, descriptions, version numbers, and the license field.
    - If necessary, change the `LICENSE` file as well.
3. Start editing the content of the `src` directory to add functionality to your extension.


## Updating

First, make sure your changes are committed in your own repo.

```
git fetch upstream
git merge upstream/main
```


## Attributions

[Extension icons created by Royyan Wijaya - Flaticon](https://www.flaticon.com/free-icons/extension).
