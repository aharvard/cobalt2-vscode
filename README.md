# Cobalt2 Theme for VS Code

[![Version](https://vsmarketplacebadge.apphb.com/version/wesbos.theme-cobalt2.svg)](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2)

![Preview](https://raw.githubusercontent.com/wesbos/cobalt2-vscode/cobalt2-updates/images/ss.png)


# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Cobalt2` - find the one by **Wes Bos** - there are a few other half-baked ones so make sure you have the right one!
3. Click **Install** to install it.
4. Code > Preferences > Color Theme > **Cobalt2**
5. Optional: Use the recommended settings below for best experience

## Recommended Settings

```js
{
  // This is all that matters
  "workbench.colorTheme": "Cobalt2",
  // The Cursive font is operator Mono, it's $200 and you need to buy it to get the cursive. Dank Mono or Victor Mono are good alternatives 
  "editor.fontFamily": "Operator Mono, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontSize": 17,
  "editor.lineHeight": 25,
  "editor.letterSpacing": 0.5,
  "files.trimTrailingWhitespace": true,
  "editor.fontWeight": "400",
  "prettier.eslintIntegration": true,
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "solid",
  "editor.renderWhitespace": "all",
}
```
## Colours

| Name            | Hex       |   |
|-----------------|-----------|---|
| Blue            | `#193549` |<img alt="Blue swatch" src="https://placehold.jp/24/193549/fff/20x20.png?text=%20">|
| Blue Highlight  | `#1F4662` |<img alt="Blue Highlight swatch" src="https://placehold.jp/24/1F4662/fff/20x20.png?text=%20">|
| Blue Highlight2 | `#234E6D` |<img alt="Blue Highlight2 swatch" src="https://placehold.jp/24/234E6D/fff/20x20.png?text=%20">|
| Blue Dark       | `#122738` |<img alt="Blue Dark swatch" src="https://placehold.jp/24/122738/fff/20x20.png?text=%20">|
| Yellow          | `#ffc600` |<img alt="Yellow swatch" src="https://placehold.jp/24/ffc600/fff/20x20.png?text=%20">| 
| Hot Pink        | `#ff0088` |<img alt="Hot Pink swatch" src="https://placehold.jp/24/ff0088/fff/20x20.png?text=%20">| 
| Blush Pink      | `#ff628c` |<img alt="Hot Pink swatch" src="https://placehold.jp/24/ff628c/fff/20x20.png?text=%20">|
| Orange          | `#ff9d00` |<img alt="Orange swatch" src="https://placehold.jp/24/ff9d00/fff/20x20.png?text=%20">|
| Green           | `#3ad900` |<img alt="Green swatch" src="https://placehold.jp/24/3ad900/fff/20x20.png?text=%20">|

## Contributing

To work on the theme:

1. Clone this repo and open in VS Code
2. Open run `View → Run`
3. Click `Launch Extension`. This will open up another VS Code Editor
4. Make changes to `cobalt2.json`. You will see changes reflected in the other editor that opened in step 3.

If you are making a Pull Request, Please give me a screenshot of before/after!

## Deploying a new version

These are mostly notes for me.

1. Increment the version number in `package.json`
1. run `npm run bundle`
1.

## I don't like something

First, this theme is new so if something is funky, please open an issue. There are many languages and parts of VS Code I don't use, so let me know!

These are the things we have control over. If you would like to change something, you can either open a PR and see if I'd like it added, or override the colours in your own settings.json file.

https://code.visualstudio.com/docs/getstarted/theme-color-reference

## Put Cobalt2 in other places!

* [Sublime Text](https://github.com/wesbos/cobalt2)
* [Atom](https://github.com/wesbos/Cobalt2-atom)
* [iTerm2](https://github.com/wesbos/Cobalt2-iterm)
* [Hyper Term](https://github.com/wesbos/hyperterm-cobalt2-theme)
* [Alfred](https://github.com/wesbos/Cobalt2-Alfred-Theme)
* [Slack](https://github.com/wesbos/Cobalt2-Slack)

## Thanks

Thanks to Roberto Achar for doing much of the initial porting to VS Code.
