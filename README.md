# Clean Dark & Light By Birdlinux

![Clean Dark](https://media.discordapp.net/attachments/884940359279456276/885358784522911795/7e50af2978561b72ee51ae9042f44d90.jpg)

## Install

1. Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=Clean-Dark.clean-dark).
2. Click on the "Install" button.
3. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme). Avaible Themes:
    - [Clean Dark](https://github.com/0x81RD/Clean-Dark)
    - [Clean Light](https://github.com/0x81RD/Clean-Light)
    - `More coming soon...`
## Publish (internal)

> Note: Publishing a new version of this theme is only meant for maintainers.

**Prerequisite**: Please follow this [guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) to install and login to `vsce`. Ask an existing maintainer how to get the "Personal Access Token".

1. Merge any PR that is ready to be published into `master`.
2. Run `npm run build` to generate the themes with the new changes.
3. Update [CHANGELOG.md](https://github.com/primer/github-vscode-theme/blob/master/CHANGELOG.md) + commit the changes.
4. Run `vsce publish [version]`. Follow the [SemVer](https://semver.org) convention and replace `[version]` with one of the following  options:
    - `patch` for bug fixes
    - `minor` for improvements
    - `major` for breaking or bigger changes
5. Push the commits and make a [new release](https://github.com/primer/github-vscode-theme/releases/new).
