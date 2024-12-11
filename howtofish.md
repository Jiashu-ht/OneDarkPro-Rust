## Where did you find the color scheme?

I found a useful website [coolors.co](https://coolors.co/), there are many palettes you can try.

## How did I achieve it?

Almost every programming language have a .tmLanguage.json file to describe how to analyze its tokens. The `"name"` in `/syntax/rust.tmLanguage.json` is the `"scope"` in `/themes/OneDarkPro-Rust.json`, then you can provide some settings to describe how to render the `"scope"` in editor.

Here is the link to rust.tmLanguage.json

[vscode/extensions/rust/syntaxes/rust.tmLanguage.json at main · microsoft/vscode (github.com)](https://github.com/microsoft/vscode/blob/main/extensions/rust/syntaxes/rust.tmLanguage.json)

In every theme.json in `/themes/...`, I add line 2740 - 3151 to it.