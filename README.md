<image>

## SubSeven Theme for Firefox

A throwback theme with the color scheme of [SubSeven](https://darknetdiaries.com/episode/20/), the screen-flipping, CD tray-popping scourge of AOLers in the early 2000s.

Currently just a color scheme in the `manifest.json` file, but could expand to add CSS down the road.

## Contributing

> 🪝 Save cycle time by using this repo's [pre-commit](https://pre-commit.com/) hooks: `pre-commit install`

New to firefox extension/theme development like I was? These are good resources to get started:

- [Theme creation basics](https://extensionworkshop.com/documentation/themes/) - start here
- Developer docs on [manifest.json](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json), particularly the [theme](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/theme) section
- [Firefox extension .xpi file structure: description, contents, creation, and installation](https://stackoverflow.com/questions/30865644/firefox-extension-xpi-file-structure-description-contents-creation-and-inst/31043045#31043045)
- [Getting started with web-ext](https://extensionworkshop.com/documentation/develop/getting-started-with-web-ext/) - cli tool designed to speed up various parts of the extension development process

The release and beta versions of Firefox don't allow installation of unsigned add-ons. To test changes locally, you'll need to run one of the other builds, such as [developer edition](https://www.mozilla.org/en-US/firefox/developer/) or [nightly](https://www.mozilla.org/en-US/firefox/112.0a1/releasenotes/), and set `xpinstall.signatures.required = false` in `about:config`.
